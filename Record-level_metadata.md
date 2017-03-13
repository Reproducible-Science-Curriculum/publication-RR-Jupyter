
# Creating Record Level Metadata

Learning objectives:

* Evaluate and rank the quality of existing metadata records.
* Describe the types of and importance of record level metadata. 
* Compose an appropriate set of descriptive keywords for a given text.


## Ranking records

### Exercise 1 - rank these Zenodo entries in terms of information quality (7 minutes)

Ranking worse to better zenodo records:

* https://zenodo.org/record/220887 - Simulated breed for GENMON
* https://zenodo.org/record/193080 - Raw data for a manuscript. Gives manuscript title.
* https://zenodo.org/record/215975 
* https://zenodo.org/record/193025 
* https://zenodo.org/record/158943 - data, jupyter notebook, video, and readme file for a paper (http://iopscience.iop.org/article/10.1088/0143-0807/38/1/015005/meta#footnotes)

Look through these three (TODO, [issue 1](https://github.com/Reproducible-Science-Curriculum/publication-RR-Jupyter/issues/1)) and rank them from 1 (most helpful/informative) to 3 (least helpful/informative).  (5-7 minutes).

Place your green sticky up when you are done.

### Group discussion (5 minutes)

Tally for who ranked each record for being the most informative:

* [record number...]
* [record number...]
* [record number...]

Tally for who ranked each record for being the least informative:

* [record number...]
* [record number...]
* [record number...]

Discussion questions:

* What were the criteria that you used to rank? 
* What was missing? 
* What was the most helpful? 
* What was the most critical piece of information? 


## The metadata in your life

You're used to metadata within your research. You've got metadata about specific data points, observations, samples, etc.  But there are many more parts of metadata.  

The information that you were looking at in the Zenodo records is metadata.  Metadata about the dataset (record) on that page.  Let's take a look at the pieces of these pages.

Point out where these pieces are:

* Title
* Authors
* Description
* Keywords

This information is important because:

* people need to find your stuff
* people need to know what your stuff is

Let's think about the workflow of discovery, the user...

1. Searches for something
2. Reviews the results, based on the title and other information coming up in the search results pages
3. Might add some filters to reduce and refine the results
4. Selects a record to review and goes to that record's page
5. Reviews the new information on this page, including the fuller description, keywords, and other readme/documentation files.
6. Downloads and digs in to the data files

This person would continue to move through these steps so long as the information continues to look sufficiently interesting.

<iframe src="https://zenodo.org/record/158943" width=700 height=350></iframe>

## Keywords, best friend/worst enemy (7 minutes)

There are many places where you might need to add in tags and keywords about items.  You do this for organizing your pictures, maybe your evernote notes or your Jira tickets.

The keywords you add need to be items:
* not too general that it doesn't disambiguate it from anything else or 
* so specific that it would never be searched for.

The same keyword may count as too general, too specific, or just right depending on the platform you are using.

For example, can you think of times when the following keywords would be useful or not useful?  Think about usage on GitHub issue tags, Evernote tags, article descriptive keywords, a relevant conference presentation, etc. (pick 2-3 that are relevant to this group and write them down).

* python
* data
* code
* (TODO: add in more example keywords that would be overly specific to specific domains)

For example, tagging a task in your ticketing system as Python might be relevant if it is about a python lesson development when you normally work in other languages. It may not be that useful for a ticket about a python project.

### Exercise 2:  Picking keywords for the gapminder data

We're going to take a more critical look at the gapminder dataset that we've been using over the course of the workshop.  Imagine that you are finishing up a project on this dataset and preparing to deposit your data and Jupyter Notebook into something like Zenodo.  You've been asked to come up with a set of keywords to describe your deposit.

#### Step 1: You pick out keywords (3 minutes)

* Individually pick max five keywords for the gapminder dataset.

You are free to pick any five (or fewer) keywords that you feel are relevant.

#### Step 2:  Check with your partner (3 minutes)

* Work with your partner, and together decide on a new set of five (or fewer) keywords.

You are free to mix and match between either of your keyword sets, or you might want to create new ones.  You must decide and agree on your new keywords.

#### Step 3:  Check with the room (5 minutes)

* Each pair (or other small group) places their keywords into the etherpad and the room reviews.

The entire room now decides on a single set of 5 keywords.  Again, this may be some form of union or new creation.
