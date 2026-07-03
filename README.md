# Screen Time and User Engagement Analysis in r/julgueme

## Overview

This repository contains the source code for an undergraduate academic research project focused on analyzing user engagement and activity patterns within the Reddit community **r/julgueme**.

The study aims to investigate how users interact with content over time by analyzing publicly available Reddit data. The project applies data analysis and Natural Language Processing (NLP) techniques to identify engagement trends, participation frequency, and temporal activity patterns that may be associated with user behavior within the community.

This project is intended exclusively for academic research and does not collect any private user information.

---

## Research Objectives

The primary objectives of this project are to:

- Collect publicly available posts and comments from **r/julgueme**
- Analyze posting and commenting activity over time
- Measure community engagement patterns
- Identify peak activity periods
- Evaluate temporal interaction trends
- Generate statistical reports and visualizations
- Support research on digital behavior and online communities

---

## Research Questions

This research seeks to answer questions such as:

- When is the community most active?
- How does user engagement vary throughout the day and week?
- What are the posting and commenting trends over time?
- Are there recurring activity patterns within the community?
- What behavioral indicators can be inferred from public interaction data?

---

## Technologies

The project is developed using the following technologies:

- Python
- PRAW (Python Reddit API Wrapper)
- Pandas
- NumPy
- Matplotlib
- Plotly
- Scikit-learn
- Jupyter Notebook

---

## Project Structure

```text
reddit-screen-time-analysis/

├── data/
│   ├── raw/
│   ├── processed/
│   └── results/
│
├── notebooks/
│
├── src/
│   ├── collect.py
│   ├── preprocess.py
│   ├── analysis.py
│   ├── visualization.py
│   └── utils.py
│
├── docs/
│
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

---

## Data Collection

Data are collected exclusively through the official Reddit API.

The application retrieves only publicly available information, including:

- Submission titles
- Submission timestamps
- Comment timestamps
- Public engagement metrics (score, number of comments)
- Community activity metadata

No private, deleted, or restricted user information is collected.

---

## Analysis Methods

The project includes:

- Data collection through the Reddit API
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Time-series analysis
- User engagement analysis
- Statistical analysis
- Data visualization

---

## Expected Outputs

The project generates:

- Community activity timelines
- Daily and weekly engagement statistics
- Posting frequency reports
- Comment activity reports
- Visual dashboards and charts
- Statistical summaries

---

## Ethical Considerations

This project is conducted exclusively for academic research purposes.

Only publicly available Reddit content is analyzed.

No automated interaction with Reddit users occurs.

No personally identifiable information is intentionally collected, and all published results will present aggregated analyses.
