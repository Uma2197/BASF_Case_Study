
BASF Case Study: Data Analysis & Anomaly Detection
Project Overview
This project focuses on analyzing and interpreting measurement data to identify trends, detect anomalies, and improve data quality using statistical and machine-learning methods. The results are visualized in a dashboard for effective reporting.

Project Structure
bash
Copy
Edit
├── build/           # Compiled outputs and distribution files  
├── data/            # Raw and processed datasets  
├── docs/            # Documentation files - model justification, project summary  
├── models/          # Machine learning models and scripts  
├── plots/           # Generated visualizations and charts  
├── reports/         # Analysis reports and insights  
├── source/          # Sphinx documentation source files  
│   ├── _static/     # Static files for documentation  
│   ├── _templates/  # Documentation templates  
│   ├── anomaly_detection_charge_efficiency.rst  # Analysis report  
├── src/             # Main source code for data analysis  
├── tests/           # Unit and integration tests (pytest)  
├── main.py          # Entry point for executing analysis  



Setup Instructions


Clone the Repository

bash
git clone <repo_url>
cd <repo_folder>


Create a Virtual Environment

bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

Install Dependencies

bash
pip install -r requirements.txt

Run the Analysis

bash
python main.py


Run Tests

bash
pytest tests/


Generate Documentation

bash

cd docs
make html
