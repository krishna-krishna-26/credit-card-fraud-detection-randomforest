# Credit Card Fraud Detection

## 📌 Project Overview
This project aims to detect fraudulent transactions using machine learning techniques. It processes a dataset containing transaction details and applies classification models to identify fraud cases.

## 🛠️ Technologies Used
- Python (Can be used with Notepad, VS Code, or Jupyter Notebook)
- Python
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn, Imbalanced-learn
- XGBoost, LightGBM
- Joblib (for model saving)

## 🚀 How to Run the Project
### 1️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```
OR manually install:
```sh
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn xgboost lightgbm joblib
```

### 2️⃣ Run the Notebook
Open and execute the Jupyter Notebook:
```sh
jupyter notebook "krishna notebook.ipynb"
```

### 3️⃣ Run Without Jupyter (Using Script)
For users who prefer running the model without Jupyter:
```sh
python main.py
```
This script will load the trained model and make predictions.

## 📊 Steps in the Notebook
1. **Data Loading:** Reads train and test datasets.
2. **Data Preprocessing:** Cleans and encodes data.
3. **Feature Engineering:** Drops unnecessary columns, balances dataset.
4. **Model Training:** Trains Logistic Regression and Random Forest.
5. **Evaluation:** Generates accuracy, classification reports, and predictions.
6. **Model Saving/Loading:** Saves model using `joblib`.

## 📌 Evaluation Metrics Used
- **Accuracy Score:** Measures overall model correctness.
- **Classification Report:** Includes precision, recall, and F1-score.
- **ROC Curve:** Plots True Positive Rate vs. False Positive Rate to evaluate model performance.
- **AUC-ROC Score:** Measures area under the ROC curve, indicating how well the model distinguishes fraud cases.
- **Confusion Matrix:** Displays the number of true/false positives and negatives for detailed analysis.
- **Precision-Recall Curve:** Visualizes trade-off between precision and recall.

## 📈 Model Performance
- **Logistic Regression Accuracy:** _64.00%_
- **Random Forest Accuracy:** **99.59%**
- **AUC-ROC Score:** _0.9985_
- **Confusion Matrix & Curve:** _Visualized in the notebook._
- **Precision-Recall Curve:** _Visualized in the notebook._

### 🔹 Random Forest Classification Report
```
               precision    recall  f1-score   support

           0       1.00      0.99      1.00    257186
           1       0.99      1.00      1.00    258482

    accuracy                           1.00    515668
   macro avg       1.00      1.00      1.00    515668
weighted avg       1.00      1.00      1.00    515668
```

### 🔹 Confusion Matrix
```
               Predicted No Fraud    Predicted Fraud
Actual No Fraud       255553                1633
Actual Fraud            476                258006
```

## 💡 Possible Improvements
- Hyperparameter tuning (`GridSearchCV`)
- Feature selection for better model performance
- Comparison table for models

## 📂 Repository Structure
```
📦 Project Directory
 ┣ 📜 krishna notebook.ipynb  # Main Jupyter Notebook
 ┣ 📜 main.py                 # Script to run without Jupyter
 ┣ 📜 README.md                # Project Documentation
 ┣ 📜 requirements.txt         # Required Python packages
 ┗ 📂 Datasets                 # Folder for train/test CSVs
```

## 📢 Contribution
Feel free to fork the repository and suggest improvements!

## 📂 Dataset & Model Link
All datasets and trained models are available at: [Google Drive](https://drive.google.com/drive/folders/1Q8IXsLKl35zeHypLP2PuP7CK1s2W7BFo?usp=sharing)

## 📌 GitHub Repository
The task is hosted on GitHub: [GitHub Repository](https://github.com/krishna-krishna-26/credit-card-fraud-detection-randomforest)

### 📥 Clone the Repository
To download this project from GitHub, follow these steps:

1️⃣ **Using Git (Recommended)**
```sh
git clone https://github.com/krishna-krishna-26/credit-card-fraud-detection-randomforest.git
cd credit-card-fraud-detection-randomforest
```

2️⃣ **Download as ZIP**
- Go to the [GitHub Repository](https://github.com/krishna-krishna-26/credit-card-fraud-detection-randomforest)
- Click on the **"Code"** button
- Select **"Download ZIP"**
- Extract the ZIP file and navigate to the folder

## 📜 GitHub Repository Requirements:
- The task should have its own dedicated GitHub repository.
- Include a README file describing:
  - Task objectives
  - Steps to run your project
- Ensure clean, well-structured, and well-commented code.

## 📊 Evaluation Criteria:
- **Functionality:** How well the task is implemented and works.
- **Code Quality:** Structure, readability, and efficiency.
- **Innovation & Creativity:** Unique features or optimizations.
- **Documentation:** Clarity in explaining the implementation.

