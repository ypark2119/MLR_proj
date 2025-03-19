# **MLR_proj: Multiple Linear Regression Analysis**

This repository contains an interactive **Multiple Linear Regression (MLR) Analysis** web app built with **Streamlit**. The app allows users to explore MLR models, evaluate model performance, and analyze regression statistics.

📌 **Live App:** [Click here to access the Streamlit App](https://benetxeulhct7wukbb8vzw.streamlit.app/)

---

## **Features**

- **Upload CSV Data** 📂: Load your dataset directly into the app.
- **Model Selection** ⚙️: Choose predictor variables and fit an MLR model.
- **Regression Metrics** 📊: View R-squared, AIC, BIC, and Cp for model evaluation.
- **Residual Analysis** 🔍: Visualize leverage points and residual errors.
- **Download Results** 💾: Export regression outputs for further analysis.

---

## **Installation**

To run the project locally, follow these steps:

### **1. Clone the Repository**

```sh
git clone https://github.com/ypark2119/MLR_proj.git
cd MLR_proj
```

### **2. Create a Virtual Environment (Optional but Recommended)**

```sh
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate     # On Windows
```

### **3. Install Dependencies**

```sh
pip install -r requirements.txt
```

### **4. Run the Streamlit App**

```sh
streamlit run app.py
```

---

## **Usage**

1. Open the Streamlit app using the provided link or run it locally.
2. Upload your dataset in CSV format.
3. Select the independent variables and fit an MLR model.
4. Analyze model statistics and visualization outputs.
5. Download the regression results for further use.

---

## **Technologies Used**

- **Python** 🐍
- **Streamlit** 🌐
- **Pandas** 🏛️
- **Scikit-learn** 🤖
- **Statsmodels** 📉
