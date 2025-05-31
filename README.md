# ML-IFN695
Detecting High-Risk Grid Behaviour via Outage Near-Miss Trends in the National Electricity Market (NEM)
This repository contains the data and code used in the project "Detecting High-Risk Grid Behaviour via Outage Near-Miss Trends in the National Electricity Market", submitted as part of IFN695 Assessment 3.

📊 Project Overview
The project investigates near-miss outage events within Australia’s National Electricity Market (NEM) to identify systemic risks and operational stress. By analysing historical trends across substations, equipment types, and outage reasons, the study aims to uncover early warning indicators of grid instability. The analysis focuses on two key timeframes: 2009–2011 and January–May 2025, periods marked by noticeable surges in near-miss activity.

📁 Repository Contents
Minor Project-Final.ipynb: The complete Jupyter Notebook used for data analysis, including visualisation and filtering pipelines.

Datasets.zip: Contains the raw data files used for analysis, sourced from AEMO’s Market Management System (MMS) January 2025 archive.

README.md: This file.

🧰 Technologies Used
Python 3.12

Pandas: for data manipulation

Matplotlib & Seaborn: for visualisations

Jupyter Notebook: for code execution and documentation

📦 Data Sources
All data used in this study was obtained from publicly available AEMO MMS datasets, specifically:

NETWORK_OUTAGEDETAIL

NETWORK_OUTAGESTATUSCODE

These datasets were filtered to isolate near-miss events (e.g. UTP, STLP, WD REQ) and aggregated by time, substation, and equipment type for temporal and categorical trend analysis.


📄 Reproducibility
To reproduce the analysis presented in this project, follow the steps below:


1. Unpack the Dataset
Inside the root directory, unzip the file Datasets.zip.
This should create a folder named Datasets that contains the following files:

PUBLIC_ARCHIVE#NETWORK_OUTAGEDETAIL#FILE01#202501010000.CSV

PUBLIC_ARCHIVE#NETWORK_OUTAGESTATUSCODE#FILE01#202501010000.CSV

PUBLIC_ARCHIVE#NETWORK_OUTAGECONSTRAINTSET#FILE01#202501010000.CSV (optional, not required in main analysis)

3. Environment Requirements
Ensure you have Python 3.12 installed along with the following packages:

- pandas
- numpy
- matplotlib
- seaborn
- calendar


2. Open and Run the Notebook
Launch Jupyter Notebook or any compatible IDE (e.g., VSCode with Jupyter extension).

Open Minor Project-Final.ipynb.

!!Run the cells sequentially, ensuring the notebook's working directory is set to the root folder where the Datasets folder is located!!.

3. Output
The notebook will:

- Filter and preprocess the outage data.
- Generate all visualisations (bar charts and heatmaps) based on predefined logic.

📬 Contact
For any questions, please contact: [@Nasilem4rc](https://github.com/Nasilem4rc]
