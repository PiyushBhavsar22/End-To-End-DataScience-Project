# 🍷 End-to-End Wine Quality Prediction Project

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.2.2-yellow)
![MLflow](https://img.shields.io/badge/MLflow-2.4.1-red)
![License](https://img.shields.io/badge/License-GNU-green)

A complete MLOps pipeline for predicting wine quality using machine learning. This project demonstrates industry best practices for building production-ready ML systems.

## 🌟 Overview
Predict wine quality (0-10 scale) using physicochemical properties. Implements a robust ML pipeline with:
- 1️⃣Automated data validation
- 2️⃣Feature engineering
- 3️⃣Model training & evaluation
- 4️⃣Experiment tracking
- 5️⃣Configuration management

## 📋 Key Features
- 🎯 **Modular Pipeline Architecture**
- 🎯 **Data Version Control**
- 🎯 **Hyperparameter Tuning**
- 🎯 **Model Performance Tracking**
- 🎯 **YAML Configuration Management**
- 🎯 **Continuous Integration Ready**

## 🛠️ Workflows (ML Pipeline)
- 1️⃣ **Data Ingestion** 📥 - Load datasets
- 2️⃣ **Data Validation** ✅ - Schema enforcement & Check for missing or null values
- 3️⃣ **Data Transformation** 🔄 - Feature engineering & preprocessing
- 4️⃣ **Model Training** 🤖 - Multiple algorithm support with hyperparameter tuning
- 5️⃣ **Model Evaluation** 📊 - Assess model performance using metrics like RMSE, R², MAE & model comparison

## ⚙️ Technologies Used
| Category        | Technologies                          |
|-----------------|---------------------------------------|
| **Core ML**     | Scikit-learn, ElasticnetModel         |
| **Workflow**    | MLflow, PyYAML                        |
| **Data**        | Pandas, NumPy                         |
| **Visualization**| Matplotlib, Seaborn                  |
| **DevOps**      | Dagshub, DVC                          |

## 📂 Project Structure

```bash
📦 Wine-Quality-Prediction
├── 📂 src
│   ├── 📂 components         # ML pipeline components
│   ├── 📂 config             # Configuration files
│   ├── 📂 pipeline           # Complete workflow
│   ├── 📂 utils              # Helper functions
│   ├── main.py               # Execution script
│   ├── entity.py             # Data class entity
├── 📂 data                   # Raw and processed data
├── 📂 notebooks              # Jupyter notebooks for EDA
├── 📜 config.yaml            # Global project configurations
├── 📜 params.yaml            # Model hyperparameters
├── 📜 schema.yaml            # Data schema definition
├── README.md                 # Project Documentation
```

## 🚀 Installation

### 1️⃣ Clone repository:
   ```bash
   git clone https://github.com/yourusername/wine-quality-prediction.git
   cd wine-quality-prediction
```

### **2️⃣ Create & Activate a Virtual Environment**:

```bash
python -m venv venv
source venv/bin/activate  # For macOS/Linux
venv\Scripts\activate  # For Windows
```

### **3️⃣ Install Dependencies**:

```bash
pip install -r requirements.txt
```

### **4️⃣ Run the Pipeline**:

```bash
python main.py
```
   
