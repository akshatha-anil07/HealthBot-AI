MediGuide- Your Personal Health Navigator

## Overview
This Healthcare Chatbot is designed to assist users in understanding their symptoms and suggest possible diseases based on the input symptoms. It uses machine learning models, specifically a Decision Tree Classifier and Support Vector Classifier (SVC), to make predictions about potential health issues.

## Features
- **Symptom Recognition**: Input symptoms to receive potential disease predictions.
- **Decision Tree and SVC Models**: Utilizes two machine learning models to improve prediction accuracy.
- **User-Friendly Interface**: Interactive console-based interface for user input.
- **Precaution and Description Lookup**: Provides users with disease descriptions and precautionary measures based on predicted diseases.

## Technologies Used
- Python
- Modin(Intel Extensions used in place of Pandas)
- Scikit-learnex(Intel Extension used in place of Sklearn)
- NumPy
- CSV

## Why Intel Extensions?
- Intel AI Tools facilitate the development and deployment of robust machine learning models. In this project, we utilize its capabilities to analyze symptom data and predict potential health conditions effectively, improving the chatbot's responsiveness and accuracy.
- Folder with "intel_extensions" contains the code for the chatbot which was designed to make a chatbot using intel extensions such as modin and scikit-learn

## Performace Metrics
| Accuracy | F1 Score |
| ------------- | ------------- |
DecisionTreeClassifier| 0.97 | 1.0  |
SVM| 1.0  | 1.0  |

## Datasets
- 80% of the data is used for training and 20% is used for testing.
- Train_data.csv: Training dataset containing symptoms and corresponding diseases.
- Test_data.csv: Testing dataset for model evaluation.
- Description.csv: Descriptions of diseases.
- severity.csv: Severity levels for symptoms.
- precaution.csv: Precautions for different diseases.

## Usage
- Run the chatbot:
      python chatbot.py
- Follow the prompts in the console to input your name and symptoms.
- The chatbot will provide disease predictions and related information.

## How It Works
- The chatbot loads training and testing data from CSV files.
- It preprocesses the input data, encodes categorical variables, and splits it into training and testing datasets.
- Two models (Decision Tree and SVC) are trained on the data.
- User input is processed to match symptoms with known conditions, providing predictions and additional information like 
  disease descriptions and precautions.



## Example Usage
![image](https://github.com/user-attachments/assets/8265c07b-9166-4c96-b022-2837edd45a75)

![image](https://github.com/user-attachments/assets/65f95326-6b1f-4297-b090-4853d0105682)



