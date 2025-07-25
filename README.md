# Heart Disease Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0.2-orange)
![Pandas](https://img.shields.io/badge/Pandas-1.3.0-red)
![Streamlit](https://img.shields.io/badge/Streamlit-1.14.0-green)

A machine learning model to predict the likelihood of heart disease based on clinical parameters. Achieved **62% accuracy** with scope for improvement through feature engineering and advanced algorithms.

## 🚀 Features
- **Data Preprocessing**: Handles missing values, outlier detection, and feature scaling
- **Multiple Algorithms**: Tested Logistic Regression, Random Forest, and SVM
- **Web Interface**: Simple Streamlit app for real-time predictions (optional)
- **Key Insights**: Identified most influential features like cholesterol and blood pressure

## 📂 Project Structure
heart-disease-prediction/
├── data/ # Dataset folder
│ └── heart.csv # Sample dataset (Cleveland dataset)
├── notebooks/ # Jupyter notebooks
│ ├── EDA.ipynb # Exploratory Data Analysis
│ └── Model_Training.ipynb # Model development
├── src/ # Source code
│ ├── preprocess.py # Data cleaning functions
│ ├── train_model.py # Model training script
│ └── app.py # Streamlit deployment (optional)
├── models/ # Saved models
│ └── random_forest.pkl # Trained model
├── requirements.txt # Python dependencies
└── README.md # This file


## 🛠️ Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/heart-disease-prediction.git
   cd heart-disease-prediction
   pip install -r requirements.txt
🧮 Usage
For training:
python
python src/train_model.py
For web app (if deployed):
bash
streamlit run src/app.py
📊 Results
Model	Accuracy	Precision	Recall
Logistic Regression	61%	0.60	0.62
Random Forest	62%	0.61	0.63
SVM	59%	0.58	0.60

@ Key Findings:

Maximum heart rate (thalach) was most predictive feature
Model performance limited by small dataset size (n=303)

🔮 Future Improvements

Experiment with XGBoost/Neural Networks
Integrate more clinical features (genetic markers)
Develop mobile-friendly interface



