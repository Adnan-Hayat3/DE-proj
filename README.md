# Reddit Data Pipeline — Batch ETL with Airflow

## Overview
This project builds a batch ETL pipeline that extracts Reddit posts from a selected subreddit, processes the data through Bronze, Silver, and Gold layers, and automates the workflow using Apache Airflow.  
The pipeline simulates a cloud data engineering setup locally using Python, Airflow, and local file storage.


## Tech Stack
- Python
- Apache Airflow (Local Setup)
- Pandas
- Reddit API (praw)
- SQLite (optional for queries)
- Matplotlib / Seaborn (for visualization)


## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/DE-proj.git
   cd DE-proj

2. Install required packages and navigate to the project:
   ```bash
   pip install -r requirements.txt

3. Setup Airflow:
   ```bash
   airflow db init
   airflow scheduler
   airflow webserver
  
5. Trigger the DAG from the Airflow UI to start the ETL pipeline.
