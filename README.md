
# Project: Job Role Recommendation App

### Create virtual Environment

```bash
conda create -n env5006 python=3.11 -y
conda activate env5006
pip install --upgrade pip
pip install -r requirements.txt
```

### Run the Main.py

```bash
streamlit run Main.py
```

### Dataset:
Kaggle's Annual Machine Learning and Data Science Survey from the past three years (2020-2022)

### Project Tasks
#### [(streamlit app link)](https://it5006-kxx3jsq4iscaa9vyoqohvk.streamlit.app/)

### Files structure   
You are recommended to run through notebooks from 0 to 3.
0Preprocess.ipynb is to preprocess the three datasets and merge them by the same questions    
1Data_Cleaning.ipynb is further data cleaning and extract useful features from dirty data.
2Model_Training&Evaluation.ipynb is model training and evaluation. We did feature selection and evaluated three models.
3GBM_Model_training.ipynb is the final model training and model exportation. We selected GBM and exported pretrained model for our streamlit app to use.

### Technical Report
The Technical Report.pdf provides an overall technical summary of the entire project. This report includes detailed descriptions of the methodologies, data preprocessing steps, model training processes, and evaluation metrics used in the project.

Feel free to explore the project and use the Job Role Recommendation App to find the best job roles based on your skills and experience!