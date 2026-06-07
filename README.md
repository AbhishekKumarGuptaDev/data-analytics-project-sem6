# 🗳️ India General Election Analysis Dashboard

### Power BI | Python | Data Analytics | Business Intelligence

An end-to-end Election Analytics and Business Intelligence project built using Python, Google Colab, and Power BI to analyze historical Indian General Election data and generate interactive insights on voter participation, political competition, and party performance.

---

## 📌 Project Overview

This project transforms raw election records into meaningful analytical dashboards.

The dashboard helps analyze:

* Voter turnout trends
* Party-wise performance
* Election competitiveness
* Constituency-level insights
* Historical trend analysis
* Geographic distribution

---

## 🚀 Dashboard Preview

### Executive Dashboard

<img width="100%" src="images/dashboards/executive_dashboard.png">

---

### Risk Analysis Dashboard

<img width="100%" src="images/dashboards/risk_analysis.png">

---

### Voter Turnout Dashboard

<img width="100%" src="images/dashboards/turnout_analysis.png">

---

### Party Analysis Dashboard

<img width="100%" src="images/dashboards/party_analysis.png">

---

# 🎯 Objectives

* Analyze election participation trends
* Study voter turnout patterns
* Compare party performance
* Detect high-risk constituencies
* Build executive dashboards
* Apply Business Intelligence techniques

---

# 📊 Dashboard Modules

## 1. India General Election Analysis

Features:

* Total Votes
* Average Turnout
* Highest Margin
* Total Constituencies
* Total Political Parties

Visuals:

* KPI Cards
* Trend Analysis
* Geographic Map
* Constituency Comparison

---

## 2. Risk Analysis

Risk Categories:

| Category  | Rule        |
| --------- | ----------- |
| High Risk | Margin < 5  |
| Moderate  | Margin 5–15 |
| Safe      | Margin > 15 |

Visuals:

* Pie Chart
* Risk Distribution
* Detailed Constituency Table

---

## 3. Voter Turnout Analysis

Visuals:

* Turnout Trend
* State Comparison
* Scatter Analysis

Insights:

* Historical turnout growth
* State-wise participation

---

## 4. Party Analysis

Visuals:

* Treemap
* Vote Distribution
* Constituency Performance

Insights:

* Party dominance
* Regional influence

---

# 🛠️ Tech Stack

| Technology   | Purpose         |
| ------------ | --------------- |
| Python       | Data Processing |
| Pandas       | Cleaning        |
| Google Colab | Development     |
| Power BI     | Dashboard       |
| DAX          | Measures        |
| CSV          | Dataset         |

---

# 📂 Repository Structure

```bash
India-General-Election-Analysis/

├── Datasets/
│   ├── final_processed_election_data.csv
│   └── working_data_IGE.csv
│
├── Notebook/
│   └── IGE.ipynb
│
├── Power BI/
│   └── IGE_Analysis.pbix
│
├── images/
│    ├──dashboards/
│     ├── executive_dashboard.png
│     ├── risk_analysis.png
│     ├── turnout_analysis.png
│     └── party_analysis.png
│    └── other images
│
└── README.md
 
```

---

# 📈 Key Metrics

* Total Votes
* Avg Turnout
* Victory Margin
* Party Count
* Constituency Count
* Risk Category

---

# 🧠 Analytical Approach

This project introduces a risk-based election analytics framework:

* Lower margin → Higher electoral risk
* Higher turnout → Stronger voter engagement
* Historical comparison → Trend discovery

---

# 🔍 Sample DAX

```DAX
High_Risk_Seats =
CALCULATE(
COUNT(Pc_name),
Victory_Risk="High Risk"
)
```

---

# ▶️ Run Project

Clone Repository:

```bash
git clone https://github.com/AbhishekKumarGuptaDev/India-General-Election-Analysis.git
```

Open Notebook:

```bash
IGE.ipynb
```

Open Dashboard:

```bash
IGE_Analysis.pbix
```

---

# 📚 Skills Demonstrated

* Data Cleaning
* EDA
* Dashboard Design
* DAX
* Business Intelligence
* Data Storytelling

---

# 🌟 Future Improvements

* ML-Based Prediction
* Real-Time Election Data
* Sentiment Analysis
* Power BI Service Deployment

---

# 👨‍💻 Author

**Abhishek Kumar Gupta**

B.Tech CSE (AI & ML)

Data Analytics • Machine Learning • Power BI

---

⭐ If you liked the project, give it a star.

