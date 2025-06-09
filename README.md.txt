# 📈 Customer Churn Prediction

This project aims to predict customer churn using traditional machine learning models and a neural network. It also uses SHAP values for explainability and visualizes model performance.

## 🛠️ Tech Stack
- Python, Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn, XGBoost, PyTorch
- SHAP for model interpretability

## 📁 Project Structure
- `eda.ipynb`: Data preprocessing and exploration
- `traditional_models.ipynb`: Logistic Regression, Random Forest, XGBoost
- `nnmodel.ipynb`: PyTorch Neural Network
- `shap_explainability.ipynb`: SHAP-based model interpretation
- `model_comparison.ipynb`: Metric and visual comparison of models
- `/data/`: Saved models, predictions, and SHAP outputs
- `/plots/`: All graphs and figures used in the project

## 📊 Key Results

| Model              | Accuracy | Precision | Recall | F1 Score |
|-------------------|----------|-----------|--------|----------|
| Logistic Regression | 0.777   | 0.565     | 0.695  | 0.623    |
| Random Forest       | 0.729   | 0.493     | 0.738  | 0.591    |
| XGBoost             | 0.765   | 0.549     | 0.647  | 0.594    |
| Neural Network      | 0.778   | 0.567     | 0.693  | 0.623    |

## 💡 Takeaways
- Neural Network and Logistic Regression had the highest overall F1 scores.
- Random Forest had the strongest recall, making it suitable if false negatives are costly.
- SHAP identified key churn drivers: tenure, contract type, and monthly charges.

## 📌 Future Work
- Hyperparameter tuning for all models
- Deploy as a Streamlit or Flask web app
- Add cost-sensitive learning for business relevance

## 📬 Contact
Author: [Your Name]  
Email: [your.email@example.com]  
LinkedIn: [Your LinkedIn]  
