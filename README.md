# Enhanced Fraud Detection: A comparative study of Ensemble Learning, Machine Learning and Retrieval Augmented Generation

## Overview

This repository has one main notebook file [View the Notebook](code_files/main.ipynb)
All code related to data loading, pre-processing, EDA, Feature engineering, Training and Testing is included in this. Code is structured in object oriented way using classes and functions to maintain a proper structure and reduce redundancy.

Code Structure is as below
* Environment Setup
    - Installing required libraries, verification of GPU and setting the environment to execute code is ensured in this section
* Data Ingestion
    - Loading data from external file to the dataframe
* Data Pre-processing
    - Shaping, cleansing the data before model training
* Explorative Data Analysis (EDA)
    - Visulize dataset with numerous plots to identify patterns, inter-relationships and any data distributions
* Feature Engineering
    - Creatng new features from raw features 
* Random Forest Classifier Model
    - In this section, multiple experiments were carried out. Random forest model with basic configuration, with customized and fine tuned model are compared and analysed. Also how Random Forest perform on raw dataset and oversampled dataset is also investigated.
* Neural Network Model
    - NN model with basic and customized settings are evaluated. Furthermore, how NN perform on raw and oversample dataset is also measured
* XGBoost
    - Multiple experiments on XGBoost is carried out, specially how it behaves for raw dataset and for SMOTE oversampled dataset
* Retrieval Augmented Generation
    - In this section, multiple tests were considered. First tests were carried out to see how efficient the retriever model in detecting anomalies using euclidean and cossine distance matrix is evaluated. Same experiment is done with BERT and OPEN AI embeddings to identify the optimal embedding for the dataset structure. Then using similarity search a prototype model is created to showcase how RAG can be applied in fraud detection. Performance of similarity search and ranking on FAISS index/vector store is measured using variouse metrics.

## Files
* Notebook : code_files/main.ipynb
* Related libraries and modules : code_files/requirements.txt
* Dataset : data_files/dataset.csv
* Final Project Report : documents/Enhancing Fraud Detection by Ensemble Machine Learning and RAG by Tharinda Arachchi.docx
* Draft Project Report : documents/Final Project Report - 21062872.docx
* Logbook : documents/Project+Logbook+Sem+C+Data+Science+2023.docx
* Data Management Plan : documents/pdm_plan_v_1.1.docx

## Getting Started
### Prerequisites
* Python 3.x
* Relevant Python libraries as listed in [View Requirements](code_files/requirements.txt)

### Special Notes
* For the experiments involved with Open AI embeddings, add a authentic Open AI key to execute. I have excluded the key from code for security purposes.
