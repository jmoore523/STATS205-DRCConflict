# STATS205-DRCConflict
Final project for STATS205: Nonparametric Statistics

> The purpose of this project was to assess whether kernel density estimation could be used to effectively predict the locations of conflicts in the Democratic Republic of the Congo. I built and evaluated kernel density estimates that used a number of different bandwidth selection methods. I ultimately concluded that KDE is a potentially effective technique for this purpose. 

> See "STATS205-Proposal.pdf" for the project proposal and "STATS205-Final Paper.pdf" for the full report.

A few important notes:

**Input**

> In order to save space, I created a zip file of the data I used. The “Input.zip” file in the “Input” folder must be unzipped in order for the code in this repository to run.

> The files in the folder “DRC Outlines” are the shape file and associated support that allow the creation of the outline of the DRC. They were acquired from GADM’s website, located at http://www.gadm.org/country.

> The files in the folder “ACLED” are the shape file and associated support recording the locations of conflicts in Africa. They were acquired from ACLED’s website, located http://www.acleddata.com/data/version-6-data-1997-2015/.

**Scripts**

> The R scripts should be run in the listed order, e.g., 01 precedes 02. Later scripts often call on files produced in earlier scripts. Running them in order will ensure the appropriate files are created in the appropriate sequence.
