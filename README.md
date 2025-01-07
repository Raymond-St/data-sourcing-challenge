# data-sourcing-challenge
DU Bootcamp Module 6 "Data Sourcing" Challenge

## Overview
- Student prepared dataset for a prediction system that looks at the diffential timing of Geomagnetic Storms (GSTs) that are caused by so-called Coronal Mass Ejections (CMEs).   Data obtained from the NASA API, GST data and its CME data, are merged and the time difference is computed.
  
## Table of Contents
- [Requirements]
- [Installation]
- [Project Structure]
- [Usage]
- [Analysis Features]
- [Data Structure]
- [Repository Information]
- [Contributing & Contact]
- [License]

### Requirements
- Python 3.x
- pandas
- numpy
- Jupyter Notebook

### Installation
1. Clone the repository:
"""
using bash
git clone URL: 
"""

2. Install required packages:
"""bash
pip install pandas numpy jupyter
"""

## Project Structure
"""
retrieve_data/
│
├── Resources/
│   ├── NASA API
│   └── CMEs and GSTs
│
├── retrieve_data.ipynb
├── README.md

"""

## Usage
1. Launch Jupyter Notebook:

2. Run cells sequentially to perform the analysis and see the results

3. open the CSV ("cme_gst_data.csv")

## Analysis Features
The notebook performs the following analyses:

1. **Data Preparation**
   - Retrieve API Data for CME

2. **Data Preparation**
   - Create DataFrame
   - Prepare Data
   - Merge DataFrames

3. **Export CSV with Results**
   - Results in CSV for sharing with peers
   - 

## Data Structure
The analysis uses NASA Solar storm data with the following key fields:
- 'gstID': NASA identifier for storm
- 'startTime_GST': NASA storm start time
- 'startTime_CME': NASA CME start time
- 'timeDiff': Identified by this python program to Identify the time difference between a GST and CME


## Repository Information
- Remote: https://github.com/Raymond-St/data-sourcing-challenge
- Local: C:\Users\resto\AI\Projects\Module_6\

## Contributions & Contact
If interested, or for questions / feedback on this NASA data-sourcing-challenge, please contact: RStover@Gmail.com

## License
This project is not licensed for any public use. This data-sourcing-challenge project is for educational purposes and uses API data obtained from NASA. This body of work is for reference only and is Not intended for production use.
