# Data and Analysis Codes for TRR paper:

## Evaluating Mechanical Performance of High-RAP Asphalt Mixtures Modified with Bio- and Petroleum-Based Recycling Agents: Insights from the Pavement Testing Facility

[![GitHub License](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/TFHRC-ABML/Pub_TRR_RAmodified_PitC/blob/main/LICENSE)

**[paper](XXXX)**

Authors and Contributors:
- *Behnam Jahangiri (behnam.jahangiri.ctr@dot.gov)*
- *S. Farhad Abdollahi (farhad.abdollahi.ctr@dot.gov)*
- *Adrian Anderiescu (adrian.anderiescu.ctr@dot.gov)*
- *Hamzeh Haghshenas (hhaghshenas@nas.edu)*
- *David Mensching (david.mensching@dot.gov)*


This repository contains the data and analysis codes for the TRR paper [currently under review] titled "Evaluating Mechanical Performance of High-RAP Asphalt Mixtures Modified with Bio- and Petroleum-Based Recycling Agents: Insights from the Pavement Testing Facility".  

## Content ##

0. [Requirement](#setup-instruction)
0. [Dataset](#sample-database)
0. [Analysis codes](#how-to-use)
0. [Acknowledgement](#acknowledgement)
0. [Citation](#citation)


## Requirement ##

This project has been developed using `Python` programming language coupled with some external libraries, detailed provided below. You'll need to use the compatible versions to run it smoothly.

* Python version 3.8.20
* `numpy` library, version 1.24.3
* `scipy` library, version 1.10.1
* `pandas` library, version 2.0.3
* `matplotlib` library, version 3.7.2
* `sklearn` library, version 1.3.0

---

## Dataset ##

Data has been provided with this repository as an Excel file, called `Data.xlsx`. This file include several sheets, each for a specific test or material properties results, as follows:

* **RA Dosage Determination**: this sheet include the high- and low-temperature performance grade (HTPG and LTPG) of the binder blends which is used to determined the optimized recycling agent (RA) dosage at the mixture level. 
* **Compaction Curves**: this sheet include the gyratory compactor results in terms of calculated %Gmm as a function of number gyration for different asphalt mixtures (with three replicates).
* **Gradation Curves**: this sheet includes the measured aggregate gradation, target gradation, and couple of control points for the asphalt mixtures used in this study. 
* **JMF**: this sheet include the job mix formula (JMF) details of the asphalt mixtures used in this study.
* **HTPG**: this sheet include the measured HTPG of the recovered binders from the asphalt mixtures of this study. 
* **LTPG**: this sheet include the measured S-values and m-values from the BBR testing for the recovered binders from the asphalt mixtures of this study. 
* **Glover-Rowe (G-R)**: this sheet include the |G*| and phase angle values measured at the temperature of 44.7°C and loading frequency of 10 rad/s which is used to calculate the G-R parameter for the recovered binders from the asphalt mixtures of this study. 
* **DENT**: this sheet include the detailed outputs of the DENT test for the recovered binders from the asphalt mixtures of this study.
* **Extended BBR**: this sheet include the measured S-values vand m-values under different conditioning of extended BBR test for the recovered binders from the asphalt mixtures of this study.
* **IDEAL-CT**: this sheet include the analyzed outputs of the IDEAL-CT test for the asphalt mixtures of this study. 
* **DCT**: this sheet include the analyzed outputs of the DCT test (fracture energy) for the asphalt mixtures of this study. 
* **HWTT (raw data)**: this sheet include the raw data from the HWTT test to plot the rutting curves for the asphalt mixtures of this study. 
* **HWTT (Analysis)**: this sheet include the analyzed outputs of the HWTT test for the asphalt mixtures of this study. 


## Analysis codes ##

The analyses efforts of this study has been organized into 4 different jupyter notebooks, as follows: 

* `Task01_RA_Optimization.ipynb`: this notebook include the codes to calculate the optimized RA dosage and plot the relevant figure. 
* `Task02_Compaction_Gradation.ipynb`: this notebook include the codes to plot the compaction and gradation curves. 
* `Task03_Binder_Test_Results.ipynb`: this notebook include the analysis and plotting codes for the asphalt binder tests, including the HTPG, LTPG, G-R, LTPG loss, and DENT's CTOD parameter. 
* `Task04_Mixture_Test_Results.ipynb`: this notebook include the analysis and plotting codes for the asphalt mixture tests, including the IDEAL-CT, DCT, and HWTT tests. 

## Acknowledgement ##

We extend our sincere gratitude to Bethel La Plana, Steve Portillo, Scott Parobeck, and Frank Davis for their contributions in preparing and testing the asphalt binder and mixture samples.

## Citation ##

If you use our code or method in your work, please cite the following:

```bibtex
@misc{JahangiriRAmodifiedHighRAP2025,
  title = {Evaluating Mechanical Performance of High-RAP Asphalt Mixtures Modified with Bio- and Petroleum-Based Recycling Agents: Insights from the Pavement Testing Facility},
  author = {Jahangiri, Behnamm and Abdollahi, Seyed Farhad and Andriescu, Adrian and Haghshenas, Hamzeh and Mensching, David},
  year = {TBD},
  month = TBD,
  publisher = {Transportation Research Record: Journal of Transportation Research Board},
  doi = {XXXXX},
  urldate = {2025-10-09},
  archiveprefix = {XXX},
  langid = {english},
  keywords = {Bio Recycling Agent, Petroleum Recycling Agent, High-RAP Asphalt Mixtures, Cracking Resistance, Rutting Resistance}
}
```

Please direct any questions to Farhad Abdollahi (farhad.abdollahi.ctr@dot.gov).