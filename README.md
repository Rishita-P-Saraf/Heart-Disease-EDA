# Heart Disease Dataset - Exploratory Data Analysis (EDA)

This project focuses on performing Exploratory Data Analysis (EDA) on a heart disease dataset.

## Dataset
The heart disease dataset used in this analysis contains various features such as age, sex, blood pressure, cholesterol levels, and more. Each record indicates whether or not the individual has heart disease.

### Features

- Age: age of the patient [years]
- Sex: sex of the patient [M: Male, F: Female]
- ChestPainType: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
- RestingBP: resting blood pressure [mm Hg]
- Cholesterol: serum cholesterol [mm/dl]
- FastingBS: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
- RestingECG: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]
- MaxHR: maximum heart rate achieved [Numeric value between 60 and 202]
- ExerciseAngina: exercise-induced angina [Y: Yes, N: No]
- Oldpeak: oldpeak = ST [Numeric value measured in depression]
- ST_Slope: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]
- HeartDisease: output class [1: heart disease, 0: Normal]

## Objectives
- Clean and preprocess the dataset.
- Perform univariate, bivariate, and multivariate analysis.
- Visualize relationships between features and the target variable.
- Identify key features that may influence heart disease.

## Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Key Insights
1. **Age and Heart Disease**: Higher prevalence of heart disease in older individuals.
2. **Chest Pain Type**: Certain chest pain types are strongly associated with heart disease.
3. **Cholesterol and Blood Pressure**: High cholesterol and blood pressure levels contribute significantly.
4. **Exercise Induced Angina**: Individuals experiencing angina during exercise are at higher risk.

## Visualizations
- Correlation heatmap to understand feature relationships.
- Histogram and boxplots for numerical feature distribution.
- Scatter plots to observe feature interactions.
- Pie charts for categorical features.
- Pair plots for multivariate analysis.

## Future Work
- Perform predictive modeling using machine learning algorithms.
- Optimize feature selection and engineering.
- Compare models to find the best-performing classifier.


Contributions are welcome! Please open an issue or submit a pull request.


This project is licensed under the MIT License.
