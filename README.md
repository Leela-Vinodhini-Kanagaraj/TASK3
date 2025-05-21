# TASK3 – Sports Results Processing

## Overview

This project is designed to process and analyze results from state-level athletics and swimming competitions. It includes Python scripts for data extraction and analysis, as well as Excel files containing raw and processed data.

## Repository Structure

- `Athletics_State_level.py` – Script to process athletics results  
- `Swimming_state_level.py` – Script to process swimming results  
- `ATH_All_Results.xlsx` – Consolidated athletics results  
- `SFI_All_Results.xlsx` – Consolidated swimming results  
- `Athletics_result.xlsx` – Raw athletics data  
- `swimming_results.xlsx` – Raw swimming data  
- `ath_results_pdfs/` – Directory containing athletics result PDFs  
- `sfi_results_pdfs/` – Directory containing swimming result PDFs  

## Tools and Libraries

- [`warnings`](https://docs.python.org/3/library/warnings.html) – Handle warning messages  
- [`requests`](https://pypi.org/project/requests/) – For sending HTTP requests  
- [`BeautifulSoup`](https://pypi.org/project/beautifulsoup4/) – For parsing HTML/XML content  
- [`os`](https://docs.python.org/3/library/os.html) – Interact with the operating system  
- [`pdfplumber`](https://pypi.org/project/pdfplumber/) – Extract text from PDF files  
- [`pandas`](https://pypi.org/project/pandas/) – Data analysis and manipulation  

## Getting Started

### 1. Clone the repository
git clone https://github.com/Leela-Vinodhini-Kanagaraj/TASK3.git

### 2.Install Dependencies
pip install pandas openpyxl requests beautifulsoup4 pdfplumber

### 3.Run the scripts_
python Athletics_State_level.py
python Swimming_state_level.py

## Contributing
Contributions are welcome! Please fork the repository, create a feature branch, and submit a pull request for any enhancements or bug fixes.
