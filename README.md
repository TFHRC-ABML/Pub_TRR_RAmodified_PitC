# Data and Analysis Code for TRR Paper

## Evaluating Mechanical Performance of High-RAP Asphalt Mixtures Modified with Bio- and Petroleum-Based Recycling Agents: Insights from the Pavement Testing Facility

[![GitHub License](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/TFHRC-ABML/Pub_TRR_RAmodified_PitC/blob/main/LICENSE)

📄 **[Paper Link (under review)](XXXX)**

### Authors and Contributors
- *Behnam Jahangiri (behnam.jahangiri.ctr@dot.gov)*
- *S. Farhad Abdollahi (farhad.abdollahi.ctr@dot.gov)*
- *Adrian Anderiescu (adrian.anderiescu.ctr@dot.gov)*
- *Hamzeh Haghshenas (hhaghshenas@nas.edu)*
- *David Mensching (david.mensching@dot.gov)*

---

This repository contains the data and analysis code accompanying the TRR paper (currently under review) titled:  
**"Evaluating Mechanical Performance of High-RAP Asphalt Mixtures Modified with Bio- and Petroleum-Based Recycling Agents: Insights from the Pavement Testing Facility."**

---

## Table of Contents

1. [Requirements](#requirements)
2. [Dataset](#dataset)
3. [Analysis Code](#analysis-code)
4. [Acknowledgments](#acknowledgments)
5. [Citation](#citation)

---

## Requirements

The analysis was conducted using Python and several external libraries. Please ensure the following versions are installed for full compatibility:

- Python 3.8.20  
- `numpy` 1.24.3  
- `scipy` 1.10.1  
- `pandas` 2.0.3  
- `matplotlib` 3.7.2  
- `scikit-learn` 1.3.0  

---

## Dataset

The dataset is provided as an Excel file, `Data.xlsx`, which contains multiple sheets corresponding to different laboratory tests and material properties:

- **RA Dosage Determination**: Contains high- and low-temperature performance grades (HTPG and LTPG) of binder blends used to determine optimized RA dosage.
- **Compaction Curves**: Gyratory compactor results showing %Gmm versus number of gyrations (three replicates per mixture).
- **Gradation Curves**: Measured and target aggregate gradations with control points for the mixtures.
- **JMF**: Job Mix Formula (JMF) details for all asphalt mixtures.
- **HTPG**: Measured HTPG of recovered binders.
- **LTPG**: S-values and m-values from BBR testing of recovered binders.
- **Glover-Rowe (G-R)**: |G*| and phase angle values at 44.7 °C and 10 rad/s used to compute the G-R parameter.
- **DENT**: Results from the DENT test, including CTOD and related outputs.
- **Extended BBR**: S-values and m-values under extended BBR test conditions.
- **IDEAL-CT**: Summary results of the IDEAL-CT test.
- **DCT**: Summary results from the DCT test (fracture energy).
- **HWTT (raw data)**: Raw rutting data from the Hamburg Wheel Tracking Test.
- **HWTT (Analysis)**: Analyzed HWTT outputs.

---

## Analysis Code

The analysis is organized into four Jupyter Notebooks:

- `Task01_RA_Optimization.ipynb`: Calculates the optimized RA dosage and plots relevant figures.
- `Task02_Compaction_Gradation.ipynb`: Plots compaction and gradation curves.
- `Task03_Binder_Test_Results.ipynb`: Analyzes binder test results including HTPG, LTPG, G-R, LTPG loss, and CTOD from DENT.
- `Task04_Mixture_Test_Results.ipynb`: Analyzes mixture performance from IDEAL-CT, DCT, and HWTT tests.

---

## Acknowledgments

We gratefully acknowledge Bethel La Plana, Steve Portillo, Scott Parobeck, and Frank Davis for their efforts in preparing and testing the asphalt binder and mixture samples used in this study.

---

## Citation

If you use this code or dataset in your research, please cite the following:

```bibtex
@misc{JahangiriRAmodifiedHighRAP2025,
  title     = {Evaluating Mechanical Performance of High-RAP Asphalt Mixtures Modified with Bio- and Petroleum-Based Recycling Agents: Insights from the Pavement Testing Facility},
  author    = {Jahangiri, Behnam and Abdollahi, Seyed Farhad and Anderiescu, Adrian and Haghshenas, Hamzeh and Mensching, David},
  year      = {TBD},
  month     = {TBD},
  publisher = {Transportation Research Record: Journal of the Transportation Research Board},
  doi       = {XXXXX},
  urldate   = {2025-10-09},
  archiveprefix = {XXX},
  langid    = {english},
  keywords  = {Bio Recycling Agent, Petroleum Recycling Agent, High-RAP Asphalt Mixtures, Cracking Resistance, Rutting Resistance}
}
```

---

📬 For questions or feedback, please contact **Farhad Abdollahi** at *farhad.abdollahi.ctr@dot.gov*.