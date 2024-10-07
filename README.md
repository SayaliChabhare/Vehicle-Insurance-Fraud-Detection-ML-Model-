# Vehicle-Insurance-Fraud-Detection-ML-Model-
This project focuses on detecting fraudulent claims in vehicle insurance data using advanced machine learning techniques.The dataset comprises 15,420 records, of which only 6% (923 records) are classified as fraudulent, indicating a significant class imbalance.To ensure the dataset was ready for modeling, I performed data preprocessing,which includes data clening,duplicate removal,renaming columns,data type conversion,removing unwanted columns.I explored six different machine learning models to find the best-performing model both before and after addressing the class imbalance issue and outlier tratment.After addressing the class imbalance, I employed Recursive Feature Elimination (RFE) to select the most relevant features, improving model efficiency. Following feature selection, I applied XGBoost, a powerful gradient-boosting algorithm, to develop the model. To ensure the model's generalizability and avoid overfitting, I utilized Stratified K-Fold Cross-Validation, which maintains the original class distribution across training and validation sets. This technique provided a more reliable estimate of the model's performance on unseen data.The final model achieved an impressive accuracy of 92% indicating strong predictive performance across different data split
