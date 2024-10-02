# Heart Disease Prediction using Machine Learning

## Project Overview
This project focuses on predicting the likelihood of heart disease using machine learning algorithms. It was created as part of a **Hackathon** organized by *Data Scientists Network* and *Microsoft*. The goal is to build a predictive model that can assist healthcare professionals in identifying patients who are at risk of developing heart disease. 

The project leverages clinical data, applying various machine learning techniques to analyze key health metrics such as age, cholesterol levels, blood pressure, and more.

## Motivation
Heart disease is one of the leading causes of death globally, and early detection is critical for effective treatment and prevention. Machine learning can aid in making more accurate predictions by analyzing patterns in patient data that may not be immediately apparent through traditional methods. This project seeks to build a solution that helps medical professionals assess heart disease risk with higher precision.

## Data Description
The dataset used in this project is obtained from the **UCI Machine Learning Repository**. It consists of 14 attributes related to heart disease. The key features include:

- **Age**: The age of the patient.
- **Sex**: The gender of the patient.
- **Chest Pain Type**: Various types of chest pain experienced.
- **Resting Blood Pressure**: Blood pressure measured during rest.
- **Cholesterol**: Serum cholesterol level.
- **Fasting Blood Sugar**: Blood sugar levels post fasting.
- **Resting ECG**: Results of resting electrocardiography.
- **Maximum Heart Rate Achieved**: Maximum heart rate during testing.
- **Exercise Induced Angina**: Whether the patient experienced angina post exercise.
- **Oldpeak**: Depression related to exercise.
- **Slope**: The slope of the peak exercise ST segment.
- **Number of Major Vessels**: Number of vessels colored by fluoroscopy.
- **Thal**: Thalassemia.

The target variable is a binary classification that indicates whether the patient has heart disease (1) or not (0).

## Tools and Technologies
The following tools and libraries were used in this project:

- **Python**: Programming language used to build the machine learning pipeline.
- **Pandas**: For data manipulation and cleaning.
- **Scikit-learn**: For building machine learning models.
- **Matplotlib** and **Seaborn**: For data visualization.
- **Jupyter Notebook**: Development environment for coding and visualization.

## Methodology
The approach for this project follows these key steps:

1. **Data Preprocessing**:
    - Data cleaning to handle missing values.
    - Feature scaling to standardize the dataset.
    - Feature selection to identify the most relevant predictors.

2. **Exploratory Data Analysis (EDA)**:
    - Statistical analysis of each feature to identify correlations.
    - Visualization of distributions and relationships in the dataset.

3. **Model Selection**:
    - Tested multiple models including Logistic Regression, Decision Trees, Random Forest, and XGBoost.
    - Model hyperparameter tuning using techniques like GridSearchCV.
    - Cross-validation to assess model performance.

4. **Evaluation**:
    - Models were evaluated using accuracy, precision, recall, and F1-score.
    - Confusion matrix and ROC curves were plotted to analyze the prediction results.

## Results
The best performing model was **LightGBM** 

The model can be further improved with additional data and more advanced techniques.

## Recommendations
Based on the results, the following recommendations were made to improve the effectiveness of this heart disease prediction system:
- Integrating the model into a real-time clinical setting to assist doctors during patient consultations.
- Continuously training the model with updated data to ensure it remains accurate and relevant.
- Incorporating other health metrics like lifestyle habits and family medical history to make the model more robust.

## Conclusion
This project successfully built a machine learning model to predict heart disease using key health metrics. It demonstrated the potential of machine learning in assisting healthcare professionals with early diagnosis and improving patient outcomes.

## How to Run the Project
1. Clone this repository:
    ```
    git clone https://github.com/YourUsername/heart-disease-prediction.git
    ```
2. Install the necessary dependencies:
    ```
    pip install -r requirements.txt
    ```
3. Run the Jupyter Notebook to explore the code and results.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any inquiries, feel free to reach me at:  
**Odelola Solomon Oluwatobiloba**  
Email: [odelolasolomon5@gmail.com](mailto:odelolasolomon5@gmail.com)
