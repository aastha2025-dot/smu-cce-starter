## Installation Instructions

This project is simple to run. Follow these steps in order.

1. Open the repository in GitHub Codespaces, or clone it to your computer:

```bash
git clone https://github.com/<your-username>/smu-cce-starter.git
cd smu-cce-starter
```

2. Install the required Python packages:

```bash
pip install -r requirements.txt
```

3. Open the `notebooks/` folder in VS Code.

4. Open one of the notebooks, such as `filings.ipynb` or `stock_price_ratings.ipynb`.

5. Run the cells from top to bottom. If you are using Jupyter, click the Run button for each cell.

6. You should see stock data, financial tables, news, or analyst information printed in the notebook output.

If you are using GitHub Codespaces, the environment is already set up for you. You only need to install the dependencies and run the notebooks.

---

## Code Walkthrough

This repository is a beginner-friendly financial data project built with Python notebooks.

### Main files and folders

- `notebooks/` — the main project code. These notebooks fetch live stock data.
- `requirements.txt` — lists the Python libraries needed to run the project.
- `lessons/` — course notes and setup instructions.
- `README.md` — project overview.

### What is inside `notebooks/`

- `filings.ipynb` — pulls company financial statements such as income, balance sheet, and cash flow data.
- `news.ipynb` — fetches recent news articles for a stock ticker.
- `stock_price_ratings.ipynb` — gets the current stock price and analyst ratings summary.

### How the application works

The project uses the `yfinance` library to get data from Yahoo Finance. A user picks a stock ticker (for example, `MU`), and the notebook creates a ticker object. The code then requests data such as:

- current price
- analyst recommendations
- company financial statements
- recent news

The notebook prints the results in a simple, readable format so the user can inspect the data. In short, the flow is:

```text
Choose a stock -> fetch data -> display results -> analyze the output
```

This is a simple example of how Python can turn live financial data into useful information for analysis.

---

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