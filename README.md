# Temporal response characterization across individual multiomics profiles of prediabetic and diabetic subjects

The current repository contains code and data as online data files (ODFs) to accompany the manuscript by Zheng et al.

## Requirements and Dependencies
The code utilizes and has been executed in Python 3.8. Mathematica (version 12) was used for the .nb files. For more details, please refer to the comments within the code, including package dependencies.

## Directories and Files
The following directories are included:

### code
The *code* folder includes the source code we used in this research. We recommend running the code on a server with 5GB free storage space to save results.

### data
The *data* folder includes the original data for the research, as used by the code as inputs, including mapped data and metadata/subject information from Zhou et al. [[1]](#1), with diabetes measures included in Schussler-Fiorenza Rose et al.  [[2]](#2).

### figures
The *figures* folder includes the figures used directly the manuscript

### results
The *results* folder contains figures and output from the code.  The *singleSub* subdirectory contains the PyIOmica output using classification of time signals for each individual subject.  Withing the *singleSub* directory are two folders: (i) the *consolidatedGroupsSubgroups* folder that contains excel spreadsheets with the information correspondig to the heatmaps/clustering for each subject in the main directory, and (ii) the *reactome* folder that contains Reactome pathway enrichment results for the clusters/corresponding results listed in the *consolidatedGroupsSubgroups* folder.

## Funding
This study was funded by the Translational Research Institute for Space Health through National Aeronautics and Space Administration (NASA) Cooperative Agreement NNX16AO69A (Project Number T0412, PI: George Mias). 

## Contact Information
* Code Contributor: Mingzhang Zheng (zefer001@gmail.com)
* Project Principal Investigator (PIs): Dr George Mias (gmias@msu.edu)
* [G Mias Lab](https://georgemias.org)

## References
<a id="1">[1]. </a>  Zhou W, Sailani MR, Contrepois K, Zhou Y, Ahadi S, Leopold SR, et al. *Longitudinal multi-omics of host-microbe dynamics in prediabetes.* Nature 569(7758):663–671, 2019. (https://doi.org/10.1038/s41586-019-1236-x)

<a id="2">[2]. </a> Schussler-Fiorenza Rose SM, Contrepois K, Moneghetti KJ, Zhou W, Mishra T, Mataraso S, et al. *A longitudinal big data approach for precision health.* Nature Medicine 25(5):792–804, 2019. (https://doi.org/10.1038/s41591-019-0414-6)