# ☁️ Weather Prediction Classification

A machine learning project for classifying weather conditions (Rain, Sun, Fog, etc.) using real-world Seattle weather data and models like Decision Tree, KNN, and Logistic Regression.

📚 **Course**: Introduction to Data Science (MTH10171)  
👨‍🏫 **Instructor**: ThS. Hà Văn Thảo  
👥 **Group**: Hồ Ngọc Ân, Trần Tuấn Thái, Huỳnh Quang Trung, Hỏa Ngọc Tú  
📍 **Institution**: University of Science, VNU-HCM  
📅 **Date**: June 2022


## 🔍 Dataset

- Source: [Kaggle - Seattle Weather](https://www.kaggle.com/datasets/ananthr1/weather-prediction)
- Features: 
  - `precipitation` (mm)
  - `temp_max`, `temp_min` (°C)
  - `wind` (m/s)
  - `weather` (categorical target)


## 🧪 Technologies Used

- **Languages**: Python
- **Libraries**: 
  - `pandas`, `numpy`, `matplotlib`, `seaborn` for data analysis & visualization
  - `sklearn` for ML models and evaluation
  - `scipy`, `missingno` for statistical tests and null-value visualization


## 🧹 Data Preprocessing

- Removed outliers using IQR
- Transformed skewed distributions (√ transformation for wind and precipitation)
- Label encoded the target variable `weather`
- Split data into training/test sets (90% / 10%)


## 🤖 Models Applied

1. **K-Nearest Neighbors (KNN)**
2. **Decision Tree**
3. **Logistic Regression**

| Model               | Accuracy |
|---------------------|----------|
| KNN                 | 75.00%   |
| Decision Tree       | **83.06%** ✅ |
| Logistic Regression | 80.65%   |

> 🏆 The Decision Tree model yielded the best accuracy and was selected for final deployment/testing.


## 📊 Model Evaluation

- Used confusion matrix and classification report (`precision`, `recall`, `f1-score`)
- Visualized model comparison using bar charts
- Supported both automated test data and manual input predictions


## 📌 Key Takeaways

- Weather classes with low data representation (e.g., Snow, Fog) lead to weaker model performance.
- Data preprocessing (outlier removal, encoding, distribution fixing) significantly improved model results.
- Decision Tree performed best due to its interpretability and suitability for imbalanced datasets.


## ▶️ Run the Project

You can explore the full Colab notebook here:  
📎 [Google Colab Notebook](https://colab.research.google.com/drive/1xF1djO43fKVzlKZNV0FfUqmXBlMRsIhV?usp=sharing)


## 📜 License

This project is for academic purposes. Feel free to use the code with attribution.
