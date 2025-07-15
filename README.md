# 🏡 House Price Prediction using IBM Watson Studio (AutoAI)

This repository contains the complete project developed during my *AI Internship at IBM, focused on predicting house prices using **IBM Watson Studio's AutoAI*.  
The model was trained on a real-world housing dataset to forecast property prices based on multiple features like bedrooms, bathrooms, area, and location.

---

## 🔍 Project Overview

The real estate market requires accurate price estimation to support better decision-making. This project leverages *AutoAI* to automate the machine learning workflow—from data preprocessing to model deployment—making it easier to build predictive models with minimal coding.

---

## 🚀 Features

- Uses *AutoAI* for fully automated ML pipeline generation  
- Automatically handles missing values, encoding, and scaling  
- Trains and compares multiple regression models (like XGBoost, Linear Regression)  
- Deploys the best model using *IBM watsonx.ai runtime*  
- Integrates with *Google Colab* for testing and real-time predictions  
- Achieves high accuracy (R² = 0.89)

---

## 📂 Project Structure




---

## 📊 Dataset Details

- *Source*: [Kaggle House Sales Prediction Dataset](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction)  
- *Size*: ~21 features and 21,000+ rows  
- *Features*:
  - Bedrooms, Bathrooms, Sqft_living, Lot size
  - Year Built, Year Renovated
  - Location (City, Zipcode)
  - Waterfront, View, Condition, Grade

---

## 🔁 Workflow

1. *Dataset Upload* to IBM Watson Studio using Cloud Object Storage  
2. *AutoAI Experiment Setup*  
3. *Pipeline Generation & Evaluation*  
4. *Model Selection* – XGBoost Regressor (R² = 0.89)  
5. *Deployment* using watsonx.ai  
6. *Prediction Testing* using Google Colab

---

## 🖼 Screenshots

| Description            | Screenshot               |
|------------------------|--------------------------|
| AutoAI Leaderboard     | ![Leaderboard](screenshots/leaderboard.png) |
| Model Deployment       | ![Deployment](screenshots/deployment.png) |
| Google Colab Output    | ![Colab](screenshots/colab_output.png) |

---

## 📈 Results

- *Best Model*: XGBoost Regressor  
- *R² Score*: 0.89  
- *Deployment*: Successful on IBM Watson Studio  
- *Prediction*: Tested on Google Colab with accurate outputs

---

## 🛠 Tools & Technologies Used

- IBM Watson Studio (AutoAI)
- IBM Cloud Object Storage
- watsonx.ai Runtime for deployment
- Google Colab for integration
- Python (Pandas, Sklearn, Joblib)
- PowerPoint & Word for documentation

---

## ▶ How to Run (Colab Testing)

1. Clone the repo or download the notebook
2. Upload the .pkl or .zip model in Colab
3. Run the cells to load the model and test on new data

---

## 🙏 Acknowledgement

I would like to thank *IBM* for providing the opportunity to work on this project as part of their *AI Internship, and my mentor **Mr. Samarth Amrute* for his continuous guidance and support throughout the project.

---

## 👩‍💻 Author

*Gaurav Modanwal*  
B.Tech IT, United College of Engineering and Research  
📧 gauravmodanwal239@gmail.com  
🌐 [LinkedIn (optional)](https://linkedin.com/in/your-profile)
