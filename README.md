
# 🔥 Algerian Forest Fire Prediction (End-to-End ML Project with Flask Deployment)

## 🚀 Project Overview

Forest fires are heavily influenced by environmental factors such as temperature, humidity, wind speed, and rainfall.  This project builds a **machine learning model to predict the Forest Fire Weather Index (FWI)** using meteorological data.

The workflow includes **data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and deployment using Flask**.  

A **web application interface** allows users to enter environmental parameters and instantly receive predictions from the trained model.
## 📊 Dataset

The project uses the **Algerian Forest Fires Dataset**, which contains meteorological and environmental data collected from two regions of Algeria.

Dataset information:

- Total Records: **244**
- Regions: **Bejaia and Sidi Bel-Abbes**
- Time Period: **June – September 2012**

Features include:

- Temperature
- Relative Humidity
- Wind Speed
- Rain
- FFMC
- DMC
- ISI

🔗 Dataset Link  
https://www.kaggle.com/datasets/nitinchoudhary012/algerian-forest-fires-dataset
## 🤖 Machine Learning Workflow

1. **Data Cleaning**
   - Removed unnecessary columns
   - Handled missing values

2. **Exploratory Data Analysis (EDA)**
   - Visualized relationships between weather variables and fire risk
   - Identified important features affecting forest fires

3. **Feature Engineering**
   - Selected relevant features
   - Applied **StandardScaler** for feature scaling

4. **Model Training**
   - Trained multiple regression models
   - Selected **Ridge Regression** for better generalization

5. **Model Deployment**
   - Saved the trained model using **pickle**
   - Integrated the model into a **Flask web application**
## 🌐 Web Application

The Flask web application allows users to input environmental parameters and receive predictions.

User inputs include:

- Temperature
- Relative Humidity
- Wind Speed
- Rain
- FFMC
- DMC
- ISI

The system processes the input data, scales it using **StandardScaler**, and predicts the **Forest Fire Weather Index (FWI)** using the trained Ridge Regression model.
## 📂 Project Structure

  <img width="916" height="537" alt="Screenshot 2026-03-17 023908" src="https://github.com/user-attachments/assets/172fc3a7-b581-48f5-a452-199ac3986a0f" />


## ⚙️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Flask
- HTML / CSS
- Jupyter Notebook
## ▶️ Run Locally

**Clone the repository**

git clone https://github.com/yourusername/algerian-forest-fire-prediction.git

Install dependencies

    pip install -r requirements.txt

Run the application

    python application.py
## 👨‍💻 Author

**Satyansh Singh**  
Electronics and Communication Engineering (ECE) Student  
Birla Institute of Technology, Mesra  

Machine Learning Enthusiast | Full Stack Developer  

📧 Email: [bhikams468@gmail.com](mailto:bhikams468@gmail.com)  
🔗 LinkedIn: [satyansh-singh](https://www.linkedin.com/in/satyansh-singh-567a22260)  
💻 GitHub: [krotov22](https://github.com/krotov22)
