# Python-Projects
A comprehensive set of Python projects ranging from basic exercises to full applications. Perfect for students, self-learners, and anyone looking to master Python through hands-on experience.

# 🏦 Python Bank Account Management System
A simple Bank Account Management System built in Python. This program allows users to create and manage bank accounts, perform transactions (deposit, withdrawal, transfer), view transaction history, and generate summary reports.

It uses file handling with Pickle to persist account and transaction data, and includes error handling, interactive menus, and NumPy for transaction statistics.

# ✨ Features
✅ Account Management

Create new accounts (auto-generated account number)

View account details (name, account number, type, balance)

✅ Transactions

Deposit money

Withdraw money (with balance check)

Transfer money between accounts

✅ File Handling

Saves account details & transaction history using pickle

Loads saved data when program starts

Appends new transactions without overwriting previous data

✅ Reports & History

View transaction history (date, type, amount)

Summary statistics using NumPy (total deposits, withdrawals, average transaction)

✅ User Interaction

Interactive menu-driven interface

Smooth navigation with loops & conditions

✅ Error Handling

Input validation for positive amounts

Prevent withdrawal beyond available balance

Handle invalid account numbers

✅ Optional Bonus (if implemented)

User login with username & password

Use of lambda functions for quick calculations

# 🛠 Technologies Used
Python 3.x

Pickle (for saving/loading account data)

NumPy (for summary statistics)

datetime (for transaction timestamps)

# 📂 Project Structure
bash
Copy
Edit
bank_management/
│
├── bank_system.ipynb    # Main Jupyter Notebook
├── accounts.pkl         # Pickle file storing account data
├── transactions.pkl     # Pickle file storing transaction history
└── README.md            # Project documentation
# 🚀 How to Run
1️⃣ Clone the Repository
git clone https://github.com/your-username/bank-account-management.git
cd bank-account-management

2️⃣ Install Requirements (NumPy)
pip install numpy

3️⃣ Run the Notebook
Open bank_system.ipynb in Jupyter Notebook and run all cells.

# 🧑‍💻 Usage
When you run the program, you’ll see an interactive menu:

==== Bank Account Management ====
1. Open a New Account
2. View Account Details
3. Deposit Money
4. Withdraw Money
5. Transfer Money
6. View Transaction History
7. Exit
Enter your choice:
Follow the prompts to create accounts, perform transactions, or view reports.

# 📊 Example Output
✅ Creating a new account:

Enter account holder's name: Alice
Account type (savings/current): savings
Initial balance: 5000
✅ Account created successfully! Your Account Number is 1001
✅ Depositing money:

Enter account number: 1001
Enter amount to deposit: 2000
✅ Deposit successful! New balance: 7000
✅ Viewing transaction history:

Date        | Transaction | Amount
2025-07-26  | Deposit     | 2000
2025-07-26  | Withdraw    | 500

# 📌 Future Improvements
Implement a login system for multiple users

Add a GUI version using Tkinter or PyQt

Support for interest calculation

# 🤝 Contributing
Feel free to fork this repository and submit pull requests with improvements!

# 📝 License
This project is for educational purposes and is free to use.

#######################################################################################

# 🎬 IMDB Movie Analysis
📌 Objective
As a data analyst intern at IMDb, the goal of this project is to explore and analyze the IMDb Movies dataset to gain insights into movie trends, popular genres, and key factors that influence a movie's success. This involves answering specific business questions through data wrangling, visualization, and statistical analysis using Python.

🧰 Tools and Libraries
The following Python libraries are used in this analysis:

Pandas – For data manipulation and analysis

NumPy – For numerical operations

Matplotlib – For data visualization

Seaborn – For advanced statistical plotting

Warnings & OS – For clean output and file handling

# 📂 Dataset
Source: IMDb Dataset (Google Drive)
The dataset contains information on a wide range of movies, including attributes like title, genre, rating, votes, budget, revenue, and more.

Each row represents a unique movie.
Each column contains specific attributes related to that movie.

✅ Tasks & Analysis Workflow
1. 📦 Project Setup and Data Loading
Load the dataset

Understand the structure using .shape and .head()

2. 🔍 Data Overview and Basic Exploration
Use .info() and .describe() to get initial insights

Identify potential data quality issues

3. 🧹 Data Cleaning
Handle missing values and data type conversions

Detect and treat outliers

4. 📊 Univariate Analysis
Histogram of movie runtimes

Bar chart of most frequent genres

5. 🔗 Bivariate Analysis
Scatter plot of runtime vs. rating

Box plot of ratings by genre

Correlation between votes, budget, and revenue

6. 🎭 Genre-Specific Analysis
Identify genres with highest average rating

Analyze how genre popularity changes over time

7. 📆 Year & Trend Analysis
Trends in average ratings over years

Movie release counts by year

8. 📉 Multivariate Analysis
Popular genres by decade

Heatmap or pairplot between budget, revenue, ratings

Analysis of genre and year-wise rating patterns

9. 🧠 Insights and Summary
Key Questions:
What are three major insights you discovered about movie trends, genres, or ratings?

What other questions could be asked or what additional data would improve the analysis?

# 📈 Sample Outputs
📉 "Drama and Biography genres have the highest average IMDb ratings."

🎥 "Action and Sci-Fi genres have surged in popularity since the 2000s."

💰 "Movies with higher budgets tend to receive more votes, but not necessarily higher ratings."

# 📎 Submission Guidelines
Submit the final version as a Jupyter Notebook (.ipynb) via GitHub.

Ensure the notebook is well-commented with clear logic and visualizations.

Include sample outputs and conclusions in markdown cells.

Share only the GitHub repository link.

# 📬 Author
Role: Data Analyst Intern
Project: IMDb Movie Analysis
Organization: IMDb (Fictional Internship Scenario)

#######################################################################################

# 🛒 Super Market Billing System

A simple Python-based billing system for a supermarket, built using Jupyter Notebook. This project simulates a point-of-sale (POS) experience where customers can select items from a predefined menu and receive a bill based on their choices.

## 📌 Features

- Predefined supermarket inventory with 5 common items
- Price calculation based on quantity
- User-friendly prompts via console (text input)
- Simple, modular Python code using lists and dictionaries
- Easily extendable to include stock management, discounts, categories, and more

## 🧾 Sample Menu
menu = [
    {"sr_no": 1, "name": "Whole Milk (1 Gallon)", "price": 3.49},
    {"sr_no": 2, "name": "White Bread (Loaf)", "price": 2.49},
    {"sr_no": 3, "name": "Brown Eggs (Dozen)", "price": 3.29},
    {"sr_no": 4, "name": "Chicken Breast (per lb)", "price": 5.29},
    {"sr_no": 5, "name": "Fuji Apples (per lb)", "price": 1.49}
]

# 📊 Customer Sentiment Analysis – iPhone 15 (128GB) Flipkart Reviews

## 📌 Overview
This project analyzes **300 customer reviews** for the iPhone 15 (128GB) model from **Flipkart**, applying text cleaning, sentiment analysis, and insight generation.  
The goal is to understand customer sentiment trends, identify recurring issues, and suggest actionable improvements.

---

## 📂 Data Collection & Cleaning
- **Source**: Product review pages from Flipkart (iPhone 15 – 128GB model).
- **Scraping Tools**: Python + Selenium for automated data extraction.
- **Fields Collected**:
  - `username`
  - `review_text`
  - `rating`
- **Cleaning Steps**:
  - Removed special characters and emojis from review text.
  - Converted ratings to numeric type.
  - Handled missing values (none in this dataset).
  - Ensured all columns had equal lengths.

---

## 📈 Sentiment Analysis
- **Library Used**: [TextBlob](https://textblob.readthedocs.io/en/dev/)
- **Metrics**:
  - **Polarity**: Sentiment score from `-1` (negative) to `+1` (positive).
  - **Subjectivity**: Score from `0` (objective) to `1` (subjective/opinion-based).

**Results Summary**:
- **Rating Distribution**:
  - ⭐⭐⭐⭐⭐ – Majority (strongly positive sentiment)
  - ⭐⭐⭐⭐ – Moderate share (minor issues)
  - ⭐⭐⭐ or less – Small share (battery, heating, refresh rate complaints)
- **Average Polarity**: High positive (~0.6–1.0 for most reviews)
- **Average Subjectivity**: High (~0.7–1.0, opinion-heavy)

---

## 🔍 Key Insights
**Positive Highlights**:
- **Camera quality** is the most praised feature (photos & video).
- **Premium, lightweight design** with good in-hand feel.
- Smooth, lag-free **performance** (A16 Bionic).
- Display brightness and **Dynamic Island** appreciated.
- Seamless integration with the **Apple ecosystem**.

**Negative Themes**:
- Battery drains faster than expected for heavy users.
- Heating during charging, gaming, or extended camera usage.
- 60Hz refresh rate feels outdated at this price point.

---

## 💡 Recommendations

**For Apple**:
- Improve battery life and charging efficiency.
- Optimize thermal management for camera/gaming.
- Consider higher refresh rate (90–120Hz) in future models.

**For Flipkart Marketing**:
- Highlight camera quality, design, and performance in ads.
- Include real customer photos and testimonials.
- Be transparent about battery performance and refresh rate.
- Emphasize deals, exchange offers, and fast delivery.

---

## Data Visualization using Matplot library in Python.

# Distribution of positive and negative sentiments for the 300 reviews

![Distribution of positive and negative sentiments for the 300 reviews](https://github.com/farook8090/Python-Projects/blob/50d110554edb28aaa6e59cec33fedad1e8cf5a9d/Customer%20Sentiment%20Analysis/Distribution%20of%20positive%20and%20negative%20sentiments%20for%20the%20300%20reviews.png)

# Average Sentiment Polarity vs Rating

![Average Sentiment Polarity vs Rating](https://github.com/farook8090/Python-Projects/blob/50d110554edb28aaa6e59cec33fedad1e8cf5a9d/Customer%20Sentiment%20Analysis/Average%20Sentiment%20Polarity%20vs%20Rating.png)

# Negative Reviews Word Cloud

![Negative Reviews Word Cloud](https://github.com/farook8090/Python-Projects/blob/50d110554edb28aaa6e59cec33fedad1e8cf5a9d/Customer%20Sentiment%20Analysis/Negative%20Reviews%20Word%20Cloud.png)

# Review Length vs Sentiment

![Review Length vs Sentiment](https://github.com/farook8090/Python-Projects/blob/50d110554edb28aaa6e59cec33fedad1e8cf5a9d/Customer%20Sentiment%20Analysis/Review%20Length%20vs%20Sentiment.png)
