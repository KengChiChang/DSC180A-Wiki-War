Assignment #3: Replication Part 2 (Due March 14, 11:59 PM)
===============================

In this assignment you will:

1.  Describe the experimental design and write a summary of the results with code-generated figures and tables (report)

2.  Develop code to replicate the main result under consideration, using methodological best practices from class (code)

* * * * *

This project consists of the entire 'result replication' as a single
report and code artifact. You should put together the work from
assignments 1 and 2, along with additional material from more recent
work. You previous work should be considered a *rough draft* of the
final work you are turning in for assignment 3. Make sure to include all 
relevent tables and figures in your report and explain them in words and/or
math. Don't just print them out.

### Part 1 (Report)

Create a report consisting of:
* An introduction to the problem (assgn 1)
* An introduction to the data and data generation process (assgn 1)
* A brief review of historical context (assgn 1)
* EDA, assessment of reliability of data, summary statistics, 
  need for cleaning and justification for approach to cleaning (assgn 2)
* Explanation of the calculation of M-Statistic (assgn 2)
* Calculate M-Statistic using cleaned data in light-dump format (assgn 2)
  * Present a table of top articles with max/min M-statistic and explain 
    what you find
  * Present the evolution of M-statistic over time for an article with high M 
    and another with low M and explain what you find
  * Present summary statistics (distributions, classifications, etc) of the 
    M-statistics and explain what you find
* Calculate M-Statistic using [raw data](https://dumps.wikimedia.org/enwiki/20200201/) for two articles: Anarchism and Barack Obama (**new**)
  * Present the evolution of M-statistic over time (until 2019) and explain 
    what you find
* Critique of the short comings of M-Statistic (**new**)
* Discuss and validate some other measures of controversiality (**new**)
  * There are many related discussions in weekly readings 
    (text-based, network-based, etc)
* Conclusion (**new**)

*Note:* Since the "parent_id" itself is not reflecting reverts, you will need 
to store the text of the articles for each version and then check, for each 
new version, whether it is a revert (so that it has exactly the same text as 
some earlier versions) while you are processing raw data. Since you only need
to do so for two articles, this won't be that hard. The raw data are stored in 
alphabetical order on Wikimedia website, so Anarchism and Barack Obama should 
be in the first few files. 

### Part 2 (Code)

Develop code in a GitHub repository that replicates the main result of
question at hand. This repository will run the replication from
end-to-end (data ingestion to generating the results that inform the
reports) using best-practices described in class.

You code should satisfy the following criteria:
* Conform to the template structure of the methodology portion of the
  course.
* Use configuration files to parameterize the inputs of your pipeline.
* Use a `run.py` file to put together the processing logic, using
  commandline targets.
* Runnable on the DSMLP servers in an existing Docker Image (either on
  given to you (e.g. `ucsd-ets/scipy-ml`, or one created by you).
* Use a small amount of versioned test data that quickly verifying the
  runnability of the project.
* A configuration file `config/env.json` that contains the following
  information:
  * a key `docker-image` with the value a DockerHub path (e.g. the
    input of the `-i` flag when starting a container on the DSMLP
    server.
  * a key `output-paths` with the value a list of output files created
    (the files with the results of the replication).
* All criteria specified in assignments 1 and 2.

Your code will be turned into gradescope directly from
GitHub. Alongside inspecting the files of the repository, it will
be graded using the following procedure:

1. Your submitted repository will be uploaded to a DSMLP server.
2. A container will be started using the specified Docker Image in
   your repository's `env.json`
3. In this container, the following command will be run: `python
   run.py test-project`
4. Running the above target will run your replication on a small
   amount of test data. The existence/content of output test files
   will be checked.

*Note:* You should test running your project from end-to-end, by
pulling it from GitHub and trying to run the targets yourself, in a
clean directory! (E.g. create a directory `~/test-run/`, and clone/run
the project in that directory).