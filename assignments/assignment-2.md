Assignment #2: Cleaning and EDA (Due Feb 15, 11:59 PM)
===============================

In this assignment you will:

1.  Statistically assess and explain/analyze the features/statistics/target 
    needed for the replication (report).
    
2.  Develop replication and data cleaning (code).

* * * * *

### Part 1

* (Download) Download the 
    [light dump data](http://wwm.phy.bme.hu/LD/ld_en_wiki.zip) 
    of the English Wikipedia from the 
    [WikiWarMonitor](http://wwm.phy.bme.hu/light.html) website. 
    -   Articles are separated by their names within the file. 
    -   Each line of the file below the name of an article, contains a 
        delimiter "^^^" followed by the timestamp of each edit, a binary flag 
        of 0/1 corresponding to a normal/revert edit, an accenting integer 
        code, starting from 1, assigned to each new revision, whose text is 
        not similar to any of the previous ones, otherwise the same code as 
        the previous version with the similar text, and finally the editor of 
        the version.

* (Descriptive Stats) Statistically summarize the attributes in the light dump 
    data.

* (Edit Wars) Replicate the paper on edit war.
    -   Derive the algorithm described in [Yasseri et al 2012a](https://arxiv.org/pdf/1107.3689.pdf) 
        and calculate the M statistic for each article in the English 
        Wikipedia from the light dump data.
    -   Describe and visualize the most and the least controversial articles.
    -   Describe and visualize how controversiality for some articles evolve 
        over time. You can take [Yasseri et al 2012b](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0038869) 
        as a reference.
        
* (Raw Data to Light Dump Revisited) 
    -   Validate the data ingestion you did for the first assignment by 
        comparing the light dump downloaded from WikiWarMonitor with the data 
        you ingested over the same set of articles and the same period of 
        time. Are they consistent? If not, why?
    -   Revise the code for data ingestion (from raw format to light dump 
        format) and cleaning to enhance efficiency.


### Part 2

Develop code to calculate the M statistic from data in light dump format. 
Revise the code to ingest and clean the data from raw format to light dump 
format. Such code should conform to the methodology portion of the course 
(e.g. using the project template).

In particular, your project should have a `run.py` with the following
targets:
1. `data` creates the data needed for analysis.
2. `process` cleans and prepares the data for analysis (e.g. cleaning
   and feature creation).
3. `data-test` ingests a small amount of *test data* (that `process`
   can then process).
