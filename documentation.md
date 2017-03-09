---
title: Documentation
teaching: 10
exercises: 20
questions:
- "Why should I invest time in good documentation?"
- “How does my target audience influence my documentation strategy?”
- "What are some published examples of good documentation?”
objectives:
- Describe how documentation is useful to yourself and to others
- Evaluate and rank the quality of comments in published notebooks 
keypoints:
- "Your code tells *what* you did. Your documentation tells *why* you did it and why it is important."
- "Documentation is the key to communicating your workflow and findings with your future self, collaborators, peers, and the general public."
---

## Overview
Documenting your process, especially as it concerns your data, is a key element of making your research more reproducible. Data manipulation is as integral to your analysis as statistical modelling and inference. If you do not thoroughly record all the steps you used to process data, it will likely be impossible for you, or anyone else, to repeat the analysis in the future ([Wilson et al. 2016](https://arxiv.org/abs/1609.00037)).  Using the Jupyter Notebook for scripting your data processing is powerful because it saves the code, which documents **what** action was taken, and the code can be interspersed with documenting the motivations behind each step, i.e., the **why**. There is also project-level documentation that isn't needed to understand a particular series of data processing steps, but to understand the organization of the project as a whole. Finally, documentation can be used to aid discoverability.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">&quot;If you want to slow down your competitors, give them all your data&quot; <a href="https://twitter.com/ctitusbrown">@ctitusbrown</a> <a href="https://twitter.com/hashtag/openscience?src=hash">#openscience</a> <a href="https://twitter.com/hashtag/titusbuzz?src=hash">#titusbuzz</a></p>&mdash; kelsey wood (@klsywd) <a href="https://twitter.com/klsywd/status/688086178172567552">January 15, 2016</a></blockquote> <script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

In this lesson, we will discuss the types and styles for documentation, their utility, and how you might tailor them for different audiences.

## A Gallery of Awesome Jupyter Notebooks
Wondering how others have been using the Notebook? Luckily, the IPython community curates a [_Gallery of IPython Notebooks_](https://github.com/ipython/ipython/wiki/A-gallery-of-interesting-IPython-Notebooks) that have been used for scientific research and educational tutorials. Browse the topics that pique your curiosity. 

Here are some cool features that have been added to or done with notebooks:
- [A table of contents, chemical equations, and an embedded video](http://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/Psychrometrics.ipynb)
- [Multipanel figures referred to as Figure 1A, 1B, etc as in a printed publication](https://anaconda.org/jbednar/plotting_pitfalls/notebook)
- [One about graffti in subway stations that that has no images of graffitti in a subway station](http://nbviewer.jupyter.org/github/invisibleroads/crosscompute-tutorials/blob/master/computational-analysis/300%20Count%20graffiti%20sightings%20within%20100%20feet%20of%20a%20subway%20entrance.ipynb) 
- [A collection of notebooks published as a textbook](https://github.com/tiagoantao/bioinf-python/blob/master/notebooks/Welcome.ipynb) 

### Exercise 1a
Evaluate and rank the breadth and quality of documentation in two notebooks. What is one good thing and one bad thing about each. Add your comments to the etherpad.

### Exercise 1b
Here is a piece of a notebook. Modify the existing markdown documentation to improve either the text itself or the formating. Past your modification in the etherpad.

### Optional Jupyter Notebook Demonstration
It is possible that the instructors and or helpers for this lesson will want to provide a brief demonstration for how they use the jupyter notebook in their own research. 

FIXME: This portion of the lesson will detail the best practices for doing that (i.e. time, providing the links, how to prepare, etc). 

## Documentation for different target audiences

- *For yourself*: You are your most important collaborator. Past self doesn’t answer email. Treat it like a notebook and detailing what you’ve done, why you did it, what worked and what didn’t work. A cool feature for the notebook is that you can view the order in which you have executed consecutive cells (e.g. In [38]: is followed by In [14]:) in the notebook as a record of your workflow. 
- *For your peers*: Before sharing your process with others, you will likely want to do some polishing. One step to polish is to restart and rerun all the cells so that the entire workflow is reproduced in order (e.g In [1]: is followed by In [2]:). Even though the input and output are adjacent to one another, you will want to intersperse the cells with text (in Markdown) documenting the rationale for the workflow and interpreting the results so that a reader understands the context.
- FIXME. add additional target audiences and or rationales/suggestions.

### Exercise 2
**Think Pair Share.** Should you leave commented-out code in your workflow when you publish it. Although it is useful to you while you’re working, is it useful to someone who is interested in your process? Is it necessary to understand and recreate your research?

## README file
It is important to **write a brief overview of your project**. A README file is a short file (think 1-pager) in the project's home directory, and typically is the main entry point for readers to the project, including in particular the code. It should thus answer questions others will commonly have when they come upon the project, including the following:

- the purpose of the project, such as which problem does it try to solve, and what is its scope
- how suitable for reuse is the project, such as stage of maturity it is in
- prerequisites and other dependencies, and how to satisfy or obtain them
- where and how to start for using it
- how to cite and/or terms of reuse
- are contributions welcome, and if so, how to best make them
- who to contact and how for questions

A README should be written in text, with markup that is easy to read (such as Markdown, [Reitz 2016](http://docs.python-guide.org/en/latest/writing/documentation/)). 

Based on the above, items to include in a README file include the following:

- the project's title
- a brief description
- a purpose statement
- up-to-date contact information
- a brief tutorial or how-to
- any relevant weblinks
- how to cite and license and/or terms of reuse

### Exercise 3
Compare and contrast two README files. 

-FIXME. Elaborate upon this exercise by providing links to notebooks with good, better, best README files.

## Wrap-up

At this point in the workshop, you have now learned a lot about using the Jupyter Notebook and how to document your process. Documentation of your process is very important for communicating your work to others but also as a tool for communicating with yourself. 

### Exercise 4

1. Take a moment to reflect on what you what learned in this workshop and what changes you want to make in your scienctific process. 
2. In your Jupyter notebook, write down what was the most useful thing that you learned.
3. In your Jupyter notebook, write one change you will make to your current workflow to make it more reproducible.
4. Set an alert to check in with yourself to see if you have implemented the change you wanted to make
