# **PHYS 139 Project**

## **Overview**

This repository contains Jupyter notebooks for the PHYS 139 project, focusing on the exploratory data analysis, preprocessing, and model training to predict superconducting transition temperature of different materials.

## **Files**

### **1. `PHYS_139_Project_EDA_Data-Preprocessing.ipynb`**

- **Description**: This notebook includes exploratory data analysis (EDA) and visualization. It also covers data preprocessing, such as cleaning problematic data and handling outliers.
- **Requirements**: 
  - Ensure the `primary.tsv` file is downloaded.
  - Ensure the data files are in the same directory as the notebook

### **2. `PHYS_139_Project_Model_Final.ipynb`**

- **Description**: This notebook is used for training the model to predict superconductive materials.
- **Data Files**:
  - You can obtain the necessary data by running the preprocessing notebook.
  - Alternatively, you can skip the preprocessing notebook entirely and use the provided `cleaned_supercond_df.csv` and `final_design_matrix_supercond.csv` files.
- **Requirements**:
  - -Ensure the `cleaned_supercon_df.csv` and `final_design_matrix_supercond.csv` files are downloaded and in the same directory

## **Setup Instructions**

1. **Download Data Files**: Ensure all required data files (`primary.tsv`, `cleaned_supercond_df.csv`, `final_design_matrix_supercond.csv`) are downloaded.
2. **Directory Requirements**: Ensure all required data files are in the same directory as the notebook
3. **Run Notebooks**: Execute the notebooks in the following order:
   1. `PHYS_139_Project_EDA_Data-Preprocessing.ipynb` to preprocess and clean the data.
   2. `PHYS_139_Project_Model_V2.ipynb` to train the model using the cleaned data.
