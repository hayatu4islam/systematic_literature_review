# Systematic Literature Review
## Overview
This repository contains the dataset and relevant materials for a systematic literature review (SLR) on fault detection in cyber-physical systems (CPS). The dataset includes research papers, extracted data, and analysis results, providing a comprehensive overview of the current state of research in this field.
## Repository Structure
- **data**/: Contains the datasets used for the SLR.
  - **`papers.csv`**: A CSV file containing the list of papers included in the review.
  - **`extracted_data.csv`**: A CSV file with data extracted from the included papers.
  - **`metadata/`**: Directory containing metadata files for each paper.
    
- **scripts/**: Includes scripts used for data extraction, analysis, and visualization.
  - **`data_extraction.py`**: Script for extracting data from the papers.
  - **`visualization.py`**: Python script for generating visualizations from the analysis results.
    
- **docs/**: Documentation and supporting materials.
  - **`SLR_protocol.pdf`**: The protocol followed for conducting the systematic literature review.
  - **`SLR_report.pdf`**: The final report of the SLR.
  - **`README.md`**: This readme file.
  
- **results/**: Contains the results of the data analysis and visualizations.
  - **`figures/`**: Directory with visualizations generated from the analysis.
  - **`summary_statistics.csv`**: A CSV file with summary statistics of the analyzed data.

## Getting Started
### Prerequisites
- Python 3.7 or higher
- Required Python packages (listed in `requirements.txt`)

### Installation
1. Clone the repository:
<pre>
  git <span style="color:orange;">clone</span> https://github.com/hayatu4islam/systematic_literature_review
  <span style="color:orange;">cd</span> SLR-Fault-Detection-CPS
</pre>
2.  Install the required Python packages

### Usage
1. Data Extraction:
- Use the 'data_extraction.py' script to extract data from the collected papers.
<pre>
```bash
# List all files in the current directory
ls -la

# Change to the home directory
cd ~

# Display the current path
pwd
```
</pre>

2.  Visualisation:
- Generate visualisation from the analysis results using 'visualisation.py'
<pre>
  ```bash
  python scripts/data_extraction.py
  ```
  
</pre>
3.   
