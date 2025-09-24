# Lung Cancer Prediction Web Application

A Flask-based web application that predicts lung cancer risk using machine learning. The application uses a KNN model trained on patient attributes to provide risk assessment.

## 📋 Project Overview

This web application provides a user-friendly interface for healthcare providers to assess lung cancer risk based on non-invasive patient data. The model uses 15 different patient attributes including demographics, lifestyle habits, and early symptoms.

## 🛠️ Features

- **Web Interface**: Easy-to-use form for inputting patient data
- **Real-time Prediction**: Instant risk assessment results
- **Input Validation**: Comprehensive error handling and data validation
- **Responsive Design**: Works on different devices
- **Model Interpretability**: Clear binary output (Cancer Detected/No Cancer)

## 📊 Model Details

- **Algorithm**: K-Nearest Neighbors (KNN)
- **Input Features**: 15 patient attributes
- **Output**: Binary classification (Lung Cancer / No Lung Cancer)
- **Preprocessing**: Data scaling using StandardScaler

### Input Features:
1. Gender (M/F)
2. Age
3. Smoking (YES/NO)
4. Yellow fingers (YES/NO)
5. Anxiety (YES/NO)
6. Peer pressure (YES/NO)
7. Chronic Disease (YES/NO)
8. Fatigue (YES/NO)
9. Allergy (YES/NO)
10. Wheezing (YES/NO)
11. Alcohol consumption (YES/NO)
12. Coughing (YES/NO)
13. Shortness of Breath (YES/NO)
14. Swallowing Difficulty (YES/NO)
15. Chest pain (YES/NO)

## 🏗️ Project Structure
