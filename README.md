Predicting Employee Attrition 🧑‍💼📉

This project predicts whether an employee is likely to leave the company using machine learning techniques. It utilizes a Random Forest classifier on HR-related data to assess attrition risk.


🎯 Aim:

The primary aim of this project is to develop a machine learning model that accurately predicts whether an employee is likely to leave the organization (attrition). This helps HR departments proactively identify at-risk employees and take preventive measures to improve retention.


📁 Dataset:


Source:[employee_data.csv](https://github.com/user-attachments/files/20499131/employee_data.csv)


🔧 Technologies Used:


Python


Pandas


NumPy


Matplotlib / Seaborn (for visualization)


Scikit-learn


Google Colab


Joblib (for model saving)



📊 Exploratory Data Analysis:

Feature correlation heatmap created using Seaborn


Dataset encoding via get_dummies for categorical variables



🧠 Model Training:

Model: Random Forest Classifier


Data split into 80% training and 20% testing


Categorical data encoded


Features scaled using StandardScaler (if needed)


Target: Attrition_Yes column



📈 Model Evaluation:

Accuracy Score


Classification Report


Confusion Matrix Heatmap



🗃️ Model Saving:

Trained model is saved as employee_attrition_model.pkl using Joblib.


🚀 Usage:

Upload employee_data.csv in the Colab environment.


Run the notebook/script.


View metrics and visualizations.


Use the saved model (.pkl file) for further predictions.


📜 License:

This project is open-source and available under the MIT License.


🙋‍♂️ Author:

Haridasula Abhinav
