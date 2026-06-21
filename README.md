# Olympic-Medal-Count-by-Country---Week1-AI-ML-intern-GNCIPL
The Olympic Medal Count by Country project is an AI/ML-based sports analytics project developed to analyze Olympic medal performances across countries, sports, and athlete characteristics.

Using **Python, Pandas, Matplotlib, Seaborn, and Scikit-Learn**, the project performs data preprocessing, exploratory data analysis (EDA), visualization, and machine learning to gain insights into Olympic performance patterns.

---

##  Objectives

* Analyze country-wise Olympic medal performance.
* Identify dominant sports and medal trends.
* Study athlete demographics and characteristics.
* Explore the influence of experience and previous achievements.
* Investigate the effect of injury history on performance.
* Perform correlation analysis among numerical features.
* Apply machine learning techniques for medal prediction.

---

##  Dataset Description

A synthetic dataset containing **100,000 athlete records** was created for this project.

### Features

| Feature          | Description                     |
| ---------------- | ------------------------------- |
| Athlete_ID       | Unique athlete identifier       |
| Country          | Country represented by athlete  |
| Year             | Olympic year                    |
| Sport            | Sport category                  |
| Event            | Specific event                  |
| Gender           | Male/Female                     |
| Age              | Athlete age                     |
| Height_cm        | Height in centimeters           |
| Weight_kg        | Weight in kilograms             |
| Experience_Years | Years of experience             |
| Previous_Medals  | Number of previously won medals |
| World_Rank       | Athlete world ranking           |
| Coach_Rating     | Coach performance score         |
| Injury_History   | Injury history (Yes/No)         |
| Medal            | Gold, Silver, Bronze            |
| Medal_Count      | Number of medals won            |

---

##  Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Random Forest Classifier

---

##  Project Workflow

```
Dataset Generation
        ↓
Data Cleaning
        ↓
Exploratory Data Analysis
        ↓
Data Visualization
        ↓
Feature Engineering
        ↓
Machine Learning Model
        ↓
Performance Evaluation
        ↓
Insights & Conclusions
```

---

##  Data Preprocessing

The following preprocessing steps were performed:

* Checked dataset dimensions and data types.
* Verified missing values.
* Removed duplicate records.
* Standardized categorical variables.
* Validated age, height, and weight ranges.
* Identified outliers using statistical methods.
* Prepared clean data for analysis and modeling.

---

##  Exploratory Data Analysis

Several visualizations were created to understand athlete and country performance patterns.

### Country-wise Analysis

* Top countries by medal count.
* Country-wise average world ranking.
* Country-wise coach rating analysis.

### Sport-wise Analysis

* Medal distribution by sport.
* Sport dominance comparison.

### Athlete Analysis

* Age distribution.
* Height and weight distribution.
* Gender participation analysis.

### Experience Analysis

* Experience years distribution.
* Experience vs medal count.
* Previous medals vs current performance.

### Injury Analysis

* Injury history distribution.
* Injury patterns across age groups.
* Injury analysis by gender.

### Coach Performance Analysis

* Coach rating distribution.
* Coach rating vs medal outcomes.

### Correlation Analysis

* Correlation heatmap among numerical features.
* Pairplot analysis for feature relationships.

---

##  Machine Learning

### Algorithm Used

* Random Forest Classifier

### Input Features

* Age
* Height_cm
* Weight_kg
* Experience_Years
* Previous_Medals
* World_Rank
* Coach_Rating
* Injury_History

### Target Variable

* Medal Type

---

##  Key Findings

* Countries such as USA and China consistently achieved higher medal counts.
* Athlete experience positively influenced performance.
* Previous medal history improved chances of future success.
* Better world rankings were associated with stronger outcomes.
* Coach ratings showed an impact on athlete performance.
* Injury history affected overall performance trends.

---
