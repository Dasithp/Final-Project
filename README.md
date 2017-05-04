# Final-Project
This repository contains all the files I used in order to complete my final big data analysis assignment.

My research proposal includes looking at the serum microbiome of diabetics with periodontitis and comparing it to diabetics without periodontitis and normal, healthy subjects.
The focus of my assignment is to test the methodology that I propose to carry out for this project. In order to test this method I used some publically available data that looked at the microbiome in the plasma component of blood, compared to the buffy coat layer and red blood cell layer.

The raw illumina sequence data that I used for this purpose can be found in the "raw data" folder
For the purpose of this project I only used the forward reads listed in the r1 folder for both the buffy coat and plasma

I carried out quality control using trimmomatic and flexbar. I used fastqc to verify the quality

I used MED to cluster the sequences and largely obtain species level resolution.
The Human Oral Microbiome database was used to label the species that match the output of MED. For the purpose of this assignment, I used the top hit on HOMD for each of the calls. So it is important to note that the species mentioned in the document may not be their true identities but rather their closest relatives as based on the HOMD database.

The MED and HOMD alignment result files can be found in the "MEDoutput" folder.
   
The file containing my proposal is titled as "Big data Proposal" and is a pdf document.




