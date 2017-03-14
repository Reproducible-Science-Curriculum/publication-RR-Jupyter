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

This lesson serves to introduce leaners to DOIs, other identifier systems, breifly introduce and discuss the complex needs of licensing, and ends with learners creating ORCiD profiles and exploring Impact Story.

## Stable identifiers

### What is a DOI and the landscape of identifiers

The story:  You’re a graduate student reading a paper and the authors have made the code for their analysis available on their labratory's website. You'd like to reuse and reference some of the code for your current project. The code for the analysis is linked in the footnotes, but the researcher has since left that university.  Their new lab's website no longer has a link to that code and no one is responding to your emails.  How do you access the code? You don't!  :-(

There were a few ways that you could have been saved.

1.  The researcher uploads their code to a repository, such as their institutional repository, Zenodo, FigShare, or even GitHub\*  
2.  The researcher could have linked thier GitHub repository to a Zenodo or FigShare archive, and provided the corresponding DOI within the paper.  Even if they later take down their GitHub repository, the DOI should still resolve to that archival entry within the repository.  Additionally, the repository could update the redirect from the DOI to wherever the archived files moved to.

In either condition, the DOI will remain stable within the manuscript and the paper would not need to be updated even if the content the DOI redirects to moves.  Should the underlying content move, the DOI resolver can be updated with that new location.

Note that GitHub repositories can still be moved and deleted, but in some contexts still more stable than just a personal website.

DOIs (digital object identifiers) are just one type of unique identifier, you may see other kinds across the publication landscape.  Additionally, there are two types of DOIs:  CrossRef and DataCite.  Each of these DOIs should resolve under the normal process, the difference is mainly just in who is issuing them out.  CrossRef DOIs are generally the kind that is created for papers and publications from journals while DataCite DOIs are created for repository resources, such as data and code.  This should not directly impact your selection of repositories.  Other common unique identifiers are [Handles](https://en.wikipedia.org/wiki/Handle_System), which you will see commonly throughout institutional repositories in academic institutions.

### Exercise 1: Find the DOI for a published article, dataset, and code

Pick out a paper, either one that you know very well, one of your own, or just travel to a journal website of your choice and pick out a recent paper they are highlighting.  Identify the DOI for that paper.

### What does having a DOI mean?

Most researchers are used to seeing DOIs in the context of papers and publications within journals.  However they are used, DOI and other similar identifiers are meant solely to be unique and stable identifiers for resources.  This means they can be assigned to smaller portions of papers, such as figures, or even for individual proteins or crystal structures within repositories.

The implication of having a DOI is solely of stability and not necessarily of quality.  That said, individual repositories may have specific requirements about when and how they issue DOIs for resources.  The DOI service is just a system that they utilize to create identifiers.

### Exercise 2:  Identify 2 of your works that might benefit from DOIs



## Open Access levels

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


