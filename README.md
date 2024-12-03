# Hackathon Submission - Hi! Paris Water Shortage Prediction Challenge 🌲  

## 🌟 **Team Submission for the Hi! Paris Hackathon**  

Welcome to our GitHub repository! This repository contains the code, preprocessing steps, and documentation for our submission to the Hi! Paris Hackathon. The challenge was centered around predicting water shortages using a provided dataset, which required creative problem-solving and technical implementation.  

---

## 🏆 **Challenge Overview**  
Water scarcity is one of the most pressing issues of our time, and the ability to predict shortages can help mitigate its devastating effects. The goal of this challenge was to develop a machine learning model that could accurately predict water shortages based on a variety of features provided in the dataset. This event took place November 29th to December 2nd 2024.

---


## 🚀 **Our Approach**  
### 1. **Preprocessing and Feature Engineering**  
- **Data Understanding**: Identify redundant and useless value
- **Data Cleaning**: Addressed missing values using median/mode imputation for numerical and categorical features.  
- **Feature Extraction**: Processed date-related columns to extract `year`, `month`, and `day`.  
- **Encoding**: Used `LabelEncoder` for categorical features.  
- **Filtering**: Focused on specific months (e.g., June to September) where water shortages are more prevalent.  

### 2. **Model Development**  
We experimented with various machine learning models including:  
- XGBoost (GPU-accelerated for scalability and speed)  
- Random Forest  
- Support Vector Machines (SVM)
- ANNs

**Final Model**: We selected **Random Forest** as our final model due to its balance between accuracy and computational efficiency.  

### 3. **Evaluation**  
- **Metric**: The model was evaluated on accuracy, achieving a score of **58%**.  
- **Challenges**: Predicting water shortages is a complex task with inherent variability in the data, but our preprocessing pipeline and model tuning allowed us to extract meaningful patterns.  

---

## ✨ **Highlights**  
- **Scalable Preprocessing Pipeline**: Designed to handle missing data, categorical encoding, and feature extraction.  
- **Collaboration and Iteration**: Our team worked together to refine the pipeline and improve model accuracy over multiple iterations.  

---

## 📊 **Results and Insights**  
- **Model Accuracy**: 58%  
- **Takeaways**:  
  - Importance of data preprocessing in improving model performance.  
  - Seasonal patterns play a crucial role in predicting water shortages.  
  - Potential for improvement by integrating external datasets (e.g., climate data).  


---

## 🤝 **Acknowledgments**  
We extend our gratitude to **Hi! Paris** for organizing this hackathon and providing a platform to address such a critical challenge.  
 
**Visit the Hi!ckathon website**: https://www.hi-paris.fr/hickathon/

**Visit the Hi!ckathon repo**: https://github.com/hi-paris
<br>

---

## 👥 **Contributors**  
- **Anthony** - Data Preprocessing & EDA  
- **Nadya** - Data Preprocessing & EDA  
- **Augustin** - Model Development & Training
- **Channdeth** - Model Development & Training
- **Mathieu** - Evaluation & Documentation    
- **Lina** - Evaluation & Documentation  

Feel free to reach out with questions or feedback. Thank you for visiting our repository! 🌍✨  
