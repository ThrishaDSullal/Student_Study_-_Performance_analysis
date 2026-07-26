# 🎓 Student Study Pattern vs Exam Performance Analysis
An end-to-end Data Analytics & Machine Learning project that analyzes how student study habits impact exam performance using Python, Machine Learning, and Power BI. The project demonstrates the complete analytics workflow, including data cleaning, exploratory data analysis (EDA), feature engineering, ML model building, interactive dashboard creation, and actionable insights.

# 📖 Project Overview
Understanding the link between study habits and academic performance is essential for helping students improve and enabling educators to identify at-risk learners early. This project analyzes 107 student survey records to uncover how factors like study hours, attendance, sleep, distraction levels, and revision habits relate to exam scores. A machine learning classification model was built to predict whether a student is a High Performer or Low Performer, and the findings were visualized through an interactive Power BI dashboard.

# 📂 Dataset
Dataset Summary
Rows: 107
Columns: 13 (original)
Source: Direct survey of classmates at AIMIT, St. Aloysius College (Autonomous), Mangalore

# Key Features
Study Hours per Day
Study Days per Week
Attendance Rate
Sleep Duration
Revision Frequency
Distraction Type & Level
Mobile Usage Hours
Last-Minute Study Habit
Exam Score

The dataset contains self-reported student behavior and lifestyle data linked to actual exam scores, enabling both statistical and predictive analysis.

# 🛠️ Tools & Technologies
Tool | Purpose
Python | Data Cleaning & Analysis
Pandas | Data Manipulation
NumPy | Numerical Operations
Matplotlib | Data Visualization
Seaborn | Statistical Visualization
Scikit-learn | Machine Learning (Classification Models)
Power BI | Interactive Dashboard
Jupyter Notebook | Development Environment
Git & GitHub | Version Control

# 🔄 Project Workflow
# 1️⃣ Data Loading
Imported dataset into Python using Pandas.
Performed initial exploration using info() and describe().

# 2️⃣ Data Cleaning & Preprocessing
The dataset was cleaned and prepared before modeling by:
- Handling missing values (mean imputation for Score column)
- Applying Ordinal Encoding for naturally ordered variables
- Applying Label Encoding for categorical variables (StudyDays, Revision, DistractionType, MobileHours)
- Engineering new features (study_quality, study_efficiency, distraction_impact)
- Creating the target variable performance_class (threshold: Score ≥80 = High Performance)

# 3️⃣ Exploratory Data Analysis (EDA)
Performed visual analysis to understand study behavior patterns.

# Analysis Included
- Score Distribution
- Study Hours Analysis
- Attendance Distribution
- Sleep Hours Distribution
- Distraction Level Analysis
- Performance Class Distribution
- Correlation Heatmap

# Visualizations were created using:
- Histograms with KDE curves
- Box Plots
- Bar Charts
- Pie Charts
- Heatmaps

# 4️⃣ Machine Learning Model Building
Four classification models were trained and compared to predict student performance class:

# Models Trained
- Random Forest (n_estimators=200)
- Gradient Boosting
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

# Techniques Applied
- 80/20 Stratified Train-Test Split
- 5-Fold Stratified Cross-Validation
- GridSearchCV Hyperparameter Tuning
- StandardScaler for SVM & KNN

# Best Model: KNN — 63.6% Test Accuracy, AUC-ROC 0.5938

# 📊 Power BI Dashboard
An interactive dashboard was developed in Power BI to visualize key academic performance insights.

# Dashboard Features
- KPI Cards (Average Score, Performance Split, etc.)
- Study Habit vs Score Analysis
- Attendance & Sleep Pattern Visuals
- Distraction & Mobile Usage Trends
- Performance Class Breakdown
- Interactive Filters & Slicers

The dashboard enables users to explore student study patterns and performance trends dynamically.

# 📈 Key Results
The project revealed several valuable insights:
- Study quality & study efficiency are the strongest predictors of exam performance
- More study hours correlate with higher scores, but quality outweighs quantity
- Class attendance strongly amplifies the effectiveness of study time
- High distraction levels negatively impact academic outcomes
- Sleep duration of 7–8 hours aligns with better performance

# 💼 Recommendations
Based on the analysis:
- Encourage consistent, distraction-free study sessions over long unfocused hours
- Promote regular class attendance as an academic support strategy
- Highlight the importance of adequate sleep (7–8 hrs) for cognitive performance
- Use model outputs to flag at-risk students early for timely intervention
- Encourage structured revision schedules over last-minute study habits

# 📁 Project Structure
Student-Performance-Analysis/

│── Dataset/
│     └── Student_Performance.xlsx
│
│── Python/
│     └── Studentstudypattern_VS_Examperformance_analysis.ipynb
│
│── Dashboard/
│     └── reportstudent.pbix
│
│── Report/
│     └── StudentPerformanceReport.docx
│
└── README.md

# ▶️ How to Run
Clone the Repository
git clone https://github.com/ThrishaDSullal/Student-Performance-Analysis.git

Install Required Libraries
Install:!pip install pandas numpy matplotlib seaborn scikit-learn

# Steps
1. Open the Jupyter Notebook.
2. Run all cells for data cleaning, EDA, and model training.
3. Review model evaluation metrics and feature importance.
4. Open the Power BI dashboard (.pbix) to explore the interactive visualizations.

# 🎯 Project Outcome
This project demonstrates practical skills in:
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Machine Learning Classification
- Model Evaluation & Comparison
- Data Visualization
- Dashboard Development
- Data Storytelling

It reflects the complete workflow expected of a Data Analyst / Data Scientist and showcases the ability to transform raw survey data into actionable academic insights.

# Thrisha D S 🎓 MSc in Big Data Analytics

📧 Email: thrishadsullal@gmail.com
💼 LinkedIn: www.linkedin.com/in/ThrishaDS
🐙 GitHub: https://github.com/ThrishaDSullal
