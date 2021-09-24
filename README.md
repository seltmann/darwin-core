# A GitHub Approach to Publishing Darwin Core Formatted Occurrence Data for Taxonomic Studies

### Description
This repository contains a Darwin Core Archive template and instructions for revisionary taxonomists to use to publish their data as a Darwin Core Archive or Darwin Core Compliant CSV file. This repository contains the Darwin Core Archive for Gryonoides specimens contained in the publication "Biology and taxonomy of Teleasinae: Review of Gryonoides Dodd 1920 (Hymenoptera: Platygastridae)." The archive was produced by the authors from data contained in mx (Yoder et al. 2006–present).


### Summary
Darwin core archives have been emerged as the accepted data sharing standard forsharing occurrence data about organisms. These occurrences could be observations or specimens in natural history collections. The standard is applied by natural history collections worldwide to share their data between various repositories, including Global Biodiversity Information Faculty (GBIF) and Integrated Digitized Bio collections (iDigBio). This repository can be repuroposed as an example template for publishing material examined as a Darwin Core Archive, accessable for data aggregators, journals and conforming to community standards. This method can be used for any occurrence dataset, either as a the material examined, species monitoring observation records, ecology publication or natural history collection data.

### How to Create a Darwin Core Archive Using this Repository
1- Fork repository on GitHub or download its contents.

2- Use the occurrences.csv file as a template. Delete the *Gryonoides* data and add your own. Do not change the column number or order. It is ok to leave in extra columns that you do not use.

3- Edit the eml.xml files to include information about your institution and project. 

4- Do not touch the meta.xml. This file describes the columns in the occurrences.csv file.

5- Zip the folder to create the archive. If you are using GitHub you can use the zip function for the repository under the Code -> Download ZIP.


Not all fields need to be filled out except: occurrenceID, BasisOfRecord. Specific definitions of the field names can be found in the Darwin Core Documentation. Occurrence data (https://dwc.tdwg.org/terms/#occurrence).
