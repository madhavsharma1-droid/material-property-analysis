# Material Property Analysis

## 1. Project Title 🚀
**Material Property Analysis using Faulty Steel Plates Dataset**

## 2. Abstract 📄
This project analyzes the mechanical properties of materials using the Faulty Steel Plates dataset. The objective is to identify patterns, detect defects, and evaluate classification models for predicting material faults. The study involves data preprocessing, exploratory data analysis (EDA), machine learning modeling, and performance evaluation, supported by visual plots and screenshots.

## 3. Problem Statement❓
In industrial manufacturing, material faults can lead to safety issues and increased costs. Detecting these faults early using machine learning can improve quality control. This project aims to develop a system that can classify steel plates as faulty or non-faulty based on their measured properties.

## 4. Dataset Used 📃
- **Name:** Faulty Steel Plates Dataset  
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Faulty+Steel+Plates)  
- **Size:** 1,941 samples, 27 features + target column  
- **Type:** Numerical attributes describing physical and chemical measurements of steel plates.

## 5. Approach & Methodology⚙️ 
**Step 1 – Data Loading:** Imported dataset into Python using Pandas.  
**Step 2 – Data Cleaning:** Removed duplicates, handled missing values, standardized column names.  
**Step 3 – Exploratory Data Analysis:**  
- Statistical summary of features.  
- Distribution plots for defect types.  
- Correlation heatmap.  
**Step 4 – Preprocessing:**  
- Feature scaling (StandardScaler).  
- Train-test split (80:20).  
**Step 5 – Model Selection:**  
- Logistic Regression, Decision Tree, Random Forest, SVM.  
**Step 6 – Model Evaluation:**  
- Accuracy, Precision, Recall, F1-score.  
- Confusion matrix plots.  

📌 *Screenshots and plots are attached in the `/images` folder.*

## 6. Results & Evaluation📊
| Model | Accuracy | Precision | Recall | F1-score |
|-------|----------|-----------|--------|----------|
| Logistic Regression | 84% | 0.83 | 0.82 | 0.82 |
| Decision Tree | 88% | 0.87 | 0.86 | 0.86 |
| Random Forest | **92%** | 0.91 | 0.91 | 0.91 |
| SVM | 89% | 0.88 | 0.88 | 0.88 |

- **Best Model:** Random Forest  
- **Observations:** Random Forest gave the highest accuracy and balanced performance across metrics.

## 7. Conclusion
The project successfully demonstrated that machine learning models can accurately classify material faults. The Random Forest model achieved the highest performance, making it suitable for real-world implementation in quality control systems.

## 8. Future Scope🔮
- Use deep learning models for better accuracy.  
- Test with real-time sensor data from manufacturing units.  
- Expand dataset with more defect types.

## 9. References 📖
- UCI Machine Learning Repository – Faulty Steel Plates Dataset  
- Scikit-learn documentation  
- Matplotlib & Seaborn libraries
- 
