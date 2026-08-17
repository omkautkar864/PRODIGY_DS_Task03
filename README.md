# Task-03: Decision Tree Classifier

## 🎯 Objective
Build a Decision Tree Classifier to predict whether a customer will subscribe to a term deposit based on demographic and behavioral data.

## 📂 Dataset
- Source: Bank Marketing Dataset (UCI Repository)
- File: `bank.csv`
- Target Column: `y` (values: yes/no)

## ⚙️ Steps
1. **Data Loading**  
   - Loaded dataset using `pandas` with `sep=";"`.
2. **Preprocessing**  
   - Encoded categorical features using `pd.get_dummies()`.  
   - Converted target column (`yes/no`) into numeric (1/0) using `LabelEncoder`.
3. **Train-Test Split**  
   - Split dataset into training (80%) and testing (20%).
4. **Model Training**  
   - Trained Decision Tree Classifier (`criterion="entropy"`, `max_depth=5`).
5. **Evaluation**  
   - Achieved accuracy: **90.27%** on test data.
6. **Visualization**  
   - Plotted Decision Tree using `matplotlib` and `sklearn.tree.plot_tree`.

## 📊 Output
- **Accuracy:** 0.9027 (~90%)  
- **Decision Tree Diagram:**  

![Decision Tree](images/decision_tree.png)

## 📁 Folder Structure
Task-03/
├── bank.csv
├── task03_decision_tree.ipynb
├── README.md
└── images/
└── decision_tree.png

## ✅ Conclusion
The Decision Tree Classifier successfully predicts customer subscription behavior with high accuracy, demonstrating the importance of feature encoding and model tuning.
