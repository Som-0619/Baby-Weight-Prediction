# Baby-Weight-Prediction

This project predicts low birthweight trends using historical data. It uses TensorFlow, Scikit-Learn, and Seaborn to train a neural network model and visualize results.

📦 Baby-Weight-Prediction
│── 📄 README.md
│── 📄 baby-weight-prediction.ipynb  # Google Colab Notebook
│── 📂 dataset
│   └── selected-trend-table.csv    # Dataset


📥 Dataset
Source: Contains historical low birthweight rates from various states and ethnic groups
Target Variable (2008-2010): Birthweight trend in this period
Features: Previous birthweight trends, state, race

📊 Model Overview
Architecture:
Dense(64) → ReLU
Dense(32) → ReLU
Dense(1) → Linear (Output)
Loss Function: Mean Squared Error (MSE)
Optimizer: Adam
Epochs: 50


📜 Results
The model helps predict low birthweight rates based on past trends
The validation loss decreases with training, indicating improvement

📌 Future Improvements
Use more features (e.g., socioeconomic factors)
Implement Hyperparameter Tuning for better accuracy
Try different ML models like XGBoost or Random Forest

🛠️ Tech Stack
Python 3.8+
TensorFlow & Keras
Scikit-Learn
Seaborn & Matplotlib
