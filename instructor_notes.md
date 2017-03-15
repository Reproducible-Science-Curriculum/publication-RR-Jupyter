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

### Resources
- We have included callouts for some of the more involved aspects of notebook conversion.
- It is worth verifying before the lesson that your installation of the notebook gives the expected behavior with images.  The most portable thing is to embed the images in the document.
- By default, GUI html export embeds as Base64
- By default, GUI markdown export creates a folder and a zip

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

#### Sensitive data

* [HIPAA](https://en.wikipedia.org/wiki/Health_Insurance_Portability_and_Accountability_Act) is relevant legislation, but specific to the US. If you are elsewhere, there will likely be similarly pertinent legislation  to protect the privacy if personal identifiable information (sometimes abbreviated PII). _(Consider contributing relevant links as pull requests.)_

#### Licensing

* Choose a License - [No License](https://choosealicense.com/no-license/)
* Guide to [Open Data Licensing](http://opendefinition.org/guide/data/)
* [University of Illinois - Research Data Sharing and Licensing](http://www.library.illinois.edu/sc/services/data_management/sharing.html)
* Ball A. How to License Research Data [Internet]. Edinburgh, UK: Digital Curation Centre; 2014. Available: http://www.dcc.ac.uk/resources/how-guides/license-research-data
* Carroll MW. Sharing Research Data and Intellectual Property Law: A Primer. PLoS Biol. 2015;13: e1002235. [doi:10.1371/journal.pbio.1002235](http://doi.org/10.1371/journal.pbio.1002235)
