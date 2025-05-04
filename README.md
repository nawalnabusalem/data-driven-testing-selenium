# 📘 Data-Driven Testing with Selenium and pytest
This project demonstrates data-driven testing using Python's pytest framework and Selenium WebDriver. The tests cover login functionality using multiple data sources:
- JSON.
- CSV.
- Excel.


# 🚀 Features
- Data-driven login tests from CSV, JSON, and Excel.
- pytest framework for structured and scalable testing
- Automated browser actions using Selenium WebDriver.
- Validates both positive and negative login scenarios.
- Clean and reusable test structure using pytest fixtures.


# 📁 Project Structure
  
<pre> 
data-driven-testing-selenium/
├── tests/
|   ├── __init__.py
│   ├── test_login_csv_data.py
│   ├── test_login_excel_data.py
│   └── test_login_json_data.py
├── data/
|   ├── __init__.py
│   ├── login_csv_data.csv
│   ├── login_excel_data.xlsx
│   └── login_json_data.json
├── requirements.txt
├── .gitignore
└── README.md
</pre>

# ⚙️ How to Run

1. Install Dependencies.
<pre> 
pip install -r requirements.txt
</pre>

2. For each test, update the driver path.

3. Run All Tests.
<pre> 
pytest tests/
</pre>

4. Run a Specific Test File.
<pre> 
pytest tests/test_login_json_data.py
</pre>


# 📎 Tools & Libraries

- [Selenium](https://pypi.org/project/selenium/)

- [pytest](https://pypi.org/project/pytest/)

- [openpyxl](https://pypi.org/project/openpyxl/) (for Excel support)
