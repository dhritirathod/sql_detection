# SQL Injection Detection
Diploma project based on detecting malicious query using machine learning algorithm.  
Scope of the project: Use Machine Learning to detect SQL injection.  
**Dataset**: https://www.kaggle.com/sajid576/sql-injection-dataset  
**App link**: [SQL Detection](https://dhritirathod-sql-detection-streamlit-app-496fpk.streamlitapp.com/)

Directory structure:
```
sqli_detection
├── streamlit_app.py     Main file to run the streamlit app_
|── prediction_module.py Prediction module with all the utility functions
├── requirements.txt    
├── README.md
├── Model
    ├──final_RFC_FE_model.model  Pickled best RF Model
    ├──tfidf_vec.sav             Pickled TFIDF vectorizer
├── Notebook             Folder for jupyter notebooks
|── data                 Folder for required data 
```

## How to run in local
Clone the repo using git clone:
```
git clone https://github.com/dhritirathod/sql_detection
```
Install dependencies using pip:  
```
pip install -r requirements.txt  
```
Go to CMD and run the following command:  
```
streamlit run streamlit_app.py 
```
(Run it from the root directory of the project).
