# 🎗️ Breast Cancer Identifier using Random Forest 🌲

## 🧠 Project Overview
This project aims to build an **AI-powered Breast Cancer Classifier** that predicts whether a tumor is **🩸 Malignant** or **💖 Benign** using the **Random Forest algorithm**. It helps in **early cancer detection** and assists doctors in making more reliable and data-driven medical decisions.

---

## 🎯 Objective
Develop a machine learning model capable of accurately identifying breast cancer type based on patient diagnostic data such as cell radius, texture, smoothness, and compactness.

---

## 📊 Dataset
The dataset contains medical features extracted from breast cell nuclei images, including:

- 🔵 Mean Radius  
- 🟣 Texture  
- 🟢 Smoothness  
- 🟡 Compactness  
- 🟠 Concavity  
- 🔴 Symmetry  
- ⚪ Fractal Dimension  

📂 **Target Column:** `diagnosis` → `M` (Malignant) or `B` (Benign)  
📚 **Source:** UCI Machine Learning Repository / Kaggle

---

## ⚙️ Workflow

1. **🧹 Data Preprocessing**
   - Handle missing and duplicate values  
   - Encode categorical labels (`M` → 1, `B` → 0)  
   - Normalize feature scales  

2. **🔍 Exploratory Data Analysis (EDA)**
   - Visualize feature relationships and correlations  
   - Identify key attributes influencing diagnosis  

3. **🤖 Model Building**
   - Algorithm: 🌲 **Random Forest Classifier**  
   - Train-test split for validation  
   - Hyperparameter tuning with GridSearchCV  

4. **📈 Model Evaluation**
   - Accuracy ✅  
   - Precision 🎯  
   - Recall 🔁  
   - F1 Score 🏅  
   - Confusion Matrix 📊  

5. **🧪 Prediction on Unseen Data**
   - Load trained model (`breast_cancer_model.pkl`)  
   - Input patient data to predict tumor type  

---

## 🧩 Results
✅ Achieved high accuracy on test data  
🩺 Effectively distinguishes **malignant** vs **benign** cases  
🌲 Random Forest provides robust and interpretable predictions  

---

## 💡 Key Insights
- 🔍 Features like **radius mean**, **texture mean**, and **concavity** are highly significant.  
- 🌿 Ensemble learning enhances predictive stability.  
- 💬 Model supports medical diagnosis with confidence.  

---

## 🛠️ Technologies Used
| Tool | Purpose |
|------|----------|
| 🐍 Python | Programming language |
| ⚙️ Scikit-learn | ML model implementation |
| 📊 Pandas, NumPy | Data manipulation |
| 📉 Matplotlib, Seaborn | Data visualization |
| 💻 Jupyter Notebook | Interactive environment |

---

## 📦 Files in Repository
| File | Description |
|------|--------------|
| `Breast_Cancer_Identifier.ipynb` | Main notebook |
| `breast_cancer_dataset.csv` | Input dataset |
| `breast_cancer_model.pkl` | Trained model |
| `README.txt` | Project documentation |

---

## 🚀 How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/Breast-Cancer-Identifier.git
   ```

2. Navigate to the project folder  
   ```bash
   cd Breast-Cancer-Identifier
   ```

3. Install dependencies  
   ```bash
   pip install -r requirements.txt
   ```

4. Launch the notebook  
   ```bash
   jupyter notebook Breast_Cancer_Identifier.ipynb
   ```

---

## 🔮 Future Enhancements
- 🧠 Use Deep Learning (ANN/CNN) for feature extraction  
- 🌐 Build a web interface for patient data entry  
- 📊 Integrate model explainability with SHAP or LIME  

---

## 🏆 Author
👩‍💻 Harshita Sharma
💬 Passionate about AI & Healthcare Innovation 🧬  
📧 harshitash1107@gmail.com 

⭐ *If you found this project useful, give it a star!* 🌟
