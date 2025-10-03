# aimltask-7
Task 7: Support Vector Machines (SVM)
# 🧠 Support Vector Machines (SVM) – Classification Task

## 📌 Objective
Implement and understand **Support Vector Machines (SVMs)** for binary classification using both **Linear** and **RBF kernels**.  
Key concepts covered:
- Margin maximization  
- Kernel trick  
- Hyperparameter tuning (C, gamma)  
- Cross-validation evaluation  

---

## 🛠 Tools & Libraries
- Python 3  
- Scikit-learn  
- NumPy  
- Matplotlib  

---

## 📂 Dataset
- **Breast Cancer Dataset** (from `sklearn.datasets`)  
- Binary classification: Malignant (0) vs Benign (1)  

---

## 🚀 Steps Implemented
1. **Load & preprocess dataset**  
   - Used `StandardScaler` to normalize features.  
2. **Train SVM models**  
   - Linear Kernel  
   - RBF Kernel  
3. **Visualize decision boundaries**  
   - Reduced features to 2D using PCA for visualization.  
4. **Hyperparameter tuning**  
   - Used `GridSearchCV` to optimize `C` and `gamma`.  
5. **Cross-validation**  
   - Evaluated performance using 5-fold CV.  

---

## 📊 Results
- **Linear SVM Accuracy**: `96.5%`  
- **RBF SVM Accuracy**: `97.4%`  
- **Best Parameters (GridSearchCV)**: `{ 'C': 10, 'gamma': 0.01, 'kernel': 'rbf' }`  
- **Mean CV Accuracy**: `97.2%`  

---

## 📸 Visualizations
- PCA 2D projection with decision boundary plots.  
- Clear separation of malignant vs benign samples.  

*(Add screenshots of your plots in a `/screenshots` folder.)*  

---

## 📁 Repository Contents
- `svm_classification.ipynb` → Jupyter Notebook with code.  
- `README.md` → Documentation (this file).  
- `screenshots/` → Visual results (plots).  

---

## ✅ How to Run
```bash
git clone https://github.com/your-username/SVM-Classification-Task.git
cd SVM-Classification-Task
pip install -r requirements.txt
jupyter notebook svm_classification.ipynb
