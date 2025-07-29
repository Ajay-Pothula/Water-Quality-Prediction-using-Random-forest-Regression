# 💧 Water Quality Index (WQI) Prediction using Machine Learning

This project predicts the **Water Quality Index (WQI)** and classifies water contamination levels based on chemical parameters like **pH**, **TDS**, **Electrical Conductivity (EC)**, **Nitrate (NO₃)**, and **Sulfate (SO₄)** using a **Random Forest Regression** model. It includes a **Gradio interface** for interactive predictions.

---

## 🚀 Demo

![App Screenshot](screenshots/demo.gif) <!-- (Optional: Add a gif or image) -->

Try the interactive demo:
> 🔗 Hosted locally via Gradio UI

---

## 🧠 Machine Learning Workflow

- 📚 **Dataset Preprocessing**  
  Cleaned and preprocessed dataset with selected key features.

- ⚙️ **Feature Engineering**  
  Features used: `pH`, `TDS`, `EC`, `NO3`, `SO4`

- 🧪 **Model Training**  
  - Model: `RandomForestRegressor`
  - Evaluation: `R² Score`, `MAE`, `MSE`

- 🧼 **Scaling**  
  Used `StandardScaler` to normalize input features.

- 🔍 **Prediction & Classification**
  WQI values are mapped to contamination levels:
  | WQI Range | Category              |
  |-----------|------------------------|
  | 0–100     | 🟢 Good Quality        |
  | 100–200   | 🟡 Low Contamination   |
  | 200–300   | 🟠 Moderate Contamination |
  | 300+      | 🔴 High Contamination  |

---

## 🧪 Sample Prediction Output

