🏥 Patient Length of Stay (LOS) Prediction – Machine Learning Project

📌 Project Overview
The objective of this project is to predict the Length of Stay (LOS) of patients in a hospital using machine learning techniques. Accurate LOS prediction helps hospitals improve resource management, bed availability, staff planning, and overall patient care.
This project explores multiple machine learning models, evaluates their performance, and recommends the most suitable model for production deployment.


📂 Project Structure
├── Healthcare_patient_stay(LOS).ipynb
├── README.md


Healthcare_patient_stay(LOS).ipynb – Complete Jupyter Notebook containing:

Data preprocessing

Exploratory Data Analysis (EDA)

Model training & evaluation

Final conclusions and recommendations


📊 Dataset Description

The dataset contains hospital patient records with features such as:

case_id	
Hospital_code	
Hospital_type_code	
City_Code_Hospital	
Hospital_region_code	
Available_Extra_Rooms_in_Hospital	
Department	
Ward_Type	
Ward_Facility_Code	
Bed_Grade	
patientid	
City_Code_Patient	
Type_of_Admission	
Severity_of_Illness	
Visitors_with_Patient	
Age	
Admission_Deposit	
Target variable: Length of Stay (LOS)


⚙️ Technologies & Libraries Used

Python

NumPy

Pandas

Matplotlib / Seaborn

Scikit-learn

XGBoost


🧠 Machine Learning Models Implemented

The following models were trained and evaluated:

Logistic Regression

Decision Tree Classifier

K-Nearest Neighbors (KNN)

Random Forest Classifier

XGBoost Classifier


📈 Model Evaluation Metrics

Models were evaluated using:

Accuracy Score

Confusion Matrix

Precision, Recall, and F1-score (Classification Report)


⚠️ Challenges Faced & Solutions
1. Class Imbalance

Problem: Uneven distribution of LOS classes

Solution: Used class_weight='balanced' to ensure fair learning

2. Presence of Outliers

Problem: Outliers in numerical features like visitors count and admission deposit

Solution: Used ensemble models (Random Forest, XGBoost) which are robust to outliers

3. Feature Scaling

Problem: KNN performance affected by feature magnitude

Solution: Applied StandardScaler

4. Model Overfitting

Problem: Decision Tree showed overfitting

Solution: Preferred ensemble techniques


🏆 Best Model Selection

After comparing all models:

✅ XGBoost Classifier achieved the best overall performance

Highest accuracy

Better handling of class imbalance

Strong generalization

Suitable for real-world deployment



✅ Final Conclusion

This project demonstrates how machine learning can be effectively used to predict patient length of stay in hospitals. Among all evaluated models, XGBoost proved to be the most reliable and accurate, making it the recommended choice for production use. The results can assist hospitals in optimizing operations and improving patient care.

🚀 How to Run the Project

Clone or download the repository

Open the Jupyter Notebook:

Healthcare_patient_stay(LOS).ipynb

Run all cells sequentially


👨‍💻 Kalaiselvi Kanagaraj -AI Solution Mentor 

Machine Learning Project – Patient Length of Stay Prediction

Feedback Expected 
