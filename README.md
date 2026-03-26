Support Vector Machine (SVM) on Wine Quality Dataset

Overview
This project presents the implementation of a Support Vector Machine (SVM) model to classify wine quality using a real-world dataset. The objective is to transform the original quality scores into a binary classification problem and evaluate the effectiveness of SVM with different kernel functions.
The workflow follows a standard machine learning pipeline, including data preprocessing, visualization, model training, evaluation, and performance comparison.

Dataset
The dataset used in this project is the Wine Quality dataset obtained from the UCI Machine Learning Repository. It contains physicochemical properties of wine samples along with their quality ratings.

Features
The dataset includes the following attributes:
•	Fixed acidity
•	Volatile acidity
•	Citric acid
•	Residual sugar
•	Chlorides
•	Free sulfur dioxide
•	Total sulfur dioxide
•	Density
•	pH
•	Sulphates
•	Alcohol
•	Quality (target variable)

Problem Definition
The original dataset contains quality scores ranging from 0 to 10. For this project, the problem is converted into binary classification:
•	Good Wine: quality greater than or equal to 6
•	Bad Wine: quality less than 6
This transformation simplifies the classification task and aligns with practical decision-making scenarios.

Methodology
Data Preprocessing
•	Loaded the dataset and handled formatting
•	Converted the target variable into binary classes
•	Split the dataset into training and testing sets
•	Applied feature scaling using standardization
Data Visualization
A scatter plot was generated using alcohol content and volatile acidity to visualize the distribution of wine samples before applying the SVM model.
Model Training
Two SVM models were trained using:
•	Linear Kernel
•	Radial Basis Function (RBF) Kernel
Hyperparameter tuning was performed to improve model performance and ensure reliable results.
Model Evaluation
The trained models were evaluated using:
•	Accuracy score
•	Confusion matrix
Kernel Comparison
A comparison was conducted between the Linear and RBF kernels to analyze their performance differences in terms of classification accuracy.

Results
•	The SVM model successfully classified wine samples into good and bad categories.
•	The RBF kernel generally achieved higher accuracy compared to the linear kernel due to its ability to handle non-linear patterns.
•	The confusion matrix demonstrated the model’s effectiveness in predicting both classes.

Key Outputs
The following outputs were generated:
1.	Distribution of wine samples in the dataset
2.	Confusion matrix of the SVM model
3.	Linear kernel accuracy (in percentage)
4.	RBF kernel accuracy (in percentage)
5.	Comparison of kernel performance

Tools and Technologies
•	Python
•	Pandas
•	NumPy
•	Matplotlib
•	Seaborn
•	Scikit-learn

How to Run
1.	Open Google Colab or a Python environment
2.	Upload the dataset file (data.csv)
3.	Run the provided Python script
4.	View the generated plots and evaluation metrics

Conclusion
This project demonstrates that Support Vector Machines are effective for classification tasks, particularly when dealing with structured datasets. The use of kernel functions enhances the model’s flexibility, allowing it to capture both linear and non-linear relationships.
The results confirm that SVM provides strong classification performance and remains a reliable choice for supervised learning problems.

Author
MD SAZZAD HOSEN KHAN


