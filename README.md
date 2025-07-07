🌱 GHG Emissions Prediction using Machine Learning
This project predicts Supply Chain Emission Factors with Margins using machine learning models. The goal is to help estimate greenhouse gas (GHG) emissions based on various data quality (DQ) metrics and supply chain factors.

📌 Project Objectives
Predict GHG emission factors using historical industry and commodity data.

Apply data preprocessing techniques to clean and scale inputs.

Train and evaluate multiple regression models.

Build a user-friendly Streamlit web application for real-time predictions.

🧠 Models Used
Linear Regression (Final selected model)

Random Forest Regressor (Tested and compared)

Feature scaling using StandardScaler

🧪 Dataset
Source: U.S. Industry & Commodity GHG dataset (2010–2016)

Features: Substance, Source, Supply Chain Emission Factors, DQ metrics

Target: Supply Chain Emission Factors with Margins

🔧 Setup Instructions
1. Clone this Repository
bash
Copy
Edit
git clone https://github.com/Sowmyasribairisetti/GHG_Emissions_Prediction_AICTE.git
cd GHG_Emissions_Prediction_AICTE
2. Install Dependencies

Required Packages:

streamlit

pandas

numpy

scikit-learn

joblib

3. Run the Streamlit App
streamlit run app.py
🚀 How It Works
User inputs DQ metrics, source type, and emission values via the Streamlit app.

Inputs are preprocessed using preprocessor.py.

Scaled input is passed to the trained ML model.

The app displays the predicted emission factor with margin.

🔧 Improvisations Done
Cleaned dataset and dropped unused columns

Added preprocessing script to automate input formatting

Trained and compared multiple regression models

Selected best model based on RMSE and R² score

Built an interactive Streamlit UI

Integrated model and scaler for real-time prediction

Hosted project code and assets on GitHub

📸 App Preview
A user-friendly web app for entering values and predicting GHG emissions in real time.

<img src=https://github.com/Sowmyasribairisetti/GHG_Emissions_Prediction_AICTE/issues/1#issue-3208612183 width="700"/>

📎 Links
🔗 Project GitHub: GHG Emissions Prediction

📊 Dataset: Available upon request or download from U.S. GHG inventory sources

🙋‍♀️ Author
Sowmya Sri Bairisetti
NPTEL Certified in Machine Learning
