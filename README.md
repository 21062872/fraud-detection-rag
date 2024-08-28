# Enhanced Fraud Detection: A comparative study of Ensemble Learning, Machine Learning and Retrieval Augmented Generation

## Overview

This repository has one main notebook file [View the Notebook](code_files/main.ipynb)
All code related to data loading, pre-processing, EDA, Feature engineering, Training and Testing is included in this. Code is structured in object oriented way using classes and functions to maintain a proper structure and reduce redundancy.

Code Structure is as below
* Environment Setup
    - Setting Up the Environment for Code Execution
* Data Ingestion
    - Loading data from external file to the dataframe
* Data Pre-processing
    - Shaping and cleansing the data before model training.
* Explorative Data Analysis (EDA)
    - Visualizing the dataset with various plots to identify patterns, relationships, and data distributions.
* Feature Engineering
    - Creating new features from raw data to enhance model performance.
* Random Forest Classifier Model
    - Multiple experiments were conducted using the Random Forest model. Basic configurations, customized, and fine-tuned models were compared and analyzed. Additionally, the performance of the Random Forest on raw and oversampled datasets was investigated.
* Neural Network Model
    - Neural Network models with both basic and customized settings were evaluated. The performance of Neural Networks on raw and oversampled datasets was also assessed.
* XGBoost
    - Several experiments were conducted with XGBoost, particularly to evaluate its performance on raw datasets versus SMOTE-oversampled datasets.
* Retrieval Augmented Generation
    - This section explores various tests to evaluate the efficiency of retriever models in detecting anomalies using Euclidean and cosine distance matrices. Experiments were also conducted using BERT and OpenAI embeddings to identify the optimal embedding for the dataset structure. A prototype model was developed using similarity search to demonstrate how RAG can be applied to fraud detection. The performance of similarity search and ranking using the FAISS index/vector store was measured with various metrics.

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
