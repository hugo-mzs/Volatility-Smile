# 📈 Implied Volatility Skew Visualizer for Listed Companies

This Python project allows you to:

- Search for any **publicly listed company** by name, and get its ticker
- Retrieve its **option chain** using the **Alpaca Markets API**,
- Filter and analyze **call options** for a selected expiry,
- Automatically **fallback to the next available expiry** if none matches,
- Compute and plot the **implied volatility skew** across strike prices.

---

## 🚀 Features

- ✅ Company name to ticker resolution using Yahoo Finance
- 📅 User-defined expiry date input (in DD/MM/YYYY format)
- 🧠 Intelligent fallback to the next expiry if necessary
- 📊 Calculation of mid-price, implied volatilities, and greeks
- 📈 Skew visualization with Matplotlib
- 🧼 Clean Pandas DataFrame transformation from Alpaca’s nested JSON

---
## User Guide : 
Enter a company name: ex : Nvidia
Enter the european option's expiration date (DD/MM/YYYY): ex : 14/06/2025
✅ If the date entered is not among the expiry dates, the program will automatically be using the closest later expiry: ex :2025-06-20

## 🛠️ Technologies Used

- Python 3.12+
- `requests` – API communication
- `pandas` – data structuring
- `matplotlib` – plotting
- `datetime` – user input handling
- `alpaca-py` – option data retrieval from Alpaca Markets

---
