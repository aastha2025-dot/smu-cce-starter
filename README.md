## Installation Instructions

This project is a beginner-friendly Python starter for working with financial data in Jupyter notebooks.

Follow these steps in the terminal:

```bash
cd smu-cce-starter
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```

What this does:
- creates a virtual environment so your project packages stay isolated
- installs the required libraries from `requirements.txt`
- opens Jupyter in your browser

Then open the `notebooks/` folder and run the notebooks to explore the examples.

## Code Walkthrough

This repository is a small learning project for financial data analysis.

Main folders and files:
- `notebooks/` - the main working files; these contain the example code
- `lessons/` - lesson notes and course instructions
- `requirements.txt` - the Python packages needed for the project
- `README.md` - project overview

Important notebooks:
- `filings.ipynb` - looks up SEC filing information for a company using Yahoo Finance data
- `news.ipynb` - fetches recent company news and prints the headlines
- `stock_price_ratings.ipynb` - gets stock price data and analyst rating summaries

How the project works from start to finish:
1. You install the required Python packages.
2. You open Jupyter Notebook.
3. You open one of the notebooks in `notebooks/`.
4. The notebook imports `yfinance` and other libraries.
5. It asks for a stock ticker such as `GOOG` or `MU`.
6. It pulls live market and company information from Yahoo Finance.
7. You view the results in the notebook and can modify the code for your own analysis.

This repo is meant to help you learn how to work with real financial data before building a cloud-based app.

 # Cloud Computing for Economics: Starter Repo 

  This repository contains the starter code and lesson materials for building a Python financial-data application and deploying it to AWS.

  Students will use GitHub Codespaces, Python, Jupyter notebooks, Streamlit, Git, and AWS CloudFormation.

  ## Learning outcomes

  By the end of the course, you will be able to:

   1.  Build and deploy an analytics application with a simple Front End / back-end (using AI)
   2.  Host and share the application on a cloud platform (e.g., AWS EC2 or similar) so that others can access it securely over the web
   3.  Integrate data sources and APIs into the app to enable interactive, real-time analytics
   4.  Apply cloud architecture best practices, ensuring the app demonstrates scalability, performance efficiency, and basic security
   5.  Showcase your work on GitHub as part of a personal portfolio, demonstrating practical cloud and analytics skills through a shareable, explorable repository

  
  ## Repository structure

  ```text
  .
  ├── lessons/          # Step-by-step course instructions
  ├── notebooks/        # Starter financial-data notebooks
  ├── requirements.txt  # Python dependencies
  └── README.md         # Course overview