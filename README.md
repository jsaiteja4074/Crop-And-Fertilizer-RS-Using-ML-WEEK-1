# Crop and Fertilizer Recommendation System using Machine Learning  MILESTONE
 

# Crop and Fertilizer Recommendation System   
# Hi there, I'm Janagam Sai teja 👋  
---

![CROP  FERT 1](https://github.com/user-attachments/assets/e84f2732-7206-4b3b-b453-c4694ae2e89e)

---

## Overview  
This project focuses on building a machine learning-based recommendation system to suggest the most suitable crops and fertilizers for farmers based on soil and environmental parameters. The goal is to enhance agricultural productivity by leveraging data-driven decision-making.The Crop and Fertilizer Recommendation System leverages machine learning to empower farmers with data-driven recommendations for crop selection and fertilizer application. By analyzing critical factors such as soil nutrients (NPK levels), pH value, temperature, humidity, and rainfall, the system identifies the most suitable crops to grow and fertilizers to use. The project incorporates two machine learning models: a crop recommendation model using Random Forest and a fertilizer recommendation model using Decision Trees. This initiative aims to optimize agricultural productivity, reduce resource wastage, and promote sustainable farming practices. With plans for integration into IoT-enabled systems and mobile applications, this project seeks to transform traditional agriculture into a smarter, more efficient process, ensuring better decision-making and higher yields for farmers.

---

## Table of Contents  
1. **Project Description**  
2. **Dataset**  
3. **Model Architecture**   
4. **Training**   
5. **Technologies Used**  
6. **Future Scope**  
---

## Project Description  
Agriculture is one of the primary sectors that needs technological advancements to ensure food security. This project uses machine learning to recommend the best crops to grow and fertilizers to use based on soil conditions, weather, and other factors, helping farmers make informed decisions and boost yields.

---

## Dataset  
The datasets used for this project come from reliable agricultural sources and include parameters like nitrogen, phosphorus, potassium (NPK) levels, pH value of soil, temperature, humidity, and rainfall.  

### Key Details:  
- **Crop Dataset:** Contains data about crops suitable for specific soil and environmental conditions.  
  - **Rows:** ~22,000  
  - **Features:** NPK values, pH, temperature, humidity, rainfall, and crop type.  
- **Fertilizer Dataset:** Contains data about fertilizers suitable for various crops and soil conditions.  
  - **Rows:** ~10,000  
  - **Features:** Crop type, soil nutrient levels, fertilizer type, and efficiency.  

**Dataset Sources:**  
- Kaggle  
- FAO Database  
- Open Government Data Platform India  

---

## Model Architecture  
The system consists of two components:  

1. **Crop Recommendation Model**  
   - Algorithm: Random Forest Classifier  
   - Input Features: NPK values, pH, temperature, humidity, rainfall.  
   - Output: Recommended crop.
     
     ![CROP   FERT](https://github.com/user-attachments/assets/d182b0ad-1d48-42b5-932c-6cdd01673993)
     
2. **Fertilizer Recommendation Model**  
   - Algorithm: Decision Tree Classifier  
   - Input Features: Crop type, NPK values, pH.  
   - Output: Suggested fertilizer.  

Both models use a pipeline for preprocessing and hyperparameter tuning to optimize performance.

---

## Training  
- **Crop Recommendation Model:**  
  - Optimizer: GridSearchCV for hyperparameter tuning  
  - Evaluation Metric: Accuracy and F1 Score  

- **Fertilizer Recommendation Model:**  
  - Optimizer: RandomizedSearchCV  
  - Evaluation Metric: Precision and Recall  

---

## Technologies Used  
- Python  
- Scikit-learn  
- Pandas  
- NumPy  
- Matplotlib/Seaborn  

---

## Future Scope  
- Adding more features like market price predictions for crops.  
- Expanding datasets with region-specific soil and weather conditions.  
- Creating a mobile or web application for real-time recommendations.  
- Integrating IoT sensors for real-time soil data collection.  

---
