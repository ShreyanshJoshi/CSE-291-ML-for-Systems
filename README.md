# Virtualization and Cloud Computing (CSE 291) <br> ML for Systems: Classifying Queries

Cloud systems have the potential to optimize their performance by making informed design decisions based on prior knowledge of workloads before their execution. One crucial aspect of this is understanding the expected execution time of SQL queries. The ability to predict whether a SQL query will have a long or short execution time can significantly impact the efficiency of resource allocation and scheduling within the cloud environment. This project aims to address the challenge of predicting the runtime of SQL queries using machine learning techniques.

## Project Directory Structure

The following is the directory structure of the project, along with a brief description of each file:

    .
    ├── README.md
    ├── code
    │   ├── EDA.ipynb: Exploratory Data Analysis notebook
    │   ├── data-preprocessing.ipynb: Data preprocessing notebook
    │   ├── feature-preprocessing.ipynb: Feature preprocessing notebook
    │   ├── get_table_size.ipynb: Notebook for getting table sizes
    │   ├── model_selection_evaluation.ipynb: Notebook for model selection and evaluation
    └── data
        ├── csv
        │   ├── advising.csv: CSV file for advising data
        │   ├── atis.csv: CSV file for atis data
        │   ├── ... (other CSV files)
        ├── db
        │   ├── advising.sql: SQL file for advising data
        │   ├── atis.sql: SQL file for atis data
        │   ├── ... (other SQL files)
        │   ├── export.py: Python script for converting from SQLite to MySQL database
        ├── json
        │   ├── advising.json: JSON file for advising data
        │   ├── atis.json: JSON file for atis data
        │   ├── ... (other JSON files)
        ├── runtime
        │   ├── processed-data.csv: Processed data CSV file
        │   ├── query-runtime-advising.csv: Runtime data for advising data
        │   ├── ... (other runtime CSV files)
        └── table_sizes.json: JSON file containing table sizes
