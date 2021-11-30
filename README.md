# Biopython
## Learning objects
- Understanding transcription and translation from DNA sequence to protein
- Analyzing information in a fasta file to generate 3D structure of protein(s)
- Showing related data from amino acid sequences by using qblast 

## Procedure
1. The fasta file has information about SARS-CoV-19 sequence, id, name and description.
2. Transcribe & translate the sequence and save the amino acid(aa) sequence in a variable. 
3. Showing distributions of aa. It helps for analyzing unknown target of interest.

![aa](https://user-images.githubusercontent.com/54334941/143525577-4aaf5aa9-774d-41f1-862a-82b832d69a6e.png)

4. Cutting it with terminal codons and sorting them to be ready to get functional proteins.

![sorted](https://user-images.githubusercontent.com/54334941/143529330-01b1b6d1-c495-4bf4-b88b-978fc786e664.png)

5. Analyzing one longest protein with 2701 length long.
6. Using qblast to search for descriptions in Protein Data Bank(PDB)
7. Choosing highly possible info. considering with E value and Bit score and alignment with the target.

![details](https://user-images.githubusercontent.com/54334941/143529950-33302394-b4c6-40e5-9a0a-38dea3719cf3.png)

8. Showing ribbon view of the protein structure

![struc](https://user-images.githubusercontent.com/54334941/143530121-f8847d29-d302-4f09-a433-ce66d56b1c59.png)

9. Showing surface filling view with adding features on the structure (Colors represent B-factor on a left image and chain index on a right image)

![bfactor](https://user-images.githubusercontent.com/54334941/143531315-79bd52a6-684e-47a2-b9af-36bcde9502d0.png)
![chainindex](https://user-images.githubusercontent.com/54334941/143531316-6a14a627-532c-4501-919a-829d14f11f3c.png)


## In Conclusion
This project is for training how to get information from the fasta file with Biopython. I am able to obtain complement/reverse complement sequence, GC contents, RNA sequence, amino acid sequence, do alignment with PDB to show 3D structure with multiple data of interest.

## What is the Next?
I am participating in one project related to cMYC-microRNA1207. I am going to analyze MYC to make sure the domains of DNA binding, MAX binding and more with a biopython library. 
