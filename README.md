# Gender and Age Classification

## Introduction
The **Gender and Age Classification** project is a tool powered by deep learning models that classifies **gender** (Male/Female) and predicts **age category** from images. This interactive application is deployed using **Streamlit**, providing a user-friendly interface for uploading images and getting real-time predictions.

## Project Overview
### What Was Accomplished?
1. **Training Two Models:**
   - A **Gender Classification Model** trained to predict gender as Male or Female.
   - An **Age Prediction Model** trained to categorize age into one of four groups:
     - **Young (0-18 years)**
     - **Youth (18-40 years)**
     - **Senior (40-60 years)**
     - **Old (60+ years)**

2. **Deployment Using Streamlit:**
   - An interactive web application was built to let users upload images and view predictions for both gender and age.

## How to Run the Project

Follow these steps to set up and run the project locally:

### Step 1: Clone the Repository
Download the project files to your local machine:
```bash
git clone <repository-link>
cd Gender_and_Age_Classification
```

### Step 2: Install Dependencies
Install the necessary Python packages:
```bash
pip install -r requirements.txt
```

### Step 3: Add Pre-Trained Models
Ensure the following pre-trained models are in the project directory:
- `age_model.h5`: The model for age prediction.
- `gender_classification_cnn_model.h5`: The model for gender classification.

If the models are not provided, download them from the specified links or contact the project owner.

### Step 4: Run the Application
Launch the Streamlit app:
```bash
streamlit run deployment.py
```

### Step 5: Access the App
Open your web browser and go to:
```
http://localhost:8501
```
Upload an image, and the app will display the predicted gender and age category.

## Project Structure
The project files are organized as follows:
```
Gender_and_Age_Classification/
├── Age_model.ipynb               # Notebook for training the age prediction model
├── Gender_model_vgg16-cnn.ipynb  # Notebook for training the gender classification model
├── deployment.py                 # Streamlit application script
├── requirements.txt              # Python dependencies file
├── age_model.h5                  # Pre-trained age prediction model
├── gender_classification_cnn_model.h5  # Pre-trained gender classification model
└── README.md                     # Project documentation
```

## Features
- **Interactive Interface**: Upload an image and get predictions instantly.
- **Gender Classification**: Predicts gender as either Male or Female.
- **Age Categorization**: Predicts age into one of the predefined categories.

## Example Output

### User Interface
(Placeholder for UI screenshot)
![UI Example](path/to/ui_screenshot.png)

### Predicted Results
- **Input**: Example image of a person.
- **Output**:
  - **Predicted Gender**: Male
  - **Predicted Age Category**: Youth (18-40 years)
