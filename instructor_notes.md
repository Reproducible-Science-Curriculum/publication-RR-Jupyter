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

#### What does having a DOI mean?

DOI and other similar identifiers are meant solely to be unique and stable identifiers for resources.  This means they can be assigned to smaller portions of papers, such as figures, or even for individual proteins or crystal structures within repositories.

The implication of having a DOI is solely of stability and not necessarily of quality.  That said, individual repositories may have specific requirements about when and how they issue DOIs for resources.  The DOI service is just a system that they utilize to create identifiers.

#### Exercise 2:
* Note that GitHub repositories can still be moved and deleted. Nonetheless, it may in some contexts still be more stable than just a download from a personal or lab website.
* Zenodo and FigShare allow linking a GitHub repository, which will then be archived in the form of a snapshot (correconding to a version). This provides a DOI one can put into the paper, and even if the GitHub repository is later taken down, the DOI should still resolve to that archival entry within the repository. (In theory, the repository could also update the redirect from the DOI to wherever the archived files moved to. In practice, few if any repositories do this.)

