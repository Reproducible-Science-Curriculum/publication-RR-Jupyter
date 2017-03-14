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

## Licensing and Terms of Reuse

Upon publishing, different research products have different needs, and different eligibility for licensing. Determining an appropriate license should be an informed decision, and can be further complicated if multiple institutions with different intellectual property policies contributed to the products in a manner that can't be easily disentangled. Also, intellectual property and copyright laws differ across countries.

### Why license in the first place?

In many jurisdictions (including the US) intellectual property rights vest in the author of a creative work whether they assert it or not. Also, in most jurisdictions (including the US) the rights one has for work copyrighted by someone else is limited to fair use (and what one believes is fair use versus what a court will say is not necessarily the same thing).

Hence, if you make public work eligible for copyright protection yet don't say anything about terms of reuse, nobody has any rights to it beyond fair use. If you reuse work published in this way yourself, you risk that at any point the author will claim their right and asks to be compensated unless you cease to use the work immediately. Do you really want to base your research success on such a risk? If not, why do you expect anyone else to?

By publishing a research product, as a scholar one usually intends to benefit from that by allowing the product to have a wider impact. Not stating any licene or terms of reuse is effectively in contradiction to that.

### What is an open license

Exercise 3:
* Enumerate provisions (rights) that you think you can expect to be granted for a "openly licensed work".

The argument is sometimes made that it is not well defined what constitutes an Open License. This is, however, not true: the [Open Definition](http://opendefinition.org/od/2.1/en/) lays out very clearly the basic rights that any Open License needs to grant. Particularly noteworthy for scientists, _the definition does not allow to discriminate between academic and commercial reuse._

### Special case: Licensing for scientific open source software

The number of open source licenses for software can seem bewildering. However, for most scientific software, the important parts can be boiled down to the following.

1. [_Choose a license_](https://choosealicense.com/) and state it.
2. Choose an [OSI-approved license](https://opensource.org/licenses) instead of using or creating a bespoke one.

The choice of license does have consequences, and these consequences may matter for some projects. For an accessible guide written by a scientist for scientists see the following paper:
> Morin A, Urban J, Sliz P. A Quick Guide to Software Licensing for the Scientist-Programmer. Lewitter F, editor. PLoS Comput Biol. 2012;8: e1002598. [doi:10.1371/journal.pcbi.1002598](http://doi.org/10.1371/journal.pcbi.1002598)

### Special case: Licensing for scientific data

In most jurisdictions (including the US), most data are considered facts of nature and are as such not eligible for copyright protection. This is so [even if it took enormous effort](https://en.wikipedia.org/wiki/Sweat_of_the_brow) or financial investment to obtain or measure the data. A license asserts copyright, and hence applying one to data that isn't eligible for such protection creates a murky legal situation at best.

In practice, research data can take many forms. Simple measurements of natural phenomenons or observations of facts are almost certainly not copyright eligible. For example, the observation that a bird of a rare species was observed at certain date and time in a certain location is likely not eligible for copyright. However, the photo that documents the observation may well be. More generally, information that can be viewed as a creative expression but is used as data could be copyright eligible.

Some jurisdictions (though not the US, but for example the EU) also recognize property protection for _databases_ ([_Sui generis_ database right](https://en.wikipedia.org/wiki/Sui_generis_database_right)). Databases whose individual records constitute simple facts of nature often assert this right without further elaboration, even though a _sui generis_ protection normally won't extend to individual database records.

When you publish your data, consider the following.
1. Understand the origins of the data and evaluate whether the dataset may be made publicly available.
    * Does it contain sensitive information (such as ePHI) that cannot be released to the public? Can you separate sensitive from non-sensitite and only public the latter? Is there a summarized form that can be published and that would still allow reproducing the results of the papper?
    * Were some of the data obtained under a Data Use Agreement, and which permissions does the DUA afford for publication.
    * Does someone other than you own copyright in some of the data?
2. Aim to improve legal clarity rather than murkying it.
    * Don't assert or withhold rights when the legal basis for that is lacking or shaky. Licenses assert (intellectual or _sui generis_) property protection. Hence the enforceability of any rights you withhold for reuse rests on whether the data you are claiming rights for are indeed eligible for such protection.
    * Don't license data that's already in the public domain.
3. If you generated the data, consider _waiving your rights_ (to the extent that a jurisdiction gives you any) by applying the [Creative Commons Zero](https://creativecommons.org/publicdomain/zero/1.0/) public domain waiver. (["No Rights Reserved"](https://creativecommons.org/share-your-work/public-domain/cc0/))
    * This is also a great way to improve legal clarity.
    * Some repositories may require you to do this, for example [Dryad](https://datadryad.org/pages/faq#info-cc0).
4. For expectations from those reusing the data, state those clearly.
    * There are many ways to meet legal requirements imposed by licenses (such as attribution) but that don't meet disciplinary norms or your expectations.
    * State how you want the dataset to be cited. Waiving one's legal rights does not mean that disciplinary norms and expectations don't apply.
    * Some data repositories will do this for you (for example Dryad).

The terms through which data is acquired may have implications for publishing, and it's therefore worth thinking through those from the get go.

### Exercise 4:

Determine and dicuss which licensing, public domain waiver, and/or terms for reuse would be suitable for the research products of yours that you previously identified.

## ORCiDs

Let's make ORCiDs!

Think you have one?  Try looking yourself up.  Otherwise, create an account on ORCiD.

[ORCiD.org](https://orcid.org/)

Take some time to explore the options within your profile.  Under works, click Add Works.  You can search several databases from within or you can add works manually.

Issue...add new info.

Once everyone has their ORCiD created, all learners should navigate to [Impact Story](https://impactstory.org) and link their accounts.

Learners who already have accounts can help those next to them get things set up.  Learners who object to creating accounts may choose to akip this activity.


