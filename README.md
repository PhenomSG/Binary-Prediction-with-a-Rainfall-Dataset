# Binary Prediction with a Rainfall Dataset

![Kaggle Competition](https://img.shields.io/badge/Kaggle-Competition-blue.svg)
![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Enabled-green.svg)

## 🏆 Kaggle Competition Details
This repository contains my solution for the Kaggle competition **Playground Series - Season 5, Episode 3**: [Binary Prediction with a Rainfall Dataset](https://www.kaggle.com/competitions/playground-series-s5e3).

- **Current Rank**: 100 (as of the latest update)
- **Objective**: Predict the probability of daily rainfall using historical weather data.
- **Dataset**: Features include temperature, humidity, pressure, wind speed, and other meteorological parameters.

## 📂 Repository Structure
```
📦 Binary-Prediction-with-a-Rainfall-Dataset
├── notebooks/             # Jupyter Notebooks for data exploration and modeling
├── src/                   # Scripts for data preprocessing, model training, and evaluation
├── data/                  # Sample datasets (if applicable)
├── models/                # Saved models and predictions
├── results/               # Performance metrics and leaderboard submissions
├── README.md              # Project documentation
```

## 📊 Approach & Methodology
1. **Data Preprocessing**
   - Handling missing values
   - Feature engineering and selection
   - Normalization and encoding

2. **Model Selection & Training**
   - Tried various ML models: Logistic Regression, Decision Trees, Random Forest, XGBoost, and Neural Networks
   - Optimized hyperparameters using GridSearchCV and Optuna

3. **Evaluation & Submission**
   - Measured performance using **log loss and AUC-ROC**
   - Generated predictions and submitted results to Kaggle

## 🚀 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/PhenomSG/Binary-Prediction-with-a-Rainfall-Dataset.git
   cd Binary-Prediction-with-a-Rainfall-Dataset
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run Jupyter Notebook for data exploration:
   ```bash
   jupyter notebook
   ```
4. Train the model using `src/train_model.py`:
   ```bash
   python src/train_model.py
   ```
5. Generate predictions and evaluate results.

## 📈 Results & Performance
- **Baseline Model**: Logistic Regression - Log Loss: *X.XX*
- **Best Model (so far)**: *Model Name* - Log Loss: *X.XX*, AUC-ROC: *X.XX*

## 🔥 Future Improvements
- Implement ensemble learning techniques (Stacking, Blending)
- Explore deep learning models (LSTMs, CNNs for tabular data)
- Optimize hyperparameters further


Feel free to contribute, suggest improvements, or reach out for discussions!

