# 🏥 Medical Insurance Cost Prediction 💰

A Machine Learning project that predicts **medical insurance costs** based on personal details such as age, gender, BMI, number of children, smoking status, and region.  

---

## 📌 Project Overview
Healthcare costs vary from person to person. By analyzing past insurance data, we can **build a predictive model** that estimates the insurance charges for a new individual.  

This project includes:
- Data Preprocessing ⚙️  
- Exploratory Data Analysis (EDA) 📊  
- Model Training 🤖  
- Model Evaluation ✅  
- Predictive System 🔮  

---

## 📂 Dataset
The dataset typically contains the following features:

| Column     | Description |
|------------|-------------|
| `age`      | Age of the insured |
| `sex`      | Gender (male/female) |
| `bmi`      | Body Mass Index |
| `children` | Number of children covered |
| `smoker`   | Smoking status (yes/no) |
| `region`   | Residential region (northeast, northwest, southeast, southwest) |
| `charges`  | Insurance cost (Target Variable) |

---

## 🔍 Exploratory Data Analysis (EDA)

- **Distribution of Age, BMI, Charges**
- **Count plots** for categorical features (`sex`, `smoker`, `region`, `children`)
- **Correlation Heatmap** to check feature relationships

---

## ⚙️ Data Preprocessing

1. Handling categorical columns:
   - `sex` → Male=0, Female=1  
   - `smoker` → Yes=0, No=1  
   - `region` → Southeast=0, Southwest=1, Northeast=2, Northwest=3  

2. Splitting dataset into train/test (80/20)

---

## 🤖 Model Training

Trained regression models to predict insurance cost.  
The best results were achieved using **Linear Regression**.

---

## 📊 Model Result

✅ **R² Score:** 0.79 (79% variance explained)  
📉 **Mean Absolute Error (MAE):** 2700.34  
📈 **Mean Squared Error (MSE):** 18590221.45  

---

## 🧪 Predictive System

Built a **user-interactive system** where the user enters details, and the model predicts the insurance cost.  

### Example Console Run:
🎂 Enter Age: 31   
👩‍🦰👨 Enter Sex (male/female): female  
⚖️ Enter BMI: 25.5  
👶 Enter number of children: 0   
🚬 Smoker? (yes/no): no    
🌍 Region (southeast/southwest/northeast/northwest): southeast  

🔮 Prediction Result 🔮  
💰 Estimated Medical Insurance Cost: $3680.73 🏥  


---

## 🚀 Future Improvements
- Deploy as a **Streamlit Web App** 🌐  
- Try **Random Forest / XGBoost** for better accuracy  
- Add more healthcare-related features  

---

## 🏆 Conclusion
This project demonstrates how **Machine Learning can help in healthcare cost estimation**, supporting both insurance companies and customers with better financial planning.  

---

👨‍💻 **Developed by:** *Rahul kumar*


