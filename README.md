# Task-1-big-data-analysis



This project demonstrates scalable big data analysis using **PySpark**, executed on **Google Colab**, and applied to real-world COVID-19 datasets from the [Johns Hopkins CSSE repository](https://github.com/CSSEGISandData/COVID-19).

---

##  Project Description

The notebook/script performs distributed data processing on a publicly available COVID-19 dataset to extract insights, such as:

- Total confirmed cases per country
- Total deaths per country
- Death rate calculations
- Scalable query execution using PySpark

This project is ideal for showcasing PySpark’s capabilities in big data analytics using a cloud environment with minimal setup.

---

##  Tools & Technologies

-  [Apache Spark](https://spark.apache.org/) (via PySpark)
-  [Google Colab](https://colab.research.google.com/)
-  Public COVID-19 dataset from Johns Hopkins CSSE
-  Python 3.x

---

## Dataset Source

We use the daily COVID-19 report from Johns Hopkins:

- **URL**: [07-01-2021.csv](https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_daily_reports/07-01-2021.csv)

---

## Sample Insights

| Country       | Total Confirmed | Total Deaths | Death Rate (%) |
|---------------|------------------|---------------|----------------|
| United States | 33,620,000       | 605,000       | ~1.80%         |
| Brazil        | 18,590,000       | 518,000       | ~2.79%         |
| India         | 30,450,000       | 400,000       | ~1.31%         |

> Death Rate = (Total Deaths / Total Confirmed) × 100

---

##  How to Run

### Option 1: Google Colab

1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Run all cells (PySpark installs automatically)
3. View analysis and outputs

### Option 2: Run Locally

```bash
# Install PySpark
pip install pyspark

# Run Python script
python covid_analysis.py

