# wgs-sars-cov2
The goal of this project is to identify and visualize variation/divergence (snippet occurence) in SARS-CoV-2 genomes as it concerns the surface glycoprotein (spike protein).

Background

Understanding variation across SARS-CoV-2 genome sequences and particularly spike protein sequences has important implications for the study of virology, vacccination production, and epidemiology. By identifying, visualizing, and interpreting the COVID-19 nucleotide record data, trends in variation can be emphasized, and a phylogenetic analysis can help understand the drift SARS-CoV-2 has taken in the United States. 
COVID-19 continues to spread and evolve since its initial outbreak in 2019. This virus is a +ssRNA virus whose genome contains genetic instructions for the construction of the Spike (S) protein. The S protein is a 1273 amino acid-long glycoprotein that plays a role in SARS-CoV-2 pathogenesis. The S protein is a portion of the SARS-CoV-2 virus that is responsible for receptor recognition and the cell membrane fusion process upon attack. The spike protein is composed of two subunits termed S1 and S2.  The S protein is a 1273 amino acid-long glycoprotein.  Previously published work has shown that changes in biological structure and function of species are attributable to sequence pattern divergence.  The S protein has a high mutational propensity, thus our project goal is to explore whole genome patterns of divergence amongst SARS-CoV-2 strains.  We would like to better understand functional consequences of divergence within the spike protein based on snippet assessments of the protein sequences.
We hypothesize that there are divergent patterns present within the spike protein sequences. Further assessments of these divergence patterns will be critical to our understanding of the levels of significance as pertains to divergence and overall impact to the viral structure and function.

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
