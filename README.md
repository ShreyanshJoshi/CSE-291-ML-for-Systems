<center>

# Virtualization and Cloud Computing (CSE 291)  
# ML for Systems: Classifying Queries

</center>



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
    │   ├── test_accuracies.png: Image showing test accuracies
    │   └── test_f1.png: Image showing test F1 scores
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
        │   ├── proccessed-data.csv: Processed data CSV file
        │   ├── query-runtime-advising.csv: Runtime data for advising data
        │   ├── ... (other runtime CSV files)
        └── table_sizes.json: JSON file containing table sizes
