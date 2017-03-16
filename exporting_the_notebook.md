---
title: Exporting the Jupyter Notebook
teaching: 15
exercises: 15
objectives:
- Recognize and identify the various publishing related data formats.
- Use NBConvert to export your notebooks in a variety of formats, including HTML, PDF, LaTeX, and Markdown.
- Select an appropriate output format for your publication and justify your choice.
keypoints:
- Jupyter Notebooks can be converted to a number of formats relevant for scholarly communication and publishing, including HTML, PDF, and Markdown.
- Some code repositories, including GitHub, "know" how to render Jupyter Notebook format natively, and hence can be used for publishing notebooks for public viewing.
---

# Introduction

The native Jupyter Notebook format is not (yet?) among those accepted by scholarly publishers. Nor do web browsers know how to render it. Hence, when it comes time to publish your Notebooks, whether as part of a scholarly publication or simply to the web, it needs to be exported to a suitable output format. This is what the `jupyter nbocnvert` command does.

In this lesson, we will look at several formats relevant to scholarly publishing and publishing to the web, and we will learn how to export a notebook to such formats.

# Output formats

Scholarly publishers typically accept one or several Word-processing oriented formats, which are often binary or at least not meant for human consumption. For sharing or publishing data and analysis documentation, a text format that is easy to read and doesn't require special-purpose software is usually best. How do you determine the best format(s) to export your Notebook to?

Below we briefly describe a few formats that are widely used in scholarly communication.

## PDF

The PDF format is primarily used for paper-based output.  It contains information about the paper size and the margins.  Most web browsers know how to display it, but posting it to the web is somewhat like posting an raster-graphics image - it is not meant to be built upon or modified.

You would use the PDF format if you were interested in printing a copy of your notebook (for filing a paper copy, or hand-writing comments), or for sending to co-authors for reading and commenting (which will likely require tools such as Adobe Acrobat).

## HTML

HTML is the native format for the web.  It does not usually contain information about printing on paper.  Exporting to this format is a popular means of posting content to the web so that browsers can render it in the best way suitable for the device they are running on. (HTML is also a format rich in metadata and context information for search engines.)

If you have a website that you manage, publishing to HTML can make it easy to add your notebook as a page to a website.

## Markdown

Markdown is a plain-text format that was designed to both be human-readable without any special-purpose rendering tools, and to be easily exported to HTML.

## LaTeX

LaTeX is a plain-text format designed for authoring documents that will subsequently be typeset. It is widely used in publishing, and often accepted as a manuscript submission format, especially in fields that routinely need extensive mathematical typesetting capabilities. For publishing, sharing, and reading LaTeX is often compiled into a PDF format.  Depending on your field, your co-authors may be more comfortable editing LaTeX files than Notebook files.


## Reveal.js

# Discussion

Students can discuss the formats of recent publications they have read or created recently.  We could also find examples in the literature of each format.  (PLOS, Nature)

# Conversion of notebooks to other formats

One benefit of using an open format to write your research is that it is often possible to convert from the open format to other formats.
The Jupyter Notebook allows for the conversion of the open notebook format to other formats such as PDF and HTML.

You can produce a converted file from the Jupyter Notebook graphical interface.
In the File/Download As menu, there are options for

## Demonstration

Here we provide a short demo of downloading these formats

- PDF
- HTML
- Markdown

## Callout on PDF Export

We are going to demonstrate the PDF export ability of the notebook.  To do this on your Jupyter installation will require the installation of the Pandoc and LaTeX libraries.

## Callout on command-line NBConvert

Also, you can perform the export functions at the command line if you want to include the conversion step in a reproducible workflow.

```
jupyter nbconvert example_jupyter_notebook.ipynb --to pdf --output output.pdf
jupyter nbconvert example_jupyter_notebook.ipynb --to html --output output.html
jupyter nbconvert example_jupyter_notebook.ipynb --to html --output output
```

If you would like to learn more about the NBConvert tool, you can visit the
[documentation](https://nbconvert.readthedocs.io/en/latest/).

## Callout on images

If your Jupyter notebook has plot images generated from your code, they will be embedded in your HTML and PDF documents.  If however, you export to the Markdown format, they will be included in a folder in a zipped archive.

