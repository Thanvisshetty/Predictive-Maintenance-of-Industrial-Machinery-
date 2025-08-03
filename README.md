# Predictive-Maintenance-of-Industrial-Machinery-

 Problem Statement
In industrial manufacturing, machinery failure can lead to significant production downtime, cost overruns, and safety concerns. A key challenge is to predict machinery failures before they occur to schedule timely maintenance. The goal is to build a system that accurately identifies failure types in advance using operational data from machines.

✅ Proposed Solution
The proposed system aims to predict the Failure Type of industrial machinery using historical sensor data. This includes developing a predictive model using supervised machine learning techniques.

Key steps:

Data Collection: Use sensor data including temperature, rotational speed, torque, and tool wear.

Data Preprocessing: Handle missing values, normalize input features, and encode categorical variables.

Model Building: Train and evaluate multiple machine learning pipelines.

Optimization: Use cross-validation and hyperparameter tuning to optimize model accuracy.

Deployment: Deploy the best-performing model via IBM Watsonx for real-time prediction.



🧠 System Development Approach
Platform Used: IBM Watsonx.ai Studio

Data Split: 90% training and 10% holdout data

Approach: AutoAI pipeline generation and evaluation

Model Selection: Snap Random Forest Classifier & Snap Decision Tree Classifier



⚙️ Algorithm & Deployment
Algorithm Selection:

Random Forest & Decision Tree Classifiers

Best model: Batched Tree Ensemble Classifier with accuracy: 0.995

Training Process:

IBM AutoAI generated 9 pipelines

Hyperparameter optimization and feature engineering applied

Deployment:

Best pipeline (Pipeline 5) deployed

Real-time prediction enabled via Watsonx's API interface



📊 Result
Model used: Pipeline 5 – Batched Tree Ensemble Classifier

Accuracy: 99.5% (Cross-validation)

Output: Multiclass classification — Predicts "Failure Type" with 100% confidence




🧾 Conclusion
The project successfully implemented a machine learning solution to predict machinery failures with high accuracy using Watsonx.ai. The system helps reduce downtime and improve production efficiency by enabling preventive maintenance actions.


🚀 Future Scope
Integrate more real-time IoT sensor data

Apply deep learning for better fault classification

Extend the system to multiple factory environments

Visualize predictions on dashboards for easier decision-making


📚 References
IBM Watsonx.ai documentation

Research papers on predictive maintenance and AutoML

Tutorials on Random Forest and Decision Tree classifiers
