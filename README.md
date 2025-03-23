# 🎟️ Redshift Ticket Sales Analysis (Google Colab Portfolio)

This project demonstrates how to connect to **Amazon Redshift Serverless** from a Google Colab notebook, run clean SQL-based analytics, and create interactive visualizations using Plotly.
([source](https://docs.aws.amazon.com/redshift/latest/dg/c_sampledb.html)).
## 🔍 Overview

We use the `tickit` sample dataset preloaded in Redshift to analyze event ticket sales. This project is ideal for showcasing:
- SQL analytics skills
- Cloud data warehouse integration (Redshift)
- Visualization and storytelling with Python

## 📌 Key Features

- 🔐 **Secure AWS connection** via Redshift Data API (boto3)
- 🧠 **SQL queries** executed directly from Python
- 📊 **Interactive charts** using Plotly (line + bar)
- ✅ Clean, production-ready Colab notebook

## 📊 Analysis Included

1. **Top Events by Revenue**
2. **Revenue Trend Over Time**
3. **Revenue by Event Category**

## 🚀 Tech Stack

- Amazon Redshift Serverless
- Python (Google Colab)
- Boto3 (Redshift Data API)
- Pandas
- Plotly

## 📁 Files

- `redshift_colab_portfolio.ipynb` – Main notebook (Colab-ready)
- `README.md` – This documentation

## 🧠 How to Run

1. Open notebook in [Google Colab](https://colab.research.google.com)
2. Install dependencies:
   ```python
   !pip install boto3 pandas plotly
   ```
3. Enter your AWS access keys (use IAM with RedshiftDataFullAccess)
4. Run each cell step-by-step

---

## ✅ Conclusion

This notebook demonstrates a complete, production-friendly workflow for data analysis using **Amazon Redshift Serverless**:

- 🔐 **Secure connection** using IAM-authenticated access via the Redshift Data API — no need for drivers or JDBC.
- 🧠 **SQL-based analytics**, leveraging Redshift’s performance with familiar query syntax.
- 📊 **Clean visualizations** using Plotly, turning raw data into interactive, professional insights.
- 🧱 **Serverless + Scalable**: No infrastructure to manage, perfect for modern cloud-native data projects.

---

Want to extend it? Add user segmentation, forecasting, or build a Streamlit app on top 💪
