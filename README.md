# Mortgage Repayment Calculator App

This is a simple **Mortgage Repayment Calculator** web application built using **Streamlit**. It allows users to input loan details such as amount, interest rate, and term, and it visualizes the breakdown of monthly payments into **principal** and **interest** over time.

**Live Demo**: [mortgage-calculatorapp-test.streamlit.app](https://mortgage-calculatorapp-test.streamlit.app/)

## About

This project was created by following the YouTube tutorial:  
[Mortgage Repayment Calculator by Streamlit App](https://www.youtube.com/watch?v=q9B1M-10sLs&ab_channel=DataPythonist) by **DataPythonist** to learn how to build interactive web apps using Streamlit.

## Features

- Interactive sidebar input for:
  - Loan amount
  - Annual interest rate
  - Loan term in years
- Calculation of monthly repayments
- Visualization of:
  - Monthly interest vs principal
  - Total payments over the term

## Tech Stack

- **Python**
- **Streamlit**
- **Pandas**
- **Plotly** (for interactive charts)

## Getting Started

To run this app locally:

```bash
git clone https://github.com/aselya9185/mortgage_calculator_app.git
cd mortgage_calculator_app
pip install -r requirements.txt
streamlit run app.py
