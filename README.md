# CodeCraft Infotech — Data Science Internship Tasks (01–05)

**Intern:** Rohan Kate  
**Organization:** CodeCraft Infotech  
**Domain:** Data Science

This repository contains my completed tasks for the CodeCraft Infotech Data Science Internship. The projects demonstrate Python-based data analysis, exploratory data analysis (EDA), data visualization, classification, and sentiment analysis.

## Tasks Overview

| Task | Project | What it covers |
|---|---|---|
| 01 | Population Data Visualization | Explores country population data and visualizes the most populous countries and population distribution. |
| 02 | Titanic Dataset — EDA | Examines passenger data and explores survival patterns by gender, passenger class, age, and fare. |
| 03 | Bank Marketing — Decision Tree Classification | Builds a scikit-learn decision-tree classification pipeline to predict whether a customer subscribes to a term deposit. |
| 04 | Text Sentiment Analysis | Uses TF-IDF text features and logistic regression to classify sentiment and evaluate model performance. |
| 05 | US Traffic Accident — EDA | Explores traffic-accident data, missing values, accident severity, and cities with high accident counts. |

## Tech Stack

- **Language:** Python 3
- **Data manipulation:** pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Machine learning:** scikit-learn
- **Text processing:** TF-IDF vectorization and logistic regression
- **Notebook environment:** Jupyter Notebook

## Repository Structure

```text
CODECRAFT_DS_ALL_TASKS_01_02_03_04_05_Rohan_Kate_NO_MD/
├── README.md
├── SUBMISSION_INFO.txt
├── CODECRAFT_DS_01/
│   ├── task01_data_visualization.py
│   ├── cleaned_population_latest_year.csv
│   ├── requirements.txt
│   └── output charts (.png)
├── CODECRAFT_DS_02/
│   ├── task02_titanic_eda.py
│   ├── titanic_cleaned.csv
│   ├── eda_summary.csv
│   ├── requirements.txt
│   └── output charts (.png)
├── CODECRAFT_DS_03/
│   ├── task03_decision_tree.py
│   ├── data/bank-full.csv
│   ├── model_metrics.txt
│   ├── requirements.txt
│   └── evaluation/visualization outputs (.png)
├── CODECRAFT_DS_04/
│   ├── task04_sentiment_analysis.py
│   ├── cleaned_sample_5000.csv
│   ├── model_metrics.txt
│   ├── requirements.txt
│   └── output charts (.png)
└── CODECRAFT_DS_05/
    ├── task05_traffic_accident_eda.py
    ├── source_us_accident_eda.ipynb
    └── requirements.txt
```

*The tree is abbreviated; refer to each task folder for all included files.*

## Getting Started

1. Install Python 3.10 or newer (Python 3.9+ should also work with compatible package versions).
2. Clone or download this repository and open the project folder.
3. For a task, open a terminal in that task's directory and install its dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the desired Python script from its task directory. For example:

   ```bash
   cd CODECRAFT_DS_01
   python task01_data_visualization.py
   ```

   Repeat with the corresponding script in each task folder.

### Task 05 dataset note

The Task 05 script expects `US_Accidents_Dec21_updated.csv` in the `CODECRAFT_DS_05` folder. That dataset is not included in this repository archive. Obtain the dataset from an authorized source, place it beside `task05_traffic_accident_eda.py`, or update the `DATA_PATH` variable in the script before running it. The supplied Jupyter notebook may also reference a local dataset path.

## Outputs

The task folders include generated plots, cleaned/sample data files, and model metric summaries where applicable. The scripts may display charts interactively and print summaries or classification metrics in the terminal.

## Skills Demonstrated

- Data cleaning and preprocessing
- Exploratory data analysis and descriptive statistics
- Data visualization and interpretation
- Categorical and numerical feature handling
- Decision-tree classification and model evaluation
- Text vectorization and sentiment classification
- Working with CSV files and Jupyter notebooks

## Notes

- Run scripts from their respective task folders so relative file paths resolve correctly.
- Results can vary if datasets, dependency versions, or preprocessing steps change.
- Use the dataset and model results responsibly; exploratory patterns do not automatically imply causation.

## Acknowledgement

Prepared as part of the **CodeCraft Infotech Data Science Internship**.

## Author

**Rohan Kate**
