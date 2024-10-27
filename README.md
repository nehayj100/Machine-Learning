# Machine Learning Projects Repository

## Motivation
The field of machine learning offers powerful tools to analyze data and make predictions across various domains. This repository showcases multiple projects employing different machine learning algorithms to solve real-world problems, ranging from image classification to regression analysis and predictive modeling. By demonstrating diverse applications, this collection aims to provide insights into the capabilities and versatility of machine learning techniques.

## About

### 1. CNN: MNIST Classification
This project utilizes a Convolutional Neural Network (CNN) to classify handwritten digits from the MNIST dataset.

- **Data**: MNIST handwritten digit dataset
- **Features**: 
  - 28x28 pixel grayscale images of digits (0-9)
  
### 2. Regression: Air Quality Assessment
This project employs regression techniques to assess air quality based on various environmental factors.

- **Data**: Air quality dataset with hourly averages of multiple pollutants and environmental conditions.
- **Features**: 
  1. **NMHC(GT)**: Hourly averaged overall Non-Methanic HydroCarbons concentration in µg/m³.
  2. **C6H6(GT)**: Hourly averaged Benzene concentration in µg/m³.
  3. **PT08.S2(NMHC)**: Hourly averaged sensor response to NMHC.
  4. **NOx(GT)**: Hourly averaged NOx concentration in ppb.
  5. **PT08.S3(NOx)**: Hourly averaged sensor response for NOx.
  6. **NO2(GT)**: Hourly averaged NO2 concentration in µg/m³.
  7. **PT08.S4(NO2)**: Hourly averaged sensor response for NO2.
  8. **PT08.S5(O3)**: Hourly averaged sensor response for O3.
  9. **T**: Temperature in °C.
  10. **RH**: Relative Humidity.
  11. **AH**: Absolute Humidity.
  12. **PT08.S1(CO)**: TARGET VARIABLE - Hourly averaged sensor response for CO.

### 3. SVM: Prediction of University Admissions
This project employs Support Vector Machines (SVM) to predict the likelihood of admission into a US university based on applicant metrics.

- **Data**: University admission dataset.
- **Features**: 
  1. **CGPA**: Cumulative Grade Point Average.
  2. **SOP**: Statement of Purpose.
  3. **GRE Score**: Graduate Record Examination score.
  4. **LOR**: Letter of Recommendation.

### 4. Trees: Loan Approval Prediction
This project uses decision tree algorithms to predict whether a loan will be granted based on various applicant characteristics.

- **Data**: Loan approval dataset.
- **Features**: 
  1. **Loan_ID**: Unique identifier for the loan.
  2. **Gender**: Gender of the applicant.
  3. **Married**: Marital status.
  4. **Dependents**: Number of dependents.
  5. **Education**: Education level of the applicant.
  6. **Self_Employed**: Self-employment status.
  7. **ApplicantIncome**: Income of the applicant.
  8. **CoapplicantIncome**: Income of the co-applicant.
  9. **LoanAmount**: Total amount of the loan requested.
  10. **Loan_Amount_Term**: Duration for loan repayment.
  11. **Credit_History**: Credit history status.
  12. **Property_Area**: Location of the property.
  13. **Loan_Status**: Target variable indicating whether the loan was granted.

## Features
- **Diverse Algorithms**: Utilizes CNN, regression models, SVM, and decision trees for different tasks.
- **Real-World Applications**: Addresses practical problems such as image recognition, environmental monitoring, university admissions, and financial decision-making.
- **Data Analysis**: Each project includes thorough data analysis and feature engineering to enhance model performance.

## Uses
- **Educational Resource**: Useful for students and practitioners to understand various machine learning techniques and their applications.
- **Predictive Analytics**: Provides insights into trends and patterns for decision-making in various sectors.
- **Model Development**: Serves as a foundation for further development and exploration of machine learning models.

## Tech Stack
- **Programming Language**: Python
- **Machine Learning Libraries**: 
  - PyTorch for CNN
  - Implemented Regression and Trees from scratch and Scikit-learn for other utlities
- **Data Handling**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn

Explore the repository for detailed project implementations, source code, and documentation!
