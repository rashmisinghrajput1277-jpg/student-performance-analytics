# student-performance-analytics
 Data Analytics project tracking student behavioral metrics using Scikit-Learn and Seaborn.”
# Student Performance Analytics & Forecasting Pipeline
### 🚀 ReadyNest Internship — Week 4 Data Analytics Project

An end-to-end data engineering and predictive machine learning pipeline designed to identify key behavioral indicators affecting student success parameters. By assessing variables like study hours, attendance rates, and sleep durations, this system dynamically visualizes data patterns and predicts academic outcomes using localized algorithmic engineering.

---

## 📊 Core Features & Marking Criteria Met

*   **Data Preprocessing & Integrity:** Cleaned and structured tracking matrix capturing 150 unique student profile entries with zero null fields and zero conflicting duplicates.
*   **Statistical Graphics Grid Dashboard:** A highly professional, multi-panel matrix plot using Matplotlib and Seaborn exploring behavioral trends.
*   **Interactive Controls (Dynamic Mode):** Integrated native `ipywidgets` inside the notebook environment to allow real-time filtering via sliders (Minimum Attendance, Maximum Study Hours) and visual theme dropdown switches.
*   **Predictive ML Infrastructure:** Trained and evaluated a Scikit-Learn `Random Forest Classifier` machine learning engine using a strict 80/20 train-test split strategy to predict whether a student passes or fails.

---

## 🛠️ Core Tech Stack Architecture

*   **Language Environment:** Python 3
*   **Data Engineering Frameworks:** Pandas, NumPy
*   **Data Visualization UI:** Matplotlib, Seaborn
*   **Dynamic Interface Layers:** IPyWidgets (Interactive Matrix Engine)
*   **Machine Learning Engine:** Scikit-Learn (Ensemble Methods)

---

## 📈 Key Analytical Insights Discovered

1. **The Attendance Threshold:** A critical academic survival threshold sits right around **80% attendance**. Students dropping below this marker face a sharply higher risk of falling into the failing cohort.
2. **Study Duration Variance:** Boxplot tracking demonstrates that passing student profiles consistently maintain a significantly higher median value of daily dedicated study hours (~6–8 hours).
3. **Model Complexity Justification:** Weak linear correlations across the basic correlation map confirmed that predicting student outcomes requires complex, non-linear machine learning models rather than simple baseline trends.

---

## 📂 Project Structure

```text
├── student-performance-analytics.ipynb   # Main Google Colab/Jupyter Notebook with code & dashboards
└── ReadyNest_Project_Insights_Report.pdf  # Executed project PDF report including final analytics summary
