\# Predicting Price Moves with News Sentiment



\## Overview



This project explores the relationship between financial news sentiment and stock market behavior using the Financial News and Stock Price Integration Dataset (FNSPID).



The objective is to analyze financial news headlines, identify patterns in news publishing activity, extract important keywords and themes using Natural Language Processing (NLP), and prepare the foundation for correlating sentiment with stock price movements.



This repository contains the implementation for \*\*Task 1: Git, GitHub, and Exploratory Data Analysis (EDA)\*\* of the Nova Financial Solutions challenge.



\---



\# Business Objective



Nova Financial Solutions aims to improve predictive analytics capabilities by leveraging financial news sentiment as a signal for stock market movements.



This project focuses on:



\- Understanding the structure and behavior of financial news data

\- Identifying trends in publishing activity

\- Extracting recurring financial themes and keywords

\- Preparing the dataset for future sentiment analysis and correlation modeling



The final goal is to support data-driven investment strategies using financial news signals.



\---



\# Dataset



The project uses the \*\*Financial News and Stock Price Integration Dataset (FNSPID)\*\*.



\### Main Dataset

`raw\_analyst\_ratings.csv`



\### Key Features



| Column | Description |

|--------|-------------|

| headline | Financial news headline |

| url | Link to article |

| publisher | Publisher or author |

| date | Publication timestamp |

| stock | Stock ticker symbol |



\---



\# Project Structure



```text

news-sentiment-analysis/



├── .github/

│   └── workflows/

│       └── unittests.yml



├── data/

│   └── raw/

│       └── raw\_analyst\_ratings.csv



├── notebooks/

│   └── task1\_eda.ipynb



├── src/



├── tests/



├── scripts/



├── requirements.txt



├── .gitignore



└── README.md

```



\---



\# Technologies Used



\- Python

\- Pandas

\- NumPy

\- Matplotlib

\- Seaborn

\- Scikit-learn

\- NLTK

\- WordCloud

\- Jupyter Notebook

\- Git \& GitHub

\- GitHub Actions (CI/CD)



\---



\# Task 1 Objectives



The following analyses were completed:



\## 1. Descriptive Statistics

\- Headline length distribution

\- Missing value inspection

\- Dataset structure analysis



\## 2. Publisher Analysis

\- Most active publishers

\- Publisher contribution patterns

\- Organizational activity trends



\## 3. Time Series Analysis

\- News publication frequency over time

\- Daily news volume trends

\- Publishing hour analysis



\## 4. NLP / Topic Analysis

\- TF-IDF keyword extraction

\- Common financial themes

\- Word cloud visualization



\---



\# Key Findings



\- Financial headlines are generally short and optimized for rapid information delivery.

\- A small number of publishers dominate financial news production.

\- News publishing activity shows strong temporal concentration during trading-related hours.

\- Common themes include earnings reports, analyst upgrades, price targets, and corporate announcements.



\---



\# Setup Instructions



\## Clone Repository



```bash

git clone https://github.com/YOUR\_USERNAME/news-sentiment-analysis.git

```



\## Navigate to Project



```bash

cd news-sentiment-analysis

```



\## Create Virtual Environment



\### Windows



```bash

python -m venv venv

venv\\Scripts\\activate

```



\### Mac/Linux



```bash

python3 -m venv venv

source venv/bin/activate

```



\## Install Dependencies



```bash

pip install -r requirements.txt

```



\## Launch Jupyter Notebook



```bash

jupyter notebook

```



\---



\# Visualizations Included



The notebook includes multiple visualizations, including:



\- Headline length distribution

\- Top publishers bar chart

\- Daily news volume trends

\- Publishing frequency by hour

\- Word cloud of common keywords



\---



\# Future Work



Future tasks will include:



\- Sentiment analysis using NLP techniques

\- Technical indicator computation

\- Correlation analysis between sentiment and stock returns

\- Predictive modeling for investment insights





