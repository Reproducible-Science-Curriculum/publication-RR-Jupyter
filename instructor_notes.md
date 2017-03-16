# Instructor notes

## Motivation

## Narrative

## Timeline  
Four modules:  
1. Exporting your Notebook (35 minutes)  
2. Documentation (35 minutes)  
3. Record-level Metadata (35 minutes)  
4. Publishing your Work (50 minutes)  

Total: 2 hrs, 35 minutes  

## 1. Exporting your Notebook

### Timeline
- Presentation of different formats (10 minutes)
- Search for examples of different formats online and discuss (10 minutes)
- Demonstration of Jupyter Notebook export (10 minutes)

### Customization
- If your participants are expecting to be able to create PDF images, you can instruct them to download and install the Pandoc and LaTeX packages in advance of the workshop.  However, these may produce installation troubles.
    * Use [TeX Live](https://www.tug.org/texlive/quickinstall.html) for installing TeX/LaTeX.
    * For those using `conda` already as their installer, the following command should [install Pandoc without issue from the conda-forge](https://anaconda.org/conda-forge/pandoc):
        conda install -c conda-forge pandoc=1.19.2

- If installation of TeXLive and Pandoc risk going beyond the scope of the workshop, consider using or hosting an instance of [tmpnb](https://github.com/jupyter/tmpnb), "the temporary notebook service".
    * The institution hosting the workshop may already run such a service. It's worth enquiring with the campus IT group.

- Time permitting, and depending on students' experience level with installing Python packages you may not currently have installed, you can also try "real" notebooks from publications or books, such as some of the following:
    * [Notebooks from 'Python for Bioinformatics'](https://github.com/tiagoantao/bioinf-python/blob/master/notebooks/Welcome.ipynb). In particular, those under the section _Simulation in Population Genetics_ don't need to download datasets as the first step.
    * Wang Z and Ma'ayan A. An open RNA-Seq data analysis pipeline tutorial with an example of reprocessing data from a recent Zika virus study [version 1; referees: 2 approved]. _F1000Research_ 2016, 5:1574 doi: [10.12688/f1000research.9110.1](http://dx.doi.org/10.12688/f1000research.9110.1) [Jupyter Notebook](https://github.com/maayanlab/Zika-RNAseq-Pipeline/blob/master/Zika.ipynb)

- For execution, can use [the `-student` version of the Data Exploration lesson's notebook](https://github.com/Reproducible-Science-Curriculum/data-exploration-RR-Jupyter/blob/master/Data_exploration_student.ipynb).

### Resources
- It is worth verifying before the lesson that your installation of the notebook gives the expected behavior with images.  The most portable thing is to embed the images in the document.
- By default, GUI html export embeds as Base64
- By default, GUI markdown export creates a folder and a zip

- _Exporting the notebook:_ If your Jupyter notebook has plot images generated from your code, they will be embedded in your HTML and PDF documents.  If however, you export to the Markdown format, they will be included in a folder in a zipped archive.

## 2. Documentation  

### Timeline

### Customization

### Resources

#### Exercise 3:
* MS Salmanpour. (2016). Data set [Data set]. Zenodo. http://doi.org/10.5281/zenodo.193025
    - Meaningless title, no description, no README
    - no links to anything
    - proprietary file format
* Solange Duruz. (2016). Simulated breed for GENMON [Data set]. Zenodo. http://doi.org/10.5281/zenodo.220887
    - Title with useful information. No description, no README
    - no links to anything
    - open reusable data format
* Zichen Wang, Avi Ma'ayan. Zika-RNAseq-Pipeline v0.1. Zenodo; 2016. http://doi.org/10.5281/zenodo.56311
    - Informative title and short description. README file.
    - Links to Github, from README to paper and Zenodo archive, from paper to Github and Zenodo archive
    - Everything in open reusable formats

See [#1](https://github.com/Reproducible-Science-Curriculum/publication-RR-Jupyter/issues/1) and [#20](https://github.com/Reproducible-Science-Curriculum/publication-RR-Jupyter/issues/20) for additional discussion. Note some of these could also be used for Record-Level Metadata below.

## 3. Record-level Metadata  

### Timeline
- Exercise 1: 
    - Exercise: Evaluating quality of metadata records (7 minutes)   
    - Whole Group Discussion of Exercise 1 (5 minutes)  
- Instructor-led discussion about record-level metadata types (7 minutes)  
- Discussion about keywords (4 minutes)  
- Exercise 2: Picking keywords for gapminder dataset.  
   - Individually pick max five keywords for the gapminder dataset. (3 minutes)  
   - Work with partner, pick max five keywords (can come up with new ones or use from union). (3 minutes)  
   - Whole group discussion to pick max five keywords final. (5 minutes)  

### Customization
- You can use other Zenodo entries. Make sure that you choose at least one entry with a non-descriptive title (eg "Dataset5"), one with a 
descriptive title but no keywords, and one with both a descriptive title and good keywords. 
- For the ranking exercise: worst = no keywords + vague title < no keywords + descriptive title < descriptive title + 
vague keywords < descriptive title + descriptive keywords = best.
- When running low on time, prioritize the ranking exercise and the related discussion and skip the keywords exercise.

### Resources

## 4. Publishing your Work  

### Timeline

### Customization

### Resources

#### What does having a DOI mean?

DOI and other similar identifiers are meant solely to be unique and stable identifiers for resources.  This means they can be assigned to smaller portions of papers, such as figures, or even for individual proteins or crystal structures within repositories.

The implication of having a DOI is solely of stability and not necessarily of quality.  That said, individual repositories may have specific requirements about when and how they issue DOIs for resources.  The DOI service is just a system that they utilize to create identifiers.

#### DOIs and registrars

* DataCite has an API as well: <https://mds.datacite.org/static/apidoc>
* Note that in practice the CrossRef and DataCite DOI registrars work together closely to enhance interoperability.

#### Exercise 2:
* Note that GitHub repositories can still be moved and deleted. Nonetheless, it may in some contexts still be more stable than just a download from a personal or lab website.
* Zenodo and FigShare allow linking a GitHub repository, which will then be archived in the form of a snapshot (correconding to a version). This provides a DOI one can put into the paper, and even if the GitHub repository is later taken down, the DOI should still resolve to that archival entry within the repository. (In theory, the repository could also update the redirect from the DOI to wherever the archived files moved to. In practice, few if any repositories do this.)

### Resources  

#### Sensitive data

* [HIPAA](https://en.wikipedia.org/wiki/Health_Insurance_Portability_and_Accountability_Act) is relevant legislation, but specific to the US. If you are elsewhere, there will likely be similarly pertinent legislation  to protect the privacy if personal identifiable information (sometimes abbreviated PII). _(Consider contributing relevant links as pull requests.)_

#### Data Use Agreements (DUA)

Data Use Agreements are often tempting to consider, but are in most cases not a good idea. That's because they are very difficult to enforce (which requires to show that an alleged perpetrator agreed to the DUA in the first place - persons who get the data without having agreed to the DUA are not bound by it in any way). For this reason, they are not discussed in the lesson in more detail -- after all, this is about reproducible science as one of the benefits enabled by open science.

Nonetheless, some data, especially data that is aggregated from many different providers in different jurisdictions and with divergent institutional policies, simply wouldn't be available without DUAs. Examples/resources if you want to discuss that include the following:
* [DUA of the Global Biodiversity Information Facility](http://www.gbif.org/terms/data-user)
* [DUA of the database of Genotypes and Phenotypes (dbGaP)](https://dbgap.ncbi.nlm.nih.gov/aa/wga.cgi?view_pdf&stacc=phs000016.v2.p2)

#### Licensing

* Choose a License - [No License](https://choosealicense.com/no-license/)
* Guide to [Open Data Licensing](http://opendefinition.org/guide/data/)
* [University of Illinois - Research Data Sharing and Licensing](http://www.library.illinois.edu/sc/services/data_management/sharing.html)
* Ball A. How to License Research Data [Internet]. Edinburgh, UK: Digital Curation Centre; 2014. Available: http://www.dcc.ac.uk/resources/how-guides/license-research-data
* Carroll MW. Sharing Research Data and Intellectual Property Law: A Primer. PLoS Biol. 2015;13: e1002235. [doi:10.1371/journal.pbio.1002235](http://doi.org/10.1371/journal.pbio.1002235)

Open Database licensing examples:
* [OpenStreetMap license](http://www.openstreetmap.org/copyright), which uses the [Open Data Commons Open Database License])https://opendatacommons.org/licenses/odbl/summary/)
