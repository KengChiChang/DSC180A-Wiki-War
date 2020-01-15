Assignment #1: The Data (Due Date: Jan 24th, 11:59 PM)
=======================

In this assignment, you will:

1.  Write a survey of the data and the context in which it was created
    (report).
    
2.  Describe and justify the data ingestion process in part 3
    (report).
    
3.  Develop code for ingesting and storing the data for later use
    (code).
    
The report portion of the assignment should be written in *markdown*,
saved as a pdf, and uploaded to Gradescope.

The data ingestion code should be submitted to Gradescope as a
programming assignment.

* * * * *

### Part 1

Introduce the problem being investigated and describe the data being
used to approach the problem. That is, describe the Wikipedia edit wars as 
framed in [this paper](https://arxiv.org/pdf/1107.3689.pdf).

Address the appropriateness of the data design and collection:

-   Why is the data appropriate to address the problem?

-   What are the potential shortcomings of the data for addressing the
    problem?
    
-   What measures have been used to address this problem in the past?

Summarize relevant details of the data generating process, describing
the population that the data represents, whether that population is
relevant to the question at hand, while addressing possible questions
of data reliability.

The material in this section should be informed by the paper listed above 
(especially section II), as well as background readings given in section.

### Part 2

Describe the data ingestion process you designed. This description should:

-   Specify from where the data originates, addressing legal issues
    pertaining to access.

-   Address any data privacy concerns and how your data pipeline
    handles them.

-   Lay out the schema and justify the decisions (what's the unit
    corresponding to an observation? What are the storage
    considerations?)

-   Address the applicability of the pipeline to similar data sources
    you might anticipate using in your future work on the subject
    (what might those be?). *Specifically describe the schema and what
    is needed*. You might find the "light dump" format on 
    [WikiWarMonitor](http://wwm.phy.bme.hu/light.html) to be a useful reference.

### Part 3

In a private GitHub repository for your project, structured according
to the methodology portion of the course, create a data ingestion
pipeline for the result-replication project. The pipeline should:

-   Ingest the [English Wikipedia edit history data](https://dumps.wikimedia.org/enwiki/20200101/) 
    (for consistency, let's start with the first 10 files starting with 
    `enwiki-20200101-pages-meta-history1.xml`).
    The data should be approriately subsetted and typed before being written 
    to file(s) on disk.

-   As a bonus, write your data ingestion code to write the data to a local 
    sqlite database. 
    This will be useful when working with multiple years or multiple languages 
    of data.

-   Store the data according to your designed schema, taking care to 
    appropriately type the data and implement the best storage design (which
    columns are needed and appropriate). The data will eventually be stored in 
    a database format both due to the size of the total collection of data.

-   The stored data should be in a form most appropriate for
    assessment and cleaning (EDA). 
    You might find the "light dump" format on 
    [WikiWarMonitor](http://wwm.phy.bme.hu/light.html) to be a useful reference.
