# Coronal Mass Ejection (CME) and Geomagnetic Storm (GST) Analysis

## Project Overview

This Jupyter Notebook provides a comprehensive analysis of Coronal Mass Ejection (CME) and Geomagnetic Storm (GST) data retrieved from NASA's DONKI (Detailed Online Knowledgebase for Solar-Terrestrial Physics) API. The project aims to investigate the temporal relationship between solar eruptions (CMEs) and their potential impacts on Earth's magnetic field (GSTs).

## Key Features

- Retrieves solar event data from NASA's DONKI API
- Processes and cleans CME and GST datasets
- Analyzes the time delay between CME events and subsequent Geomagnetic Storms
- Provides statistical insights and visualizations

## Data Sources

- NASA DONKI API
  - Coronal Mass Ejection (CME) data
  - Geomagnetic Storm (GST) data

## Methodology

1. **Data Retrieval**
   - Uses chunked API requests to handle large date ranges
   - Covers solar events from 2013-05-01 to 2024-05-01
   - Implements error handling and rate limiting

2. **Data Processing**
   - Cleans and transforms raw JSON data into pandas DataFrames
   - Matches CME events with corresponding Geomagnetic Storms
   - Calculates time differences between events

3. **Analysis Techniques**
   - Time series analysis
   - Statistical descriptive analysis
   - Histogram visualization of time delays

## Key Findings

- Total CME records retrieved: 5,555
- Total GST records retrieved: 118
- Matched CME-GST events: 52

### Time Difference Statistics
- Mean time between CME and GST: ~2.97 days
- Median time: ~2.75 days
- Minimum time: ~1.36 days
- Maximum time: ~6.13 days

## Visualization

The project includes a histogram visualizing the distribution of time delays between CME and GST events, highlighting mean and median values.

## Requirements

- Python 3.7+
- pandas
- requests
- matplotlib
- python-dotenv

## Installation

1. Clone the repository
2. Install required dependencies:
   ```
   pip install pandas requests matplotlib python-dotenv
   ```
3. Set up *YOUR* NASA API key in a `.env` file

## Usage

Run the Jupyter Notebook to:
- Retrieve solar event data
- Perform data analysis
- Generate visualizations

## Limitations

- Data dependent on NASA DONKI API availability
- Potential gaps in solar event reporting
  - Limited to specified date range: 1-5-2013 through 5-9-2024

## Future Work

- Expand date range
- Implement more advanced statistical analysis
- Develop predictive models for GST occurrence
- Reduce the size of the Jupyter file - condense and improve efficiency of python code

## Contributing

Contributions, issues, and feature requests are welcome. 

## License

Mozilla Public License (Version 2.0)

## Contact

rstover (at) gmail

## Acknowledgments

- NASA DONKI API
- Space weather research community
- 2U instructor and staff