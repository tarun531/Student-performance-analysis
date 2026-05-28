# 📊 Student Performance Analysis using Data Science & Machine Learning

## 📌 Project Overview

This project demonstrates a complete Student Performance Analysis System where student academic data is analyzed to identify performance trends, learning patterns, and factors affecting student scores.

The system uses Data Science techniques, data visualization, and Machine Learning algorithms to analyze student performance and predict outcomes based on various academic and personal attributes.

Unlike traditional projects that only focus on visualization, this project includes:

* Data preprocessing
* Exploratory Data Analysis (EDA)
* Performance visualization
* Machine learning prediction
* Statistical insights
* Interactive dashboard

This project simulates a real-world academic analytics system used by educational institutions.

---

# 🎯 Key Features

✅ Student Performance Analysis
📊 Data Visualization & Insights
🧠 Machine Learning Prediction
📈 Exploratory Data Analysis (EDA)
🌐 Interactive Dashboard
📁 CSV Dataset Processing
🚀 Performance Prediction
🎨 Responsive UI

---

# 🧠 Architecture / Workflow

```text id="jlwm21"
Student Dataset
        ↓
Data Cleaning & Preprocessing
        ↓
Exploratory Data Analysis (EDA)
        ↓
Visualization & Insights
        ↓
Machine Learning Model Training
        ↓
Performance Prediction
        ↓
Dashboard Result Display
```

---

# ⚙️ Tech Stack

| Category         | Tools                |
| ---------------- | -------------------- |
| Programming      | Python               |
| Data Analysis    | Pandas, NumPy        |
| Visualization    | Matplotlib, Seaborn  |
| Machine Learning | Scikit-learn         |
| Backend          | Flask                |
| Frontend         | HTML, CSS, Bootstrap |
| Deployment       | GitHub / Render      |

---

# 📂 Project Structure

```text id="jlwm22"
Student-Performance-Analysis/
│
├── app.py
├── analysis.py
├── model.pkl
├── student_data.csv
├── requirements.txt
│
├── templates/
│   ├── index.html
│   └── result.html
│
├── static/
│   ├── style.css
│   └── charts/
│
└── README.md
```

---

# 🔄 How It Works (Step-by-Step)

## 1️⃣ Dataset Collection

The system uses a student performance dataset containing:

* Study Hours
* Attendance
* Previous Scores
* Gender
* Parental Education
* Internet Access
* Final Exam Scores

---

## 2️⃣ Data Preprocessing

The dataset is cleaned by:

* Handling missing values
* Removing duplicates
* Encoding categorical values
* Feature scaling

---

## 3️⃣ Exploratory Data Analysis (EDA)

The system analyzes:

* Average student performance
* Subject-wise scores
* Attendance impact
* Study hour trends
* Gender-wise performance

Example Visualizations:

* Bar charts
* Pie charts
* Heatmaps
* Histograms

---

## 4️⃣ Machine Learning Model Training

The model is trained using:

```python id="jlwm23"
Linear Regression
Random Forest Regressor
```

The algorithm predicts student performance based on input features.

---

## 5️⃣ Prediction System

The user enters student details such as:

* Study Hours
* Attendance
* Previous Marks

The model predicts:

📈 Expected Student Performance

---

# 🚀 How to Run This Project

## 🔹 Prerequisites

* Python 3.x
* VS Code
* Git
* pip

---

## 🔹 Step 1: Clone Repository

```bash id="jlwm24"
git clone https://github.com/tarun531/Student-performance-analysis.git

cd Student-performance-analysis
```

---

## 🔹 Step 2: Create Virtual Environment

```bash id="jlwm25"
python -m venv venv
```

Activate environment:

### Windows

```bash id="jlwm26"
venv\Scripts\activate
```

---

## 🔹 Step 3: Install Dependencies

```bash id="jlwm27"
pip install -r requirements.txt
```

---

## 🔹 Step 4: Train Machine Learning Model

```bash id="jlwm28"
python analysis.py
```

This generates:

```text id="jlwm29"
model.pkl
```

---

## 🔹 Step 5: Run Flask Application

```bash id="jlwm30"
python app.py
```

---

## 🔹 Step 6: Open Browser

```text id="jlwm31"
http://127.0.0.1:5000
```

---

# 📊 Data Analysis Workflow

## Input Features

* Study Hours
* Attendance
* Previous Marks
* Internet Access
* Parental Education

## Output

* Predicted Student Performance
* Performance Insights
* Visual Analytics

---

# 📸 Expected Output

## Example Input

| Feature        | Value |
| -------------- | ----- |
| Study Hours    | 6     |
| Attendance     | 90%   |
| Previous Marks | 85    |

---

## Predicted Output

```text id="jlwm32"
Predicted Student Score: 88%

Performance Level:
Excellent
```

---

# 📈 Example Insights

## Analysis Results

* Students with higher attendance perform better
* Study hours positively impact scores
* Previous marks influence final performance
* Internet access improves learning outcomes

---

# 🏆 Key Learning Outcomes

* Data preprocessing techniques
* Exploratory Data Analysis (EDA)
* Data visualization
* Machine learning model development
* Flask web application development
* Real-world educational analytics
* Predictive analysis systems

---

# 🔥 Why This Project is Important

Educational institutions generate massive amounts of student data.

This project demonstrates how Data Science and Machine Learning can help:

* Analyze student performance
* Predict academic outcomes
* Identify weak students
* Improve teaching strategies
* Support data-driven education systems

It simulates a real-world academic analytics platform.

---

# 👨‍💻 Author

## Tarun Sunkam

GitHub:
https://github.com/tarun531

---

# ⭐ Future Improvements

* Deep Learning Models
* Student Login System
* Real-time Dashboard
* Cloud Deployment
* Subject-wise Predictions
* Attendance Monitoring
* PDF Report Generation
* Performance Alerts

---

# 💡 Final Note

This project represents a real-world Student Performance Analysis System that combines Data Science, Machine Learning, and Visualization techniques to analyze student data and predict academic performance with meaningful insights.

