# 📊 Product Analytics Dashboard + A/B Testing

A full-cycle analytics project that simulates a digital product's user journey, builds a robust SQL-backed dashboard, and integrates a custom A/B testing module — showcasing end-to-end BI & data science capabilities.

---

## 🚀 Objective

To design and build a portfolio-grade analytics system that:
- Tracks product performance metrics (DAU, Retention, Churn, Conversion)
- Analyzes user engagement using SQL & Power BI
- Runs and interprets A/B tests with Python and statistical methods
- Demonstrates data pipeline design and deployment on AWS

---

## 🧰 Tech Stack

| Layer        | Tools Used                         |
|-------------|------------------------------------|
| Data Gen    | Python, Pandas                     |
| Storage     | PostgreSQL (local & AWS RDS)       |
| ETL         | Python, SQLAlchemy, psycopg2       |
| Analytics   | SQL, DBT (optional)                |
| BI & Viz    | Power BI / Tableau                 |
| Stats       | Python (`scipy`, `matplotlib`)     |
| Cloud       | AWS S3, RDS                        |
| Docs        | Notion, GitHub, Markdown           |

---

## 📂 Project Structure

```
product-analytics-dashboard/
├── data/               # Simulated datasets
├── sql/                # Queries for metrics and analysis
├── python/             # Scripts for data gen, A/B test module
├── dashboard/          # Power BI or Tableau files & screenshots
├── docs/               # ERD, slides, and README assets
├── README.md           # You're here!
└── requirements.txt    # Python dependencies
```

---

## 📈 Key Metrics Tracked

- 📆 Daily/Weekly/Monthly Active Users (DAU/WAU/MAU)
- 📉 Retention & Churn Analysis
- 🧭 Feature Usage Heatmaps
- 🔁 Conversion Funnels
- 🧪 A/B Test Reports (with statistical significance)

---

## 🧪 A/B Testing Engine

Built with Python to:
- Simulate control & treatment groups
- Calculate p-values, power, and confidence intervals
- Visualize outcome distributions
- Deliver actionable experiment insights

```python
evaluate_ab(dataframe)
# Output: lift %, p-value, significant = True/False
```

---

## 📊 Sample Dashboards

![Sample Dashboard Screenshot](dashboard/screenshots/sample_dashboard.png)

> Includes filters, KPIs, trend lines, retention curves, and cohort analysis.

---

## 🌩️ Cloud Deployment (Optional)

- Host database on **AWS RDS**
- Store data snapshots on **AWS S3**
- Future: Integrate with **Streamlit UI** for live demo

---

## 📖 How to Run Locally

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/product-analytics-dashboard.git
   cd product-analytics-dashboard
   ```

2. Set up your environment:
   ```bash
   pip install -r requirements.txt
   ```

3. Generate data:
   ```bash
   python python/simulate_data.py
   ```

4. Run SQL queries in your PostgreSQL setup

5. Open the Power BI / Tableau file to explore the dashboard

---

## 🎯 Outcomes & Learnings

- Built SQL logic from scratch to model real product usage
- Designed BI dashboards focused on business impact
- Learned and applied hypothesis testing rigorously
- Integrated cloud services for scalable architecture

---

## 🤝 Let's Connect!

📧 [ashish.t@example.com](mailto:ashish.t@example.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/ashtiw/)  
🐙 GitHub: [@ashtiw](https://github.com/ashtiw)

---

## ⭐ Bonus Features To Add

- Streamlit-based A/B testing interface
- Automated dashboard refresh
- Real-time metrics with Kinesis (stretch goal)

---

## 📌 License

This project is open-sourced for educational and demonstration purposes.
