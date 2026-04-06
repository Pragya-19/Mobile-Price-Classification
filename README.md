# 📱 Mobile Price Classification

## 🚀 Overview
This project predicts the **price range of mobile phones** based on features such as RAM, battery power, internal memory, camera quality, and screen dimensions.

It is a supervised machine learning classification problem designed to simulate real-world product pricing and customer segmentation.

---

## 🎯 Problem Statement
Given mobile specifications, the objective is to classify devices into different price categories.

This helps in:
- Understanding market segmentation
- Assisting customers in choosing the best product
- Supporting pricing strategy decisions

---

## 📊 Dataset
- Source: Kaggle  
- Training data: 2000 rows, 21 features  
- Test data: 1000 rows, 21 features  

Features include:
- RAM
- Battery power
- Camera specifications
- Screen size
- Processor cores

---

## ⚙️ Tech Stack
- Python
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## 🔄 Workflow
1. Data loading and validation  
2. Data cleaning and preprocessing  
3. Exploratory Data Analysis (EDA)  
4. Feature selection  
5. Train-test split (85% train, 15% test)  
6. Model training  
7. Model evaluation  

---

## 📈 Model & Results

- Model used: **Random Forest Classifier**
- The model performs well across most price categories

### Key Observation:
- High accuracy in predicting most price ranges  
- Slight difficulty in identifying **price range 2**, but performs well for others  

---

## 🔍 Key Insights

- Higher RAM → Higher price range  
- Better battery → Higher price segment  
- Positive correlation:
  - Primary & front camera  
  - Screen width & height  
- Customers prefer:
  - 4G-enabled phones in higher price range  
  - More features as budget increases  

---

## 📂 Project Structure
# 📱 Mobile Price Classification

## 🚀 Overview
This project predicts the **price range of mobile phones** based on features such as RAM, battery power, internal memory, camera quality, and screen dimensions.

It is a supervised machine learning classification problem designed to simulate real-world product pricing and customer segmentation.

---

## 🎯 Problem Statement
Given mobile specifications, the objective is to classify devices into different price categories.

This helps in:
- Understanding market segmentation
- Assisting customers in choosing the best product
- Supporting pricing strategy decisions

---

## 📊 Dataset
- Source: Kaggle  
- Training data: 2000 rows, 21 features  
- Test data: 1000 rows, 21 features  

Features include:
- RAM
- Battery power
- Camera specifications
- Screen size
- Processor cores

---

## ⚙️ Tech Stack
- Python
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## 🔄 Workflow
1. Data loading and validation  
2. Data cleaning and preprocessing  
3. Exploratory Data Analysis (EDA)  
4. Feature selection  
5. Train-test split (85% train, 15% test)  
6. Model training  
7. Model evaluation  

---

## 📈 Model & Results

- Model used: **Random Forest Classifier**
- The model performs well across most price categories

### Key Observation:
- High accuracy in predicting most price ranges  
- Slight difficulty in identifying **price range 2**, but performs well for others  

---

## 🔍 Key Insights

- Higher RAM → Higher price range  
- Better battery → Higher price segment  
- Positive correlation:
  - Primary & front camera  
  - Screen width & height  
- Customers prefer:
  - 4G-enabled phones in higher price range  
  - More features as budget increases  

---

## 📂 Project Structure
Mobile-Price-Classification/

│
├── mobile-price-classification-final.ipynb

├── train.csv

├── test.csv

├── README.md



---

## ▶️ How to Run

1. Clone the repository  
2. Install required libraries  
3. Open Jupyter Notebook  
4. Run all cells  

---

## 🔮 Future Improvements

- Add model comparison (Logistic Regression, SVM, etc.)  
- Improve accuracy for mid-range category (price range 2)  
- Convert notebook into modular ML pipeline  
- Add deployment (Streamlit / Flask)

---

## 👩‍💻 Author

**Pragya Kapil**  
QA Automation Engineer | Data Science & AI/ML  
