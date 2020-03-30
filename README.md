# Clauer_440Project

Overview
------------------------------------
This repo contains the code and data required to reproduce Phillip Clauer and Viraat Goel's 20.440 Final Project: Determining sex-specific differentially expressed transcripts in ALS patients.

Raw data available at the GEO accession GSE122649 and GSE124439 as well as in the data folder.

The repo is divided into data, code, and figures.

Data
------------------------------------
The data for this project comes from two databases delinienated into two subfolders: 

  GSE122649_RAW: NYGC ALS consortium patient subtype assignment GEO accession: GSE122649
  
  GSE124439_RAW: Clinical information of UCSD sALS samples GEO accession: GSE124439
  
These datasets were collected and analyzed as part of Tam et al. 2019. The subfolders contain .txt files containing individual patient RNA-seq samples with the number of reads mapped to each gene. Data was collected through performing RNA extraction on frozen deceased patient samples and performing pair end seqiencing using an Illumina HiSeq 2500 (Tam et al. 2019). 

Folder Structure
------------------------------------
The repo is divided into three folders—data, code, and figures. 

The data folder contains the raw .txt RNA-seq data divided into two subfolders representing the two datasets used in this project. 

The code folder is subdivided into folders containing .py files necessary to reproduce the individual analyses and figures for this project. Code will automatically reference raw data found in the data folder and deposit all figures into the figure folder.

The figures folder contains the figures in .png format used in the project. Figures generated using .py files from the code folder will automatically be deposited in the figures folder. 

Installation
------------------------------------
Clauer_440Project code runs with Python 3 requiring the standard Python dependencies pandas, os, numpy, math, seaborn, and matplotlib. 

Currently, the dataset used to generate figures should be explicitly chosen in the code. 

The .py files should be able to be run as is upon installation of repo.

Citations:
Tam, Oliver H et al. “Postmortem Cortex Samples Identify Distinct Molecular Subtypes of ALS: Retrotransposon Activation, Oxidative Stress, and Activated Glia.” Cell reports vol. 29,5 (2019): 1164-1177.e5. doi:10.1016/j.celrep.2019.09.066
