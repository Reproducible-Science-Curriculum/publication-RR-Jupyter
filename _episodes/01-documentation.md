---
title: Documentation
teaching: 10
exercises: 20
questions:
- Why should I invest time in good documentation?
- How does my target audience influence my documentation strategy?
- What are some published examples of good documentation?
objectives:
- Describe how documentation is useful to yourself and to others
- Evaluate and rank the quality of comments in published notebooks 
keypoints:
- Your code tells *what* you did. Your documentation tells *why* you did it and why it is important.
- Documentation is the key to communicating your workflow and findings with your future self, collaborators, peers, and the general public.
- Jupyter Notebooks are powerful because it allows documenting the what (the code) and the why (the motivation and/or intepretation) interspersed with each other.

---

## Overview

Documenting your process, especially as it concerns your data, is a key element of making your research more reproducible. If you do not thoroughly record all the data manipulation steps you used to process data, it will likely be impossible for you, or anyone else, to repeat the analysis in the future ([Wilson et al. 2016](https://arxiv.org/abs/1609.00037)).  Using the Jupyter Notebook for scripting your data processing is powerful because it saves the code -- the **what** -- and interspersed it the motivations behind each step, i.e., the **why**.

There is also project-level documentation that isn't needed to understand a particular series of data processing steps, but to understand the organization of the project as a whole. Finally, documentation can be used to aid discoverability.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">&quot;If you want to slow down your competitors, give them all your data&quot; <a href="https://twitter.com/ctitusbrown">@ctitusbrown</a> <a href="https://twitter.com/hashtag/openscience?src=hash">#openscience</a> <a href="https://twitter.com/hashtag/titusbuzz?src=hash">#titusbuzz</a></p>&mdash; kelsey wood (@klsywd) <a href="https://twitter.com/klsywd/status/688086178172567552">January 15, 2016</a></blockquote> <script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

In this lesson, we will discuss the types and styles for documentation, their utility, and how you might tailor them for different audiences.

## Learning objectives

- Describe how documentation is useful to yourself and to others
- Evaluate and rank the quality of comments in published notebooks 
- Evaluate and rank the quality of existing metadata records.
- Describe the types of and importance of record level metadata. 

## Documentation best practices

### Consider the target audiences

- *For yourself*: You are your most important collaborator. Remember that your past self doesn’t answer email. Treat it like a digital notebook detailing what you’ve done, why you did it, what worked and what didn’t work.
- *For your peers*: One step before sharing your notebook with others is to restart and rerun all the cells so that the entire workflow is reproduced in order (e.g `In [1]:` is followed by `In [2]:`). Intersperse the code cells with text cells (in Markdown) documenting the rationale for the workflow and interpreting the results so that a reader understands the context.

### README file
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

### Exercise 1

Compare and contrast different research product archives for the quality and value of their documentation, and their corresponding utility for reuse.

* MS Salmanpour. (2016). Data set [Data set]. Zenodo. http://doi.org/10.5281/zenodo.193025
* Solange Duruz. (2016). Simulated breed for GENMON [Data set]. Zenodo. http://doi.org/10.5281/zenodo.220887
* Zichen Wang, Avi Ma'ayan. Zika-RNAseq-Pipeline v0.1. Zenodo; 2016. http://doi.org/10.5281/zenodo.56311



## Examples for learning what's possible

- [_Gallery of IPython Notebooks_](https://github.com/ipython/ipython/wiki/A-gallery-of-interesting-IPython-Notebooks) that have been used for scientific research and educational tutorials. Browse the topics that pique your curiosity.
- [Wang and Ma'ayan's Zika manuscript](https://github.com/MaayanLab/Zika-RNAseq-Pipeline/blob/master/Zika.ipynb)
- [The Python for Bioinformatics textbook, a collection of notebooks](https://github.com/tiagoantao/bioinf-python/blob/master/notebooks/Welcome.ipynb)
