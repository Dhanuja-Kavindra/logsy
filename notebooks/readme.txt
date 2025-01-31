
# **Logsy Anomaly Detection - HDFS, BGL, and OpenStack Datasets**

This repository contains **three Jupyter notebooks** designed to examine **HDFS, BGL, and OpenStack datasets** using the **Logsy anomaly detection model**. The implementation is based on the paper:

> **Self-Attentive Classification-Based Anomaly Detection in Unstructured Logs**  
> **S. Nedelkoski, J. Bogatinovski, A. Acker, J. Cardoso, and O. Kao**  
> *2020 IEEE International Conference on Data Mining (ICDM), Sorrento, Italy, 2020, pp. 1196-1201.*  
> DOI: [10.1109/ICDM50108.2020.00148](https://doi.org/10.1109/ICDM50108.2020.00148)  
> Keywords: *Deep learning, Semantics, Training data, Reliability, Computer security, Task analysis, Anomaly detection, Log data, Transformers, Systems reliability*

---

## **Repository Source and Modifications**
This repository is **forked** from the original implementation at:  
[**NLP-Project-Anomaly-Detection**](https://github.com/Hamideh-ghanadian/NLP-Project-Anomaly-Detection)  

Several modifications were made to **accommodate new datasets and fix coding errors** in the original implementation.

---

## **Datasets**
The datasets used in this project are **preprocessed and available in the following Google Drive folder**:  
[**Preprocessed Datasets**](https://drive.google.com/drive/folders/1dP7YGJdBXJXNiFbcmHUNdvtM6-5EIGeh?usp=sharing)

The **original datasets** were sourced from the **LogHub repository**:  
[**LogHub Datasets**](https://github.com/logpai/loghub)  

---

## **Setup Instructions**
### **Step 1: Prepare the Google Drive Environment**
1. **Create a directory in your Google Drive** with the name **"LogSy"**.
2. **Upload the datasets** from the provided Google Drive folder into this **"LogSy"** directory.

### **Step 2: Run the Jupyter Notebooks**
Each notebook corresponds to a different dataset:
- **HDFS Notebook**: Runs Logsy on the HDFS dataset.
- **BGL Notebook**: Runs Logsy on the BGL dataset.
- **OpenStack Notebook**: Runs Logsy on the OpenStack dataset.

---

## **Implementation Details**
The **Logsy model** is based on **transformers** and uses **self-attention mechanisms** to classify anomalies in system logs. This project applies Logsy to multiple log datasets and benchmarks its performance across different environments.

### **Changes from the Original Implementation**
- **Modified code blocks** to support **HDFS, BGL, and OpenStack datasets**.
- **Fixed errors in the original implementation** to ensure smoother execution.
- **Preprocessed datasets** for faster and more efficient anomaly detection.

---

