# Heart Disease Detection using Machine Learning

This project is a machine learning-based approach to detecting heart disease using patient data. It leverages logistic regression to classify whether a patient is likely to have heart disease based on various medical attributes.

## Project Overview

- **Goal**: Develop a predictive model to detect heart disease based on features such as age, sex, chest pain type, blood pressure, cholesterol level, and other medical indicators.
- **Dataset**: Utilizes the [Heart Disease UCI dataset](https://archive.ics.uci.edu/ml/datasets/Heart+Disease), which includes multiple health metrics for each patient.
- **Algorithm Used**: Logistic Regression

## Dataset

The dataset (`heart.csv`) includes the following columns:

1. **age**: Age of the patient
2. **sex**: Gender (1 = male, 0 = female)
3. **cp**: Chest pain type (0-3 values indicating types)
4. **trestbps**: Resting blood pressure (in mm Hg)
5. **chol**: Serum cholesterol in mg/dl
6. **fbs**: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)
7. **restecg**: Resting electrocardiographic results
8. **thalach**: Maximum heart rate achieved
9. **exang**: Exercise induced angina (1 = yes, 0 = no)
10. **oldpeak**: ST depression induced by exercise relative to rest
11. **slope**: Slope of the peak exercise ST segment
12. **ca**: Number of major vessels (0-3) colored by fluoroscopy
13. **thal**: Thalassemia (3 = normal; 6 = fixed defect; 7 = reversible defect)
14. **target**: Diagnosis of heart disease (1 = presence, 0 = absence)

## Project Structure

- **Data Preprocessing**: 
  - Loading the dataset.
  - Splitting into features (`X`) and target variable (`Y`).
  - Stratified train-test split to ensure balanced classes.

- **Model Training**:
  - A logistic regression model is used to classify the likelihood of heart disease.

- **Model Evaluation**:
  - Evaluated using **accuracy** on both training and test data to measure performance.

- **Prediction Example**:
  - An example input is used to test model prediction.

## Key Results

- **Training Accuracy**: The model achieved high accuracy on training data.
- **Testing Accuracy**: Demonstrated strong generalization with robust accuracy on test data.

## How to Run

1. **Clone the repository** and navigate to the project directory.
2. **Install necessary dependencies**:
   ```bash
   pip install numpy pandas scikit-learn
   ```
3. **Run the notebook**: Open the Jupyter Notebook to view the code and execute cells step-by-step.

4. **Run Model Predictions**:
   - You can input custom patient data to test the model. An example is provided in the notebook.

## Conclusion

The logistic regression model provides a straightforward yet effective way of detecting potential heart disease. This project highlights the importance of using medical data to assist in early detection of heart conditions.
