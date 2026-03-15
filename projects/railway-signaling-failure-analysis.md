## Railway Signaling Failure Analysis

This project explores failure patterns in railway signaling systems using Python and data analysis techniques.  
The objective is to simulate how operational data can be analyzed to support maintenance decisions and identify critical infrastructure components.

### Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

### Data Generation
A simulated dataset representing railway signaling failures was created using Python.  
The dataset includes information such as:

- date of failure
- railway line
- station
- signaling system type
- failure type
- intervention time

This structure mimics real operational datasets used in infrastructure monitoring.

### Data Cleaning & Preparation
Data preprocessing was performed using **Pandas**, including:

- parsing timestamps
- handling missing values
- validating categorical variables
- preparing the dataset for aggregation and KPI calculation

The cleaning logic was modularized in a reusable Python module (`data_cleaning.py`).

### Exploratory Analysis
The dataset was analyzed to extract operational insights, including:

- failure frequency per railway line
- average intervention time by signaling system
- identification of stations with higher failure occurrence

### Visualization
Key patterns were visualized using **Matplotlib and Seaborn**, enabling quick identification of critical infrastructure segments and potential maintenance bottlenecks.

### Key Insight Example
Initial analysis shows how certain stations or system types may concentrate higher failure rates, suggesting where preventive maintenance strategies could be prioritized.

### Technical Repository
Full implementation available here:

👉 https://github.com/miguel-saldana/railway-signaling-failure-analysis
