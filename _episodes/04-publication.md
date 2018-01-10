---
title: Identifiers and Licensing for Research
teaching: 15
exercises: 20
objectives:
- Define and describe the importance of unique identifiers for data, publication and software.
- Identify appropriate resources for acquiring a unique identifier.
- Identify research artifacts on your own CV that would benefit from a DOI.
- Know how to locate the DOI for an existing publication.
- Compare and contrast different levels of open access. (needs an issue)
- Select appropriate journal or preprint service for their publication, data or software.
keypoints:
- _TODO_
---

# Identifiers and Licensing for Research Products

In this lesson we will learn some of the merits of globally unique and resolvable identifiers for research products; briefly introduce and discuss licensing issues and considerations; and end with creating a research author/contributor identifier for oneself, and how it can be used.

## Learning objectives

- Define and describe the importance of unique identifiers for data, publication and software.
- Identify appropriate resources for acquiring a unique identifier.
- Identify research artifacts on your own CV that would benefit from a DOI.
- Know how to locate the DOI for an existing publication.
- Compare and contrast different levels of open access. (needs an issue)
- Select appropriate journal or preprint service for their publication, data or software.

## Stable, globally unique, and resolvable identifiers for research products

### Why archives for research products, and why use them

A not so uncommon story:  _You’re a graduate student reading a paper on which you want to base your analysis approach, and for you therefore need to verify and reproduce the analysis The paper gives the lab's website as the link for obtaining the code. However, it turns out the researcher has since left that university, and their new lab's website no longer has a link to that code. After several weeks of silence the author responds to your email saying they will try and find the code, but they're working on a different project now. That was a month ago._

**Lab websites aren't archives.** Doing archiving well is non-trivial, and likely isn't your line of research. Use an archive that specializes in doing well what you need from an archive.

There are many archives, for all imaginable purposes and domains.  In fact, there are so many that there is [re3data](http://www.re3data.org), a registry of repositories that allows browsing them by various attributes.

### Exercise 1:

* Identify requirements and desirable features for an archive for a non-manuscript research product of your choice.
* Discuss how archiving the research product as supplementary material of the manuscript would or not meet these requirements (or desiderata).

### Why globally unique resolvable identifiers for non-paper research products?

One of the key benefits of using an archive is that nearly all of them will assign a globally unique resolvable identifier to deposits. This is because deposit identifiers benefit their users - both depositors, and those reusing deposits:

* Ability to identify and cite the deposit in a manuscript and a CV
* Ability to track views, downloads, or more generally impact
* Ability to identify exactly what record, and which version of it was (re)used

### Why DOIs

DOIs (digital object identifiers) are only one type of unique identifier, but is the most frequently used type in scholarly communication, and for identifying research products. Some of its benefits include:

* Allows separating content from who hosts the content.
* Cannot be minted ad-hoc, and instead require interacting with a registration agency, which typically need to be paid a fee. This fosters metadata quality, and assigns clear responsibility for maintaining the DOI's continued resolution.
* Publishers, and the publishing industry, knows how to deal with them.
* Practically every scholar knows how to deal with them.

While DOIs on the surface all look the same, some expectations for their associated metadata (and [programmable APIs](http://citation.crosscite.org/docs.html) differ based on the issuing DOI registrar (often referred to as "type of DOI"). In scholarly publishing and communication, the most frequently encountered DOI registrars are CrossRef (issues almost all scientific paper DOIs, works with publishers) and DataCite. The latter is used for all kinds of "other" research products, including data, software, source code, and preprints.

### Exercise 2:

Identify the research products that underly and support a manuscript of yours in preparation (or one recently published if those research products became supplementary materials or were not published). Consider and discuss the following choices of repositories for fit for purpose:

* [Dryad](http://datadryad.org)
* [Zenodo](http://zenodo.org)
* [Harvard Dataverse](https://dataverse.harvard.edu) (or UNC's [Odum Dataverse](https://dataverse.unc.edu))
* [Figshare](http://figshare.com)
* [Journal of Open Source Software](http://joss.theoj.org)
* Your university's Institutional Repository (IR)
* A public source code repository ([Github](http://github.com), [Bitbucket](http://bitbucket.com), [Gitlab](http://gitlab.com) etc)

Explain your preferences, and what advantage it would (or would not) offer over supplementary materials. Discuss which of the products you identified should get their own identifier, and whether having a DOI for them would be advantageous or not.
