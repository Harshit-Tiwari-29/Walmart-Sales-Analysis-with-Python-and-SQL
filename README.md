## Walmart Sales Analysis using Python & SQL

This project focuses on analyzing Walmart sales data by integrating Python-based data processing with SQL-driven analytics. The objective was to build an end-to-end data analysis pipeline—from raw data extraction to actionable business insights—using industry-standard tools.

The analysis uncovers revenue patterns, branch performance gaps, and time-based sales trends to support data-driven decision-making.

🛠️ Tech Stack

Programming Language: Python

Libraries: Pandas, NumPy, SQLAlchemy

Database: PostgreSQL

Data Source: Kaggle (Automated via Kaggle API)

Query Language: SQL

Environment: Jupyter Notebook

```
📂 Project Structure
├── project.ipynb                     # Data preprocessing & Python-SQL integration
├── Walmart sales data analysis.sql   # Advanced SQL queries for analysis
├── Walmart.csv                       # Raw dataset
├── Walmart_clean_data.csv            # Cleaned dataset
├── requirements.txt                  # Python dependencies
└── README.md
```

🔄 Workflow

Data Extraction

Automated dataset retrieval using the Kaggle API

Loaded ~10,000 sales records

Data Preprocessing (Python)

Removed duplicate records

Handled missing values

Normalized inconsistent column formats

Generated a clean, analysis-ready dataset using Pandas

Database Integration

Loaded cleaned data into PostgreSQL

Connected Python and SQL workflows using SQLAlchemy

SQL-Based Analysis

Revenue distribution analysis

Branch-wise performance comparison

Sales trend analysis by daily shifts (morning, afternoon, evening)

📊 Key Insights

Identified a 62% revenue decline in the lowest-performing branches

Observed peak activity of 4,636 transactions during afternoon sales shifts

Highlighted underperforming branches requiring strategic intervention

Revealed clear time-based sales patterns useful for workforce and inventory planning

▶️ How to Run the Project

Clone the repository
```
git clone https://github.com/your-username/walmart-sales-analysis.git
```

Install dependencies
```
pip install -r requirements.txt
```

Configure PostgreSQL credentials in the notebook

Run project.ipynb to execute the full pipeline

Use Walmart sales data analysis.sql for direct SQL-based insights

📈 Outcomes

Built a scalable Python–SQL analytics pipeline

Demonstrated strong data engineering + analytical SQL skills

Delivered business-relevant insights from raw retail sales data
