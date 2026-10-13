Student Performance Prediction Using Machine Learning

Project Overview

This project predicts students' final mathematics grades using student-related information and Machine Learning. The aim is to understand how academic, family, and lifestyle factors may relate to students' performance.

Dataset

The project uses the Student Performance Dataset from the UCI Machine Learning Repository.

- Dataset file: "student-mat.csv"
- Number of student records: 395
- Target variable: "G3" (final mathematics grade)
- Dataset source: "UCI Student Performance Dataset" (https://archive.ics.uci.edu/dataset/320/student+performance)

Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

Machine Learning Approach

Linear Regression is used to predict final mathematics grades.

The main steps are:

1. Import the required libraries.
2. Load and explore the dataset.
3. Prepare the input features and target variable.
4. Convert categorical features into numerical form.
5. Split the dataset into training and testing sets using an 80:20 ratio.
6. Train the Linear Regression model.
7. Predict grades for the test data.
8. Evaluate the model using MAE, RMSE, and R² score.
9. Visualize actual and predicted grades.

Results

The model's performance is evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

The observed test results are reported in the Jupyter notebook.

Repository Contents

- "student_performance.ipynb" — notebook containing the code, analysis, visualizations, and results.
- "student-mat.csv" — dataset used for the project.

How to Run

1. Download or clone this repository.
2. Open "student_performance.ipynb" in Google Colab or Jupyter Notebook.
3. Upload "student-mat.csv" if required, or update the dataset path.
4. Run the notebook cells in order.

Conclusion

This project demonstrates a basic Machine Learning workflow for predicting student mathematics grades. It includes data preprocessing, model training, prediction, evaluation, and visualization.
