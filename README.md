# Diamond-Price-Prediction
## “I designed the project in multiple modular components — similar to a production-ready ML system.”

### 1. Project Setup & GitHub Repository – Set up version control and a clean folder structure following MLOps practices.

### 2. Advanced Project Structure – Divided code into components: data ingestion, transformation, model training, and prediction, so each stage was reusable and independent.

### 3. Logging & Exception Handling – Implemented centralized logging to track model execution, and custom exceptions for debugging issues easily.

### 4. EDA & Feature Engineering – Analyzed the dataset, handled missing values, encoded categorical variables, and scaled numerical features.

### 5. Data Ingestion – Automated reading of raw CSV data and storing it in a defined format for processing.

### 6. Data Transformation – Handled data preprocessing steps like outlier removal, feature scaling, encoding, and train-test split.

### 7. Model Trainer – Tested multiple regression models (e.g., Linear, Ridge, Random Forest, XGBoost), compared RMSE/MAE, and selected the best one.

### 8. Prediction Pipeline – Built a reusable pipeline that accepts new data (diamond attributes) and returns predicted price using the trained model.
