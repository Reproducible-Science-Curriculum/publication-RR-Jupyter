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
- Select an appropriate license for their publication, data, and software.
- Create an ORCiD.
keypoints:
- _TODO_
---

# Identifiers and Licensing for Research Products

In this lesson we will learn some of the merits of globally unique and resolvable identifiers for research products; briefly introduce and discuss licensing issues and considerations; and end with creating a research author/contributor identifier for oneself, and how it can be used.

## Stable, globally unique, and resolvable identifiers for research products

### Why archives for research products, and why use them

A not so uncommon story:  _You’re a graduate student reading a paper on which you want to base your analysis approach, and for you therefore need to verify and reproduce the analysis The paper gives the lab's website as the link for obtaining the code. However, it turns out the researcher has since left that university, and their new lab's website no longer has a link to that code. After several weeks of silence the author responds to your email saying they will try and find the code, but they're working on a different project now. That was a month ago._

**Lab websites aren't archives.** Doing archiving well is non-trivial, and likely isn't your line of research. Use an archive that specializes in doing well what you need it from an archive.

There are many archives, for all imaginable purposes and domains.  In fact, there are so many that there is [re3data](http://www.re3data.org), a registry of repositories that allows browsing them by various attributes.

#### Exercise 1:

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

TBD...

### Exercise 2: Explore open access policies

1. Find one of the high impact journals in your field and look up their open access policies. Paste into the Etherpad the name of the journal and (. . . ). Discuss with a partner from a different discipline. What did you find?
2. For that journal, open a recent article and locate the DOI. Does your journal have a DOI?




## Licensing concerns

This isn't a workshop to teach you everything you need to know about licenses, but it is important to understand that published works, code, and data all have different needs related to licensing.  Selecting an appropriate license is a complex task that you'll likely want or need to connect with an expert to make an informed selection, particularly in complex situaions when you are navigating a collection of copyright agreements and IP rights.

Intellectual property and copyright concerns also differ greatly across countries and insitutions, so writing an explicit guide to cover all these situations is nearly impossible.  However, this section of the module will introduce you to some of the topics around licensing publications, code, and data.

The selection of a license should involve:

1. Looking toward your community to understand canonical standards for licensing.
2. Selecting a license you understand (either beforehand or something you research).

### Licenses for publications

Very commonly, people will select licenses out of the Creative Commons family.  While these licenses are regularly applied to data and code, there are more specific liceness that may suit your needs better.

Creative Commons licenses are well documented in human-oriented text: https://creativecommons.org/choose/

#### Licenses for data

Conversations about licenses for data, within the context of making the data publicly available, should actually start with understanding the origins of the data and first evaluating to see if the dataset may be made publicly available.  You need to determine if the data you are releasing is subject to copyright, contractual, or legal sensitivities. You acquired your data somehow, and that method or the content may have restrictions in place on the redistribution of it. Just because you can access the data source without paying money or logging into a website doesn’t mean that it is public data and you are freely available to harvest and distribute it.

Some starter questions to ask include:

1. Did you have permission to gather the data and/or are you abiding by any applicable Terms of Service by gathering, using, or publishing that data?
2. Are you including data values where entities, such as publishers or users, hold copyright?
3. Was your access to the original data you’ve processed under a contract that restricts or has stipulations about how derivatives are released?
4. Does your home institution have policies on how data products and other intellectual property content is released and licensed?
5. These scenarios will impact your ability make the data public and which kind of license you can attach to it, which is why I always suggest working through this process in the hypothetical when you begin a project. Data copyright and IP control are thorny issues that, like other copyright domains, vary by country, institution, and year of creation.

(Some content borrowed from a Data Carpentry [blog post](http://www.datacarpentry.org/blog/data-licensing/))

### Licenses for software


### Exercise n:  Break out into three groups

Group 1: investigate the [creative commons wizard](https://creativecommons.org/choose/)
Group 2: investigate the [ODbL guide](http://opendatacommons.org/guide/)
Group 3: work through the [OSS license selector](http://oss-watch.ac.uk/apps/licdiff/)

Take 5 minutes to review this information and place your findings into the etherpad.  When dont place your green stickies up.

The instructor will review the report outs and lead discussion.

1. What were your general impressions?
2. What was the biggest concern with your license domain?
3. What did you find helpful?
4. What did you find confusing?

## ORCiDs

Let's make ORCiDs!

Think you have one?  Try looking yourself up.  Otherwise, create an account on ORCiD.

[ORCiD.org](https://orcid.org/)

Take some time to explore the options within your profile.  Under works, click Add Works.  You can search several databases from within or you can add works manually.

Issue...add new info.

Once everyone has their ORCiD created, all learners should navigate to [Impact Story](https://impactstory.org) and link their accounts.

Learners who already have accounts can help those next to them get things set up.  Learners who object to creating accounts may choose to akip this activity.


