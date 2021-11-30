# A GitHub Approach to Publishing Darwin Core Formatted Occurrence Data for Taxonomic Studies

[![DOI](https://zenodo.org/badge/357969604.svg)](https://zenodo.org/badge/latestdoi/357969604)

### Description
This repository contains a Darwin Core Archive template and instructions for revisionary taxonomists to use to publish their data as a Darwin Core Archive or Darwin Core Compliant CSV file. This repository contains the Darwin Core Archive for A taxonomic revision of _Gryonoides_ Dodd, 1920 (Hymenoptera: Scelionidae), with a review of the hosts of Teleasinae." The archive was produced by the authors from data contained in mx (Yoder et al. 2006–present).

### Summary
Darwin core archives have emerged as the accepted data-sharing standard for occurrence data about organisms. These occurrences could be observations or specimens in natural history collections. The standard is applied by natural history collections worldwide to share their data between various repositories, including Global Biodiversity Information Faculty (GBIF) and Integrated Digitized Bio collections (iDigBio). This repository can be repurposed as an example template for publishing material examined as a Darwin Core Archive, accessible for data aggregators, journals, and conforming to community standards. This method can be used for any occurrence dataset, such as material examined, species monitoring observation records, ecological observations, or natural history collection data.

### How to Create a Darwin Core Archive Using this Repository
1- Fork repository on GitHub or download its contents.

2- Use the occurrences.csv file as a template. Delete the *Gryonoides* data and add your own. Do not change the column number or order. It is ok to leave in extra columns that you do not use. The only columns that need to be filled out are _occurrenceID_ and _BasisOfRecord_. Specific definitions of the field names can be found in the Darwin Core Documentation under the [Occurrence Core](https://dwc.tdwg.org/terms/#occurrence).

3- Do not touch the meta.xml. This file describes the columns in the occurrences.csv file.

4- Edit the eml.xml files to include information about your institution and project. 

5- Zip the folder to create the archive. If you are using GitHub you can use the zip function for the repository using Code  -> Download ZIP.
![GitHub Code Button](https://user-images.githubusercontent.com/1044474/144145191-354c381d-8fc7-44b6-bbb8-4287a7dc97f9.png)

6- Validate the archive using the [GBIF Data Validator tool](https://www.gbif.org/tools/data-validator).

### Citations

Yoder, M.J., Dole, K., Seltmann, K., and Deans, A. 2006-Present. Mx, a collaborative web based content management for biological systematists. http://mx.phenomix.org/index.php/Main_Page
