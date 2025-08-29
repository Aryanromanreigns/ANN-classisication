# ANN Classification 🚀

This project implements **Artificial Neural Networks (ANNs)** for classification and regression tasks such as **Customer Churn Prediction** and **Salary Regression**.  
It includes Jupyter notebooks for experiments, hyperparameter tuning, and model inference using saved models and preprocessing objects.

---

## 📂 Project Structure

| File | Description |
|------|-------------|
| `app.py` | Script for running predictions on new data |
| `experiments.ipynb` | Notebook containing ANN training experiments |
| `hyperparametertuningann.ipynb` | Notebook for hyperparameter tuning |
| `prediction.ipynb` | Notebook showing how to load the trained model and predict |
| `salaryregression.ipynb` | ANN applied to salary regression |
| `Churn_Modelling.csv` | Dataset used for churn classification |
| `model.h5` | Saved trained ANN model |
| `label_encoder_gender.pkl` | Saved LabelEncoder for gender |
| `onehot_encoder_geo.pkl` | Saved OneHotEncoder for geography |
| `scaler.pkl` | Saved feature scaler |
| `requirements.txt` | Python dependencies |

---

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Aryanromanreigns/ANN-classisication.git
   cd ANN-classisication
Create a virtual environment:

bash
Copy code
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
Install dependencies:

bash
Copy code
pip install -r requirements.txt
🚀 Usage
1. Train the Model
Open experiments.ipynb in Jupyter Notebook to explore training steps and results.

2. Hyperparameter Tuning
Run hyperparametertuningann.ipynb for experimenting with different ANN configurations.

3. Make Predictions
Option 1: Run prediction.ipynb to see predictions using saved model & encoders.

Option 2: Run:

bash
Copy code
python app.py
4. Regression Example
Check salaryregression.ipynb for ANN-based regression on salary data.

📊 Example Prediction Flow
Input data is preprocessed using:

label_encoder_gender.pkl

onehot_encoder_geo.pkl

scaler.pkl

Model (model.h5) loads weights and predicts output.

🛠 Requirements
Install all dependencies with:

bash
Copy code
pip install -r requirements.txt
Main packages:

numpy

pandas

scikit-learn

tensorflow

keras

matplotlib

