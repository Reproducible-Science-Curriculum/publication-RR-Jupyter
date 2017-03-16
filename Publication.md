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

## Learning objectives

- Define and describe the importance of unique identifiers for data, publication and software.
- Identify appropriate resources for acquiring a unique identifier.
- Identify research artifacts on your own CV that would benefit from a DOI.
- Know how to locate the DOI for an existing publication.
- Compare and contrast different levels of open access. (needs an issue)
- Select appropriate journal or preprint service for their publication, data or software.
- Select an appropriate license for their publication, data, and software.
- Create an ORCiD.

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

## Licensing and Terms of Reuse

Upon publishing, different research products have different needs, and different eligibility for licensing. Determining an appropriate license should be an informed decision, and can be further complicated if multiple institutions with different intellectual property policies contributed to the products in a manner that can't be easily disentangled. Also, intellectual property and copyright laws differ across countries.

### Why license in the first place?

In many jurisdictions (including the US) intellectual property rights vest in the author of a creative work whether they assert it or not. Also, in most jurisdictions (including the US) the rights one has for work copyrighted by someone else is limited to fair use (and what one believes is fair use versus what a court will say is not necessarily the same thing).

Hence, if you make public work eligible for copyright protection yet don't say anything about terms of reuse, nobody has any rights to it beyond fair use. If you reuse work published in this way yourself, you risk that at any point the author will claim their right and asks to be compensated unless you cease to use the work immediately. Do you really want to base your research success on such a risk? If not, why do you expect anyone else to?

By publishing a research product, as a scholar one usually intends to benefit from that by allowing the product to have a wider impact. Not stating any licene or terms of reuse is effectively in contradiction to that.

### What is an open license

### Exercise 3:
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
    * Does it contain sensitive information (such as electronic [Protected Health Informtion](https://en.wikipedia.org/wiki/Protected_health_information) (ePHI)) that cannot be released to the public? Can you separate sensitive from non-sensitite and only public the latter? Is there a summarized form that can be published and that would still allow reproducing the results of the papper?
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

> _"I Am Not a Scientist, I Am a Number"_
Bourne PE, Fink JL (2008) I Am Not a Scientist, I Am a Number. PLoS Comput Biol 4(12): e1000247. [doi:10.1371/journal.pcbi.1000247](http://doi.org/10.1371/journal.pcbi.1000247)

Aggregating research products and their uptake in the scientific community as well as the public is very difficult without identifiers. Most authors of and contributors to research do not have distinctive names. If it's too difficult to aggregate someone's reseach outputs and their impact, then most research output will not be taken into account for assessment.

Enter [ORCID](https://orcid.org), the Open Researcher and Contributor ID. ORCID allows you to create and maintain a fairly comprehensive biographic, grant support, and publication profile. Funders, institutions, and publishers are increasingly adopting it. (At least in the sense of allowing you to record your ORCID; using it for features that convey tangible benefits to you are still in its infancy.)

### Exercise 5:

* You may already have an ORCID. Look yourself up on <https://ORCID.org>. If there is a record for yourself claim it if you haven't already.
* If there isn't a record, consider creating one. Try populating it with your research products (called _works_) using one of the available search-match-and-import sources. _(EuropePMC often works pretty well. Crossref does, too, but can sometimes show a lot of false positive matches. Try them out - you can abort if most matches are incorrect.)_
* Can you register your ORCID with your institution? Try inquiring with the digital scholarship group of your library.

### Aggregating your impact to tell your scholarship story

There are scholarly communication services that use author identifiers (such as ORCID) to aggregate the impact of the corresponding scholar's products. For example, [ImpactStory](http://impactstory.org) aggregates traditional citations as well as several other forms of uptake, including tweets and Wikipedia citations, that can measure different kinds of impact than scientific citations ([Priem _et al_, 2012](http://arxiv.org/abs/1203.4745)).
