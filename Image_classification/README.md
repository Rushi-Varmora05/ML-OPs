# RUSHI VARRMORA (25PGAI0142)
# Image Classification Project

## Overview
This project focuses on building and deploying an image classification model using machine learning operations (MLOps) practices. The goal is to automate the process of training, validating, and deploying a model that can classify images into predefined categories.

## Project Structure
```
.
├── data
│   ├── raw
│   ├── processed
├── notebooks
│   ├── data_preprocessing.ipynb
│   ├── model_training.ipynb
├── src
│   ├── data_preprocessing.py
│   ├── model_training.py
│   ├── model_evaluation.py
├── models
│   ├── saved_model
├── README.md
├── requirements.txt
```



## Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

 ```sh
    uvicorn app.Main:app --reload
 ```

    