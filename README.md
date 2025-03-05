# 📊 Impact of Remote Work on Mental Health

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA) on the impact of remote work on mental health**. It analyzes survey data to identify patterns in work-life balance, stress levels, job satisfaction, and overall mental well-being. The goal is to gain insights into how remote work affects employees' productivity and mental health, which can be useful for organizations and policymakers.

## 📂 Dataset Information

- **Dataset Name**: `Impact_of_Remote_Work_on_Mental_Health.csv`
- **Source**: Survey data from Kaggle
- **Features Included**:
  - `Work_From_Home`: Indicates whether the respondent works remotely (Yes/No)
  - `Hours_Worked_Per_Week`: Number of hours worked per week
  - `Stress_Level`: Self-reported stress level on a scale of 1-10
  - `Work_Life_Balance`: Rating of work-life balance on a scale of 1-10
  - `Mental_Health_Effect`: Whether remote work has positively or negatively affected mental health
  - `Productivity_Level`: Self-assessed productivity rating on a scale of 1-10
  - `Job_Satisfaction`: Overall job satisfaction on a scale of 1-10

## 🛠️ Installation & Setup

To run this project, follow these steps:

1. **Clone the repository**
   ```sh
   git clone https://github.com/Nikita-NA/Impact_Of_Remote_Work.git
   cd Impact_Of_Remote_Work
   ```
2. **Install dependencies**
   ```sh
   pip install pandas numpy matplotlib seaborn
   ```
3. **Run the Jupyter Notebook or Google Colab**
   - Open `Impact_of_remote_work.ipynb` in Google Colab or Jupyter Notebook.

## 🔍 Exploratory Data Analysis

### What is EDA?

Exploratory Data Analysis (EDA) involves summarizing key characteristics of a dataset through visualization and statistical analysis. It helps in understanding trends, identifying outliers, and preparing data for modeling.

### What has been done in this project?

The dataset was preprocessed by handling missing values, converting categorical variables, and removing duplicates and anomalies. Key statistical measures such as mean, median, and standard deviation were computed, while boxplots and the Interquartile Range (IQR) method helped detect and manage outliers in working hours, stress levels, and productivity. Various visualizations, including histograms, bar charts, heatmaps, and scatter plots, were used to analyze work hours, stress, job satisfaction, and correlations between these factors.

### Key Insights

- Employees working long hours tend to have higher stress levels and lower job satisfaction.
- Work-life balance positively correlates with mental well-being and productivity.
- Many respondents reported that remote work has a mixed impact on mental health, depending on their working conditions and personal circumstances.

## 📊 Results & Findings

- Successfully analyzed the impact of remote work on mental health using statistical and visual techniques.
- Identified strong correlations between **working hours, stress levels, and productivity**.
- Boxplots and IQR analysis helped detect outliers in working hours and stress levels.
- Correlation heatmaps revealed significant relationships between work-life balance and mental well-being.

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit pull requests.

