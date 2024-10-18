# Citrone Performance Project

**[Check the Eligibilty app here!](https://deployment-qrtkyxuwpev8jj77m2cbuv.streamlit.app/)**

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Conclusion](#conclusion)

## Project Overview
The Citrone Performance Project is focused on building a machine learning model to predict student progression on the Citrone learning management platform. The model predicts whether a student will graduate from the beginner class to the intermediate class based on various performance indicators, helping educators and administrators identify students who may need additional support or are ready to advance. The project involves data preprocessing, feature selection, model building, and performance evaluation to ensure accurate predictions and actionable insights.

## Dataset
The dataset comprises several fields relevant to the student’s performance and eligibility:
- **S/N**: Serial number for identification.
- **Name**: Student's name.
- **Email**: Contact email of the student.
- **Address**: Address at the time of application.
- **Lesson Summary**: Dates related to lessons.
- **Quiz Summary**: Student’s quiz scores.
- **Assignment Summary**: Performance on assignments.
- **Grade Point Average**: Average grade over all assignments and quizzes.
- **Intermediate Class Eligibility**: Target variable indicating whether the student is eligible to move to the intermediate class.

Due to a limited initial dataset, additional data was generated using [Mockaroo](https://www.mockaroo.com/), which provides realistic dummy data to enhance the dataset. This allows the model to better generalize to new data.

## Project Structure
- **Data Preprocessing**: The dataset was cleaned, and unnecessary columns were removed to streamline the analysis. Missing values were handled, and features were engineered where necessary.
- **Exploratory Data Analysis**: Several visualizations, including histograms, correlation plots, and scatter plots, were generated to understand the relationships between different variables. These visualizations also helped in feature selection for the machine learning model.
- **Model Training**: 
  - The dataset was split into a training set (80%) and a test set (20%).
  - Various machine learning models were trained and evaluated for performance. Models were fine-tuned to optimize for accuracy.
- **Model Evaluation**:
  - Model performance was measured on the test dataset, achieving over 90% accuracy.
  - Evaluation metrics such as accuracy, precision, recall, and F1 score were calculated to assess the model’s performance comprehensively.
- **Deployment**: The final model was deployed, allowing for real-time predictions on new data.

**[Check the Eligibilty app here!](https://deployment-qrtkyxuwpev8jj77m2cbuv.streamlit.app/)**

 ## Conclusion 
The Citrone Performance Project demonstrates a complete data science pipeline, from data collection and preprocessing to model training, evaluation, and deployment. By leveraging a well-prepared dataset and machine learning, the model provides accurate predictions on student eligibility for class progression, supporting informed decisions within the Citrone platform.



