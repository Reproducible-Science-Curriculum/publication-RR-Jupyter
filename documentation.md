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

## Documentation for different target audiences
*For yourself*: You are your most important collaborator. Past self doesn’t answer email. Treat it like a notebook and detailing what you’ve done, why you did it, what worked and what didn’t work. A cool feature for the notebook is that you can view the order in which you have executed consecutive cells (e.g. In [38]: is followed by In [14]:) in the notebook as a record of your workflow. 
*For your peers*: Before sharing your process with others, you will likely want to do some polishing. One step to polish is to restart and rerun all the cells so that the entire workflow is reproduced in order (e.g In [1]: is followed by In [2]:). Even though the input and output are adjacent to one another, you will want to add documentation with markdown formatting to add the rational for you workflow and the interpretation so that the reader understands the context.

- FIXME. add additional target audiences and or rationales/suggestions.

- FIXME. Add exercises.
- FIXME. Add discussion.

## README file
It is important to **write a brief overview of your project**. A README file is short file in the project's home directory that explains the purpose of the project. This file should contain the project's title, a brief description, up-to-date contact information, and possibly an example or two of how to run various cleaning or analysis tasks. It is often the first thing users of your project will look at, so make it explicit that you welcome contributors and point them to ways they can help.

-FIXME. Add exercise.

## Metadata
A key step in the reproducible research is to link the relevant metadata, or the data that describes the data. Metadata provides the context for in interpreting the data and results and is crucial for reusability and discovery.  Metadata should be clearly defined and tightly integrated with data and project ([Hart et al. 2016](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005097#sec008)). 

In the next section, we will discuss and work with record-level metadata. 
