# 🧠 Python Notebooks for AI, ML & ETL

A curated collection of Jupyter notebooks for hands‑on exploration of AI API calls, machine learning algorithms, ETL pipelines, and integrations with external APIs and cloud databases.

This repository includes interactive Python notebooks covering a broad range of data‑centric use cases — from fetching and transforming data to training models and making AI calls — all designed to be educational, reusable, and practical.

# Highlights
Google_Gemini_Stock_Analyst_Agent.ipynb – A notebook Flask app which uses API to feed Yahoo Finance data into Google Gemini for a Stock Market Analyst App. Calls Google Gemeni and Yahoo Finance via API  Get a Google Gemini API Key here ant try it out!: https://aistudio.google.com/app/api-keys.

outlier_selection_mahalanobis.ipynb – Multi Dimensional outlier detection algorithm using Mahalanobis distance method.


# For Researchers interested in Collaboration
See the Ukraine Behavioral Data USFCA file for Data and Codebooks for the USFCA CEGA Study Cognitive and Social Effects of War https://repository.usfca.edu/thes/1580/

# Repository 
📁 Repository Structure

This repo is organized mainly as a set of .ipynb notebooks, each illustrating a unique task or technique. Notebooks include but are not limited to:

📌 ETL & API Integrations

These notebooks demonstrate how to extract, transform, and load data from APIs or other data sources:

API_ETL_HOUSING_URBAN_DEVELOPMENT.ipynb – ETL with a government housing dataset.

US_Census_API_ETL.ipynb – Fetch and preprocess U.S. Census data.

FTP_download.ipynb – Automate downloading files via FTP.

WebScraper.ipynb – Web scraping and ETL basics.



🤖 AI API Calls

Notebooks to interact with various AI and LLM services:

OpenAI_call.ipynb – Making AI calls with the OpenAI API.

Google_Gemini_API_Call.ipynb & Google_Gemini_Stock_Analyst_Agent.ipynb – Integrate with Google Gemini AI.

Groq_AI_Call.ipynb – Making AI calls to Groq API.

My_AI.ipynb & GAME_AI.ipynb – AI testing.

📊 Machine Learning & Analytics

Examples demonstrating ML algorithms, statistical analysis, and forecasting:

ARIMA_matplotlib.ipynb / time-series-arima.ipynb – Time series modeling & forecasting with ARIMA.

outlier_selection_mahalanobis.ipynb – Outlier detection using Mahalanobis distance.

Chronbachs Alpha with Pandas.ipynb – Statistical reliability analysis.

Factor Analysis with Factor_Analyzer_and_Matplotlib.ipynb – Dimensionality reduction and factor analysis.

🧩 Cloud & Database Integrations

Notebooks showing connections to cloud platforms or databases:

Snowflake_ETL.ipynb – Extract/load data with Snowflake.

Snowpark_Connection.ipynb – Connect to Snowpark and run queries.

🛠 Utility Notebooks

Other helpful utilities and demos:

PDFPlumber.ipynb / xyPdfparser.ipynb – Extracting text from PDFs.

Dash_Qualtrics_API.ipynb – Dash dashboard with Qualtrics API integration.

Flask_App_API_Guide_Stock_Data.ipynb – A Flask API app guide for stock data.

FIPS2.ipynb – Working with FIPS codes.

🔍 Key Features
🛠 Modular Learning

Each notebook demonstrates a specific topic in isolation — ETL workflows, API calls, ML modeling, cloud integration, or analytical techniques — making this repo suitable for learning, experimentation, and real‑world prototyping.

🔄 Hands‑on Examples

The notebooks include runnable code — ideal for those who want to study workflows such as:

Calling AI/LLM APIs

Connecting to cloud databases

Building ETL pipelines from APIs

Visualizing results

Basic ML tasks with common Python libraries

📚 No Vendor Lock‑in

Examples use multiple platforms and APIs (e.g., OpenAI, Google services, Snowflake), providing a range of practical techniques for modern data workflows.

🚀 Getting Started

Clone the repository

git clone https://github.com/diagonalai/Python_notebooks_AI_ML_ETL.git
cd Python_notebooks_AI_ML_ETL

Install dependencies
Most notebooks rely on standard Python data and ML packages such as:

pip install pandas numpy matplotlib scikit-learn requests jupyter

Add API SDKs you need (e.g., openai, google‑gemini, snowflake‑python‑connector).

Open a Notebook
Launch Jupyter Notebook or JupyterLab to explore, modify, or run the examples interactively:

jupyter lab
📦 Requirements

To run the notebooks you typically need:

Python 3.8+

Jupyter Notebook or JupyterLab

Libraries such as pandas, NumPy, scikit‑learn, matplotlib

API credentials for services like OpenAI, Google Gemini, Snowflake, etc.

🤝 Contributing

Contributions are welcome! You could help by:

Adding new notebooks covering more ML/AI/ETL scenarios

Improving documentation within notebooks

Providing robust error handling, unit tests, or environment configs
