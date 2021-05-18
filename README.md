# wgs-sars-cov2
The goal of this project is to identify and visualize variation/divergence (snippet occurence) in SARS-CoV-2 genomes as it concerns the surface glycoprotein (spike protein).

Background

Understanding variation across SARS-CoV-2 genome sequences and particularly spike protein sequences has important implications for the study of virology, vacccination production, and epidemiology. By identifying, visualizing, and interpreting the COVID-19 nucleotide record data, trends in variation can be emphasized, and a phylogenetic analysis can help understand the drift SARS-CoV-2 has taken in the United States. 

Workflow

Data Preparation
1. Apply a ramdomization process in order to choose random datasets as well as allowing for iterative computing from the NCBI Virus SARS-CoV-2 nucleotide record.
2. Download all of the sequences in a convenient output file format, such as a csv, to upload into GitHub. 

Data Analysis
3. Apply a python code but more specifically a snippet occurrence analysis code to interpret the variance among the randomized dataset's sequences. 
4. Apply the use of R package, protr package, etc to analyze the data from the snippet occurrence code.

Data Visualization
5. Select 5 different strain sequences based upon snippet occurrences and run PyMol to determine if there would be structural changes. 
6. Create multiple sequence alignments and a phylogenetic tree for data visualization and analysis.

Data Interpretation
7. As the final step, interpreting all of the data that is presented through snippet occurrences or visualization tools is important while concluding results. 
