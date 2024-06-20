# CardioVision-AI-TensorFlow-Cardiac-Risk-Predictor-
Welcome to the CardioVision AI project repository. This project focuses on developing a robust machine learning model using TensorFlow to predict heart disease in patients. The model analyzes critical medical parameters to achieve a predictive accuracy exceeding 84.61%. The repository includes the final report, dataset, and several Python files for different stages of the project.

The dataset used in this study comprises various medical parameters, including age, gender, chest pain type, resting blood pressure, cholesterol levels, fasting blood sugar, resting electrocardiographic results, maximum heart rate, exercise-induced angina, oldpeak (ST depression induced by exercise), and the slope of the peak exercise ST segment. These features are critical indicators of cardiovascular health and are used to train and evaluate the predictive model.

The Exploratory Data Analysis (EDA) process involves summarizing the dataset's main features using visual methods to identify trends, patterns, and potential anomalies. The eda.py file contains the code for generating histograms and bar plots to visualize the distribution of key variables.

Various model structures were rigorously tested to determine the most effective approach. These structures ranged from simple feedforward networks to more complex architectures. Parameter optimization focused on refining regularization and learning rates to enhance model performance. The implementation details are provided in the Parameter_Optimization_HeartDisease Jupyter Notebook file.

The final model incorporates the best-performing neural network structure and optimized parameters. Detailed analysis and results can be found in the Final_Model_HeartDisease Jupyter Notebook file.
