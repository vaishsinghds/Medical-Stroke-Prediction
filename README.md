# Stroke Prediction Model

## Overview
This project aims to build a machine learning model for stroke prediction using healthcare data. The model will be trained on various features such as age, hypertension, heart disease, etc., to predict the likelihood of a person having a stroke.

## Dataset
The dataset used for this project is obtained from [Healthcare Dataset: Stroke Data](https://www.kaggle.com/fedesoriano/stroke-prediction-dataset) on Kaggle. It contains the following columns:

![Screenshot 2024-04-10 220920](https://github.com/vaishsinghds/Medical-Stroke-Prediction/assets/161769968/5959c70f-0ea9-42f5-bd4f-feb0e4936543)

- `id`: Patient ID
- `gender`: Gender of the patient (Male, Female, Other)
- `age`: Age of the patient
- `hypertension`: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
- `heart_disease`: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
- `ever_married`: "Yes" if the patient is married, "No" otherwise
- `work_type`: Type of occupation
- `Residence_type`: Area type of residence (Urban, Rural)
- `avg_glucose_level`: Average glucose level in blood
- `bmi`: Body mass index
- `smoking_status`: Smoking status of the patient
- `stroke`: 1 if the patient had a stroke, 0 otherwise

![output_14_2](https://github.com/vaishsinghds/Medical-Stroke-Prediction/assets/161769968/058b0be5-28c1-4f2e-a2bf-b69d837b8e71)

![output_14_4](https://github.com/vaishsinghds/Medical-Stroke-Prediction/assets/161769968/1ed66ac0-92f8-4086-8799-b101d918f22b)

![output_14_5](https://github.com/vaishsinghds/Medical-Stroke-Prediction/assets/161769968/9f43cf45-7aad-493f-af25-881539f32788)


## Libraries Used
- pandas
- seaborn
- matplotlib
- sklearn
- imblearn

## Model Building
1. **Importing Necessary Libraries**: Importing required libraries including pandas, seaborn, matplotlib, sklearn, and imblearn.
2. **Loading Data**: Load the dataset into a pandas DataFrame.
3. **Exploratory Data Analysis (EDA)**: Perform EDA to understand the data, check for missing values, duplicates, and visualize distributions and relationships between features.
4. **Data Preprocessing**: Preprocess the data by handling missing values, encoding categorical variables, and scaling numerical features.
5. **Model Training**: Train machine learning models such as Logistic Regression, Random Forest, and Gradient Boosting Classifier.
6. **Model Evaluation**: Evaluate the performance of each model using appropriate evaluation metrics such as accuracy, precision, recall, and F1-score.
7. **Hyperparameter Tuning**: Fine-tune the hyperparameters of the best performing model using techniques like grid search or random search.
8. **Model Deployment**: Deploy the final model for making predictions on new data.

## Logestic Regression Results:

![Screenshot 2024-04-10 221306](https://github.com/vaishsinghds/Medical-Stroke-Prediction/assets/161769968/94309a99-2160-47b2-bf2b-98d55ef73a93)

## Random Forest Results:

![Screenshot 2024-04-10 221316](https://github.com/vaishsinghds/Medical-Stroke-Prediction/assets/161769968/c76e9c16-604b-4b10-89fe-99e6b50c4231)

## Contributing
Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.


