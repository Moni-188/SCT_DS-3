📌 Objective of Task 3 is to build and evaluate a Decision Tree Classification model using a real-world dataset.
The task focuses on data preprocessing, categorical encoding, model training, and performance evaluation.

📁 Dataset
Bank Marketing Dataset
The dataset contains information about bank customers and marketing campaigns.
Target variable indicates whether a customer subscribed to a term deposit.

Key features include:
Age, job, marital status
Education level
Contact type
Campaign-related attributes

🛠️ Tools & Technologies Used
Python
Jupyter Notebook
Pandas – data preprocessing
NumPy – numerical operations
Scikit-learn – model building & evaluation

🔍 Steps Performed
Imported required libraries
pandas, numpy, scikit-learn
Loaded the dataset
Read CSV file using pandas
Data Preprocessing
Separated features (X) and target variable (y)
Applied one-hot encoding using pd.get_dummies()
Handled categorical variables
Train-Test Split
Split data into training and testing sets
Model Building
Implemented Decision Tree Classifier
Set maximum tree depth to avoid overfitting
Model Evaluation
Evaluated model using accuracy score

📈 Results
The Decision Tree model achieved high accuracy, indicating effective learning from the dataset.
Proper preprocessing significantly improved model performance.
