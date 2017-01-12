---
title: Documentation
teaching: 10
exercises: 20
questions:
- "Why should I invest time in good documentation?"
- “How does my target audience influence my documentation strategy?”
- "What are some published example of good documentation?”
objectives:
- Describe how documentation to useful to yourself and to others
- Evaluate and rank the quality of comments in published notebooks 
keypoints:
- "Your code tells *what* you did. Your documentation tells *why* you did it and why it is important ."
- "Documentation is the key to communicating your workflow and findings with your future self, collaborators, funders, and the general public."
---

## Introduction
A key step reproducible research is the documenting your process. Data manipulation is as integral to your analysis as statistical modelling and inference. If you do not record all the steps used to process data thoroughly, it will be impossible for you, or anyone else, to repeat the analysis ([Wilson et al. 2016](https://arxiv.org/abs/1609.00037)).  Using the Jupyter Notebook for scripting is powerful because you saved code documents **what** action was taken and it can be reproduced by anyone with the notebook, data, and libraries. However, documentation is necessary to convey the **why**. 
In this lesson, we will discuss the types and styles for documentation, their utility, and how you might tailor them it for different audiences.

## A Gallery of Awesome Jupyter Notebooks
You are now familiar with the process of creating and using a Jupyter Notebook for reproducible research. You may be wondering how others have been using the Notebook. Luckly, the IPython community curates a **Gallery of IPython Notebooks” that have been used for science research and educational tutorials [here](https://github.com/ipython/ipython/wiki/A-gallery-of-interesting-IPython-Notebooks). On your own, I encourage you to browse the topics that peek your curiosity. 
Here are some cool features that have been added to notebooks:
- [One with a table of contents, chemical equations, and a an embedded video](http://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/Psychrometrics.ipynb)
- [One with multipanel figures that are nicely refered to with Figure 1A, 1B, etc like you see in a printed publication](https://anaconda.org/jbednar/plotting_pitfalls/notebook)
- [One about graffti in subway stations that that has no images of graffitti in a subway station](http://nbviewer.jupyter.org/github/invisibleroads/crosscompute-tutorials/blob/master/computational-analysis/300%20Count%20graffiti%20sightings%20within%20100%20feet%20of%20a%20subway%20entrance.ipynb) 
- [A collection of notebooks that were published as a textbook](https://github.com/tiagoantao/bioinf-python/blob/master/notebooks/Welcome.ipynb) 

### Exercise 1a
Evaluate and rank the breadth and quality of documentation in two notebooks. What is one good thing and one bad thing about each. Add your comments to the etherpad.

### Exercise 1b
Here is a piece of a notebook. Modify the existing markdown documentation to improve either the text itself or the formating. Past your modification in the etherpad.

### Optional Jupyter Notebook Demonstration
It is possible that the instructors and or helpers for this lesson will want to provide a brief demonstration for how they use the jupyter notebook in their own research. 

FIXME: This portion of the lesson will detail the best practices for doing that (i.e. time, providing the links, how to prepare, etc). 

## Documentation for different target audiences

- *For yourself*: You are your most important collaborator. Past self doesn’t answer email. Treat it like a notebook and detailing what you’ve done, why you did it, what worked and what didn’t work. A cool feature for the notebook is that you can view the order in which you have executed consecutive cells (e.g. In [38]: is followed by In [14]:) in the notebook as a record of your workflow. 
- *For your peers*: Before sharing your process with others, you will likely want to do some polishing. One step to polish is to restart and rerun all the cells so that the entire workflow is reproduced in order (e.g In [1]: is followed by In [2]:). Even though the input and output are adjacent to one another, you will want to add documentation with markdown formatting to add the rational for you workflow and the interpretation so that the reader understands the context.
- FIXME. add additional target audiences and or rationales/suggestions.

### Exercise 2
**Think Pair Share.** Should you leave commented-out code in your workflow when you publish it. It is useful to you while you’re working, but is it useful to someone who interested in your process. It not necessary to recreate your research?

### README file
It is important to **write a brief overview of your project**. A README file is short file in the project's home directory that explains the purpose of the project. This file is the main entry point for readers of the code. It is often the first thing users of your project will look at, so make it explicit that you welcome contributors and point them to ways they can help. It should be raw text or written in some very easy to read markup, such as Markdown ([Reitz 2016](http://docs.python-guide.org/en/latest/writing/documentation/)). 

Some things to include in the README file are:

- the project's title
- a brief description
- a purpose statement
- up-to-date contact information
- a brief tutorial or how-to
- any relevant weblinks 

### Exercise 3
 Compare and contrast two README files. 

-FIXME. Elaborate upon this exercise by providing links to notebooks with good, better, best README files.
