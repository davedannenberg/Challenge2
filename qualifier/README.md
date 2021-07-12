# Loan Qualifier

This is a Python command-line interface application that allows users to see qualifying loans from lenders quickly and easily. The application works by that taking in a `daily_rate_sheet` of loan criteria from various loan providers, asks the user a number of questions to evaluate their loan eligibility, and then returns to them a list of qualifying loans.

---

## Technologies Utilized

This application utilizes Python 3.7 and the .csv file structure. Python libraries utlizied include questionary and fire, for collecting user input via command line interface.

---

## Installation Guide

Before running the application first install the following dependencies.

```python
  pip install fire
  pip install questionary
  pip install pytest
```
---

## Examples

The monthly debt ratio and the loan to value ratio are the two calculations enumerated and utilized in determining loan eligibility:

monthly_debt_ratio = int(monthly_debt_payment) / int(monthly_income)
loan_to_value_ratio = int(loan_amount) / int(home_value)
---

## Usage

To use the loan qualifier application simply clone the repository and run the **app.py** with:

```python
python app.py
```

---

## Contributors

The developer can be reached [here](mailto:ddannenberg1@gmail.com)

---

## License

MIT
