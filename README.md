#  Random Forest – Pima Indians Diabetes

##  Description  
This project applies a **Random Forest Classifier** on the **Pima Indians Diabetes Dataset** to predict whether a patient has diabetes.  
The project includes **data preprocessing, model training, feature importance visualization, and evaluation using Accuracy, Precision, Recall, and F1-Score**.  

---

##  Project Structure  
Random Forest - Pima Indians Diabetes
│── dataset/ # Dataset (diabetes.csv)
│── output/ # Plots (Feature Importance, Confusion Matrix)
│── RandomForest.ipynb # Jupyter Notebook with full code
│── README.md # Project documentation


---

##  Workflow  
1. **Data Preprocessing**  
   - Replaced biologically invalid 0 values (`Glucose`, `BloodPressure`, `SkinThickness`, `Insulin`, `BMI`) with median values.  

2. **Train-Test Split** (80% Training, 20% Testing).  

3. **Random Forest Classifier**  
   - Trained with 100 decision trees.  

4. **Feature Importance Plot**  
   - Highlights most important features such as Glucose, BMI, Age, and Insulin.  

5. **Evaluation Metrics**  
   - Accuracy, Precision, Recall, F1-Score.  
   - Confusion Matrix for visualization.  

---

##  Results (Typical Performance)  
- **Accuracy**: ~77–82%  
- **Precision**: ~70–75%  
- **Recall**: ~65–72%  
- **F1-Score**: ~68–73%  

 Random Forest gives good predictive performance and highlights the most important health indicators for diabetes detection.  

---

## 🚀 How to Run  
```bash
# Clone the repo
git clone https://github.com/<your-username>/Random-Forest-Diabetes.git

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook RandomForest.ipynb

Dependencies

Python 3.8+

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

