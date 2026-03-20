# Heart Disease Prediction 🫀

A machine learning project to predict whether a patient has heart disease using the K-Nearest Neighbors (KNN) classification algorithm.

---

## 📌 Problem Statement

Given clinical data about a patient (age, cholesterol, blood pressure, etc.), predict whether the patient has heart disease (`target = 1`) or not (`target = 0`).

---

## 📂 Project Structure

```
heart-disease-prediction/
│
├── Heart_disease.ipynb     # Main Jupyter notebook (EDA + Model)
├── heart.csv               # Dataset (place your heart.xls/.csv here)
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
```

---

## 📊 Dataset

- **Source:** [UCI Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
- **Rows:** ~303 records (after removing duplicates)
- **Target column:** `target` (1 = heart disease, 0 = no heart disease)

**Features used:**

| Feature | Description |
|---------|-------------|
| age | Age of patient |
| sex | Sex (1 = male, 0 = female) |
| cp | Chest pain type (0–3) |
| trestbps | Resting blood pressure |
| chol | Serum cholesterol (mg/dl) |
| fbs | Fasting blood sugar > 120 mg/dl |
| restecg | Resting ECG results |
| thalach | Maximum heart rate achieved |
| exang | Exercise induced angina |
| oldpeak | ST depression induced by exercise |
| slope | Slope of peak exercise ST segment |
| ca | Number of major vessels (0–3) |
| thal | Thalassemia type |

---

## 🔧 Steps Followed

1. **Data Loading** — Load dataset with pandas
2. **EDA** — Check shape, data types, null values, class distribution
3. **Data Cleaning** — Remove duplicate rows
4. **Outlier Handling** — IQR-based capping (clipping)
5. **Train/Test Split** — 80/20 split with `random_state=42`
6. **Model Training** — K-Nearest Neighbors (KNN)
7. **Evaluation** — Accuracy, Confusion Matrix, Precision, Recall, F1 Score

---

## 📈 Model Performance

| Metric | Score |
|--------|-------|
| Accuracy | ~XX% |
| Precision | ~XX% |
| Recall | ~XX% |
| F1 Score | ~XX% |

> *(Run the notebook to see actual scores)*

---

## 🚀 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/heart-disease-prediction.git
cd heart-disease-prediction
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Add dataset
Place your `heart.xls` or `heart.csv` file in the project folder.

### 4. Open the notebook
```bash
jupyter notebook Heart_disease.ipynb
```

---

## 🛠️ Tech Stack

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- Jupyter Notebook

---

## 👤 Author

**Your Name**
- GitHub: [@YOUR_USERNAME](https://github.com/YOUR_USERNAME)
- LinkedIn: [Your LinkedIn](https://linkedin.com/in/YOUR_PROFILE)

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).
