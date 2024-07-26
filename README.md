# Systematic Literature Review
## Overview
This repository contains the dataset and relevant materials for a systematic literature review (SLR) on fault detection in cyber-physical systems (CPS). The dataset includes research papers, extracted data, and analysis results, providing a comprehensive overview of the current state of research in this field.
## Repository Structure
- **data**/: Contains the datasets used for the SLR.
  - **`papers.csv`**: A CSV file containing the list of papers included in the review.
  - **`extracted_data.csv`**: A CSV file with data extracted from the included papers.
  - **`metadata.csv`**: A CSV file containing metadata files for each database.
    
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
  git <span style="color: orange;">clone</span> https://github.com/hayatu4islam/systematic_literature_review
  <span style="color: red;">cd</span> SLR-Fault-Detection-CPS
</pre>
2.  Install the required Python packages
<pre>
  pip install -r requirements.txt
</pre>

### Usage
1. Data Extraction:
- Use the 'data_extraction.py' script to extract data from the collected papers.
<pre>
python scripts/data_extraction.py
</pre>

2.  Visualisation:
- Generate visualisation from the analysis results using 'visualisation.py'
<pre>
  python scripts/data_extraction.py  
</pre>

## Data Description
**papers.csv**
- **`Document_Title`**: title of the paper.
- **`Authors`**: Authors of the paper.
- **`Authors_Affiliations`**: Affiliations of the authors.
- **`Publication_Title`**: Title of the publication (i.e. journal or conference title).
- **`Publication_Year`**: Year of publication.
- **`Abstract`**: Abstract of the paper.

**extracted_data.csv**
- **`paper_id`**: Unique identifier for each paper.
-   a
-   b
-   c

## Contributing
We welcome contributions to this repository. If you have suggestions, bug reports, or enhancements, please submit a pull request or open an issue.
1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request with a detailed description of your changes.

## Acknowledgements
We thank all the researchers whose work contributed to this dataset and the systematic literature review. A special recognition to Hanouf al-Ghanmy.
