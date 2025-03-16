# **Smoking Status Classification**
## **Overview**
This project aims to classify smoking status using various health metrics. The notebook explores data analysis, visualization, model training, and evaluation of classification models.
## **Objectives**
- Conduct ** Exploratory Data Analysis (EDA) ** to understand the dataset and identify key features.
- Perform **data preprocessing**, including handling missing values, feature scaling, and dataset splitting.
- Implement and train **three separate machine learning models**:
- **Logistic Regression** - a simple yet competitively effective linear classifier.
- **Random Forest** - an ensemble-based method for better generalization-
- **Support VEctor Machine (SVM)** - apowerful model for classification tasks.
- Evaluate model performance using various **classficiation metrics** and **visualizations**
- Explore potential improvements such as **cross-validation** and **hyperparameter tuning**.

## **Dataset Description**
The dataset contains various health-related attributes used to predict smoking status. The key features include:
-** Dempographic variables**( e.g., age, gender).
- **Physiological measures** (e.g., blood pressure, cholesterol levels, BMI).
- **Lifestyle indicators** (e.g., exercise frequency, dietary habits).
- **Medical history** (e.g., presence of chronic conditions).

The target variable is **smoking status**, which is classified into different categories (e.g., smoker, non-smoker, former smoker).

## **Project Workflow**
### **1. Data Exploration & Visualization**
- Analyzing feature distributions and relationships with smoking status.
- Identifying missing values and potential outliers.
- Visualizing key trends using **matplotlib** and **seaborn**.

### **2. Data Preprocessing**
- Handling missing or inconsistent data.
- Feature scaling using standardization or normalization.
- Splitting the dataset into **training** and **test sets**.

### **3. Model Training & Evaluation**
- Implementing **Logistic Regression, Random Forest, and SVM** classifiers.
- Training models on the preprocessed dataset.
- Evaluating model performance using:
  - **Confusion Matrix** – to assess true positives, false positives, etc.
  - **ROC Curve & AUC Score** – for measuring classification effectiveness.
  - **Accuracy, Precision, Recall, and F1-Score**.

### **4. Model Optimization & Improvements**
- Applying **cross-validation** to improve model reliability.
- Performing **hyperparameter tuning** for optimal model settings.
- Comparing models to determine the best-performing classifier.

## **Technologies Used**
- **Python** –  programming language applied for the development and structure of the project.
- **Libraries**:
  - numpy – numerical computations.
  - pandas – data manipulation and analysis.
  - scikit-learn – machine learning models and evaluation.
  - matplotlib & seaborn – data visualization.

## **Installation & Usage**
1. Clone this repository:
   
   git clone https://github.com/your-repository/smoking-status-classification.git
   cd smoking-status-classification
   
2. Install dependencies:
   
   pip install numpy pandas scikit-learn matplotlib seaborn
   
3. Open the Jupyter Notebook
   
4. Run the smoking_status_maria_nyolcas.ipynb file step by step.

## **Results & Findings**
- The **Random Forest classifier** showed the highest accuracy, followed by SVM and Logistic Regression.
- The **ROC curves** indicated that ensemble-based models performed better than linear models.
- **Cross-validation** and hyperparameter tuning significantly improved performance.

## **Future Improvements and Possible Project Extensions**
- **Feature Engineering**: Extracting new meaningful features.
- **Deep Learning Approaches**: Implementing neural networks for classification.
- **Larger Datasets**: Testing on larger and more diverse datasets for generalization.



