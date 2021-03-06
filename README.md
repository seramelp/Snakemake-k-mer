# Snakemake k-mer
## Description
Use of Snakemake workflow management system along with k-mer algorithm.

K-mers are subsequences of length k contained within a biological sequence. Primarily used within the context of computational genomics and sequence analysis, in which k-mers are composed of nucleotides (i.e. A, T, G, and C), k-mers are capitalized upon to assemble DNA sequences, improve heterologous gene expression, identify species in metagenomic samples, and create attenuated vaccines.This project evaluate parameters of specific k and choose the best k for the DNA sequences.

## Requirements
Before you continue, ensure you have make sure the following packages are installed in your local machine:  
  * You have installed the python libraries:  
    1. Natural Language Toolkit library.  
    2. Scikit-learn library.  
    3. Seaborn library.  

## Installation
To install Snakemake k-mer project:
  1. Click the Code Bar and download the zip file of the project.
  
  Or
  
  2. You can clone the project in your local PC using git:    
  ``` git clone https://github.com/seramelp/Snakemake-k-mer.git```
  
## Geting started
The project consists of one main file:
  * Snakefile

and eight additional scripts, that contain the functions called by the main file:
  * k-mer.py
  * fit.py
  * best-fit.py
  * matrix.py
  * plot.py
  * count_kmers.py
  * godel_f.py
  * dataPreProcessing.py

 In order to run the project follow the steps:     
 
   Step 1. Remove the default ```.fasta``` file from ```files``` directory and Copy yours ```.fasta``` file in ```files``` directory.  
   Step 2. Modify the variable ```k``` in Snakefile file with the choosen integer numbers for the analyses.  
   Step 3. Run the command line ```snakemake``` in a conda enviroment.  
   Step 4. Wait for the results.  
