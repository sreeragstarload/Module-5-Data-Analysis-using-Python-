# Module-5-Data-Analysis-using-Python-
“Social Media Engagement Analytics”

📊 Social Media Engagement Analytics Using Python

An end-to-end Exploratory Data Analysis (EDA), data cleaning, statistical profiling, and data visualization project analyzing **5,000 social media posts** across multiple platforms, content categories, devices, and demographics.

---

 ###📌 Project Overview
Social media platforms generate high volumes of user interaction metrics—likes, comments, shares, watch time, and impressions. This project processes and analyzes `social_media_engagement_5000.csv` using Python to uncover content performance patterns, audience behavior, and key engagement drivers.

##🎯 Objectives
1. **Data Setup & Cleaning:** Handle missing values, standardize categorical labels, validate interaction-to-impression ratios, and engineer features such as `hashtag_count` and `engagement_score`.
2. **Exploratory Data Analysis (EDA):** Evaluate distributions, correlations, and multi-dimensional group aggregations across post types, countries, and sentiments.
3. **Statistical Profiling:** Compute central tendency, dispersion, percentiles, skewness, and kurtosis across core engagement metrics.
4. **Data Visualization:** Build 13 static and interactive charts using **Matplotlib**, **Seaborn**, and **Plotly**.

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python 3.x
* **Data Manipulation:** `Pandas`, `NumPy`
* **Visualization:** `Matplotlib`, `Seaborn`, `Plotly`
* **Environment:** Jupyter Notebook / Google Colab

---

## 📂 Repository Structure
```text
├── module_5_assignment_social_media_engagement.ipynb   # Main Jupyter Notebook with code, plots & outputs
├── social_media_engagement_5000.csv                    # Raw dataset (5,000 records, 19 features)
├── Social_Media_Engagement_Summary.pdf                 # One-page executive summary report
└── README.md                                           # Project documentation

##🔍 Key Analytical Findings
1. Content & Category Performance
Post Types: Videos lead in average engagement rate (1.12%) and total engagement score (12,665 avg interactions), whereas Reels have the highest posting volume (1,283 posts) but a lower average engagement rate (0.78%).

Categories: Food posts achieve the highest average engagement rate (1.36%), followed by Tech (1.16%) and Lifestyle (1.09%). Music drives the highest raw interaction volume (12,789 avg score).

Geography: Brazil leads in engagement rate (1.54%), followed by Australia (1.32%). India records the highest average impressions (52,462).

2. User & Device Trends
Age Demographics: Users aged 25–34 generate the highest raw interaction volume (12,868 avg score), while the 45–54 age group achieves the highest engagement rate (1.21%).

Account Verification: Verified accounts achieve a 10.4% higher engagement rate (1.05%) compared to unverified accounts (0.95%).

Device & Timing: Mobile devices yield the longest watch time (4,088 sec) and highest engagement rate (1.12%). Tuesday generates the highest average reach (51,309 impressions).

3. Sentiment Insights
Negative Sentiment posts generate the highest average engagement rate (1.04%) and total interactions (12,731), while Neutral posts spark the highest average comment activity (1,528 comments).



