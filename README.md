# Kepler Exoplanet Detection

## Project Overview
This project focuses on the detection of exoplanet candidates using light curve data obtained from NASA’s Kepler Space Telescope. The primary objective is to analyze stellar brightness variations caused by planetary transits and apply machine learning techniques to classify potential exoplanet signals.

The project is intended as an academic study demonstrating the complete pipeline of exoplanet detection, including data acquisition, preprocessing, feature extraction, and classification.



## Objectives
- Understand the transit method for exoplanet detection
- Analyze Kepler light curve data
- Preprocess and normalize stellar flux data
- Identify periodic transit-like signals
- Extract meaningful features from folded light curves
- Apply classical machine learning models to classify exoplanet candidates



## Data Source
- **Kepler Light Curve Data**
- Data is accessed programmatically using the `lightkurve` Python library.
- Raw datasets are not stored in this repository due to size constraints.



## Methodology (High-Level)
1. Download Kepler light curve data
2. Data cleaning and normalization
3. Noise reduction and outlier removal
4. Period detection and light curve folding
5. Feature extraction (e.g., transit depth, duration, period)
6. Machine learning model training and evaluation



## Tools & Technologies
- Python
- NumPy
- Pandas
- Matplotlib
- Lightkurve
- Scikit-learn
- Jupyter Notebook



## Project Structure
```bash
kepler-exoplanet-detection/
│
├── data
│   └── README.md
├── literature
│   └── papers.md
├── notebooks
├── README.md
├── reports
│   ├── Level1_report.pdf
│   └── README.md
├── requirements.txt
└── src

```

## Project Status
🔧 **In Progress**

Current focus:
- Literature review
- Understanding Kepler data format
- Initial light curve exploration


## Scope & Limitations
- This project does not aim to discover new exoplanets.
- The goal is to demonstrate a working detection and classification pipeline.
- Results are limited to publicly available Kepler datasets.


## Future Work
- Extend the approach to TESS mission data
- Explore deep learning models for light curve classification
- Improve noise handling and feature extraction techniques


## Author
- Prajin GN


## References
Relevant research papers and resources are listed in the `literature/` directory.