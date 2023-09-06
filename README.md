## General info
Title: DNA Methylation regulator-mediated modification patterns and Risk of Intracranial Aneurysm: A Multi-omics and Epigenome-Wide Association Study integrating Machine Learning, Mendelian randomization, eQTL and mQTL Data

Author: Aierpati Maimaiti

Created: 2023/08/29

Genome build: GRCh37

Overview: This repository contains the code and data associated with the research project titled "DNA Methylation regulator-mediated modification patterns and Risk of Intracranial Aneurysm". The study aimed to investigate the relationship between DNA methylation regulator-mediated modification patterns and the risk of Intracranial Aneurysm using a multi-omics and epigenome-wide association study approach. It integrated various types of -omics data, including DNA methylation, gene expression, and genetic variation, to gain insights into the underlying molecular mechanisms.

The analysis involved several steps:
Identification of differentially genes: Differential analysis was performed to identify regions showing significant differences in DNA methylation regulators between individuals with and without Intracranial Aneurysm.

Machine learning-based feature selection: Various machine learning algorithms, such as random forest or support vector machines, were employed to select informative features that are most predictive of Intracranial Aneurysm risk.

Mendelian randomization analysis: Genetic variants associated with DNA methylation modifications were identified, and causal inference methods, such as Mendelian randomization, were applied to investigate the causal relationship between DNA methylation patterns and Intracranial Aneurysm.
Integration of eQTL and mQTL data: Expression quantitative trait loci (eQTL) analysis was conducted to identify genetic variants that influence gene expression levels, while methylation quantitative trait loci (mQTL) analysis was performed to detect genetic variants associated with DNA methylation modifications. These analyses were used to gain insights into the regulatory effects of genetic variants on gene expression and DNA methylation patterns.

Statistical analysis and visualization: Statistical tests and visualization techniques were applied to summarize and interpret the results obtained from the various analyses.

Code usage:The code provided in this repository enables reproducibility of the analysis pipeline described above. The code is written in R languages and is organized into separate directories according to the different steps of the analysis. Each directory contains detailed instructions on how to run the code and replicate the results.

Contact Information
For more details about the study or to request data, please contact:

Name: Aierpati Maimaiti
Email: mmtaili@aliyun.com

## Files in the directory
Note: Please download all 11 sub-volumes from the provided directory and subsequently extract the files to a local directory. 
#Figure1

#Figure2

#Figure3

#Figure4

#Figure5-6

#Figure7

#Figure8

#Figure9

#FigureS1

#FigureS2-S4

#Table 1 and Figure10

#GWAS raw data

#raw expression profile

#code for Table1 and Figure10.docx

#Pipline.R

## Usage method
Please use Pipeline.R and the code provided in Table1 and Figure10.docx to process the raw data located in the corresponding folder. Note that Table1 and Figure10 require Python, while the other file directories require R.

