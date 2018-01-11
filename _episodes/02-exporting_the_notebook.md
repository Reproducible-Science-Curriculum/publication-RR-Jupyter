---
title: Exporting the Jupyter Notebook
teaching: 15
exercises: 10
questions:
- How can a Jupyter Notebook be converted into formats suitable for sharing and publishing when the native format is not supported by or not suitable for the recipient or purpose?
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

## Learning objectives

- Recognize and identify the various publishing related data formats.
- Use NBConvert to export your notebooks in a variety of formats, including HTML, PDF, LaTeX, and Markdown.
- Select an appropriate output format for your publication and justify your choice.

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

# Exporting a Notebook

Notebooks can be exported through web-based user interface, or from the command line. The web-based interface in essence runs the same command as one would on the command line, and hence has the same installartion dependencies.

## Dependencies

Exporting to LaTeX format will require [Pandoc](http://pandoc.org) to be installed. Exporting to PDF works through generating LaTeX first (and has those dependencies as well), and then needs a TeX installation to generate PDF.

## From the command line

The command is `jupyter nbconvert`, followed by notebook to convert, destination format (option `--to <format>`) and output filename (option `--output <filename>`):

```sh
$ jupyter nbconvert my_notebook.ipynb --to markdown --output output.md
```

Or to HTML format:

```sh
$ jupyter nbconvert my_notebook.ipynb --to html --output output.html
```

The default HTML template (`full`) includes headers and everything needed to form a complete HTML document. If you wanted to embed the resulting HTML as a fragment into, say, [a blog post](http://nbviewer.jupyter.org/github/fperez/blog/blob/master/120907-Blogging%20with%20the%20IPython%20Notebook.ipynb), use the `basic` template:

```sh
$ jupyter nbconvert my_notebook.ipynb --to html --template basic --output output.html
```

[Full documentation of the NBConvert tool](https://nbconvert.readthedocs.io/en/latest/) is available online.

## From the web-based user interface

In the _File->Download As_ menu, click the desired format. The conversion result will download to your computer.

## Using `nbconvert` to execute or extract code

The `jupyter nbconvert` command-line tool can be used to execute a notebook in whole and capture the result, by "converting" to the `notebook` format:

```sh
$ jupyter nbconvert --to notebook --execute my_notebook.ipynb
```

This generates `my_notebook.nbconvert.ipynb`, a new notebook that is the same as the source notebook but with all the output from code cells captured.

You can also extract the code from a notebook into an executable script, i.e., for an iPython notebook extract the Python code cells into a Python script:

```sh
$ jupyter nbconvert --to script my_notebook.ipynb
```

> ## Exercises
>
> Use one or more of the notebooks you have created during this course.
> * Export notebook(s) to the following formats, using the web-interface and the command line: Markdown, HTML
>    * Observe which files get created in which arrangement.
> * If `pandoc` and LaTeX are installed, also convert to LaTeX and PDF. Alternatively, can use a [tmpnb](https://github.com/jupyter/tmpnb) instance.
> * Extract executable Python script from Notebook.
>* Execute notebook so that the result(s) of the code blocks is captured in a new notebook.
{: .challenge}
