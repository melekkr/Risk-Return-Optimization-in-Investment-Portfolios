# Risk-Return Optimization in Investment Portfolios

## Project Overview
This project focuses on **optimizing investment portfolios** using **Markowitz’s Modern Portfolio Theory (MPT)**. The goal of the project is to create a set of investment portfolios that either minimize risk for a desired return or maximize return for a given level of risk. Using historical financial data, this model calculates the best portfolio configurations by considering the **covariance matrix** to understand how different assets interact and their standard deviation to calculate the overall risk.

## Objectives:
- To **optimize portfolios** by balancing **risk and return** using Markowitz's Modern Portfolio Theory.
- To calculate the **optimal portfolio weights** for each asset in the portfolio.
- To generate an **efficient frontier** graph, which shows the relationship between risk and return for various portfolio configurations.
- To demonstrate how the **covariance matrix** helps in assessing the risk of the overall portfolio based on the interrelationships between the assets.

## Methods:
1. **Covariance Matrix**: The covariance matrix is used to understand the correlation between different assets, enabling risk diversification and the calculation of overall portfolio risk.
2. **Risk Calculation**: Risk is quantified using the **standard deviation** of the portfolio's returns. A well-optimized portfolio will aim to reduce risk while achieving the target return.
3. **Weighted Average Returns**: The weighted average of the returns on individual assets is used to determine the overall portfolio return.
4. **Efficient Portfolio Construction**: The portfolio that provides the **maximum return** for a **given level of risk** or the **minimum risk** for a desired return is considered efficient. These portfolios lie along the **efficient frontier**.

## How It Works:
1. The historical data of various assets (such as stocks, bonds, etc.) is loaded into the model.
2. **Risk and return for each asset** are calculated using historical price data.
3. The model computes the **covariance matrix** to analyze how asset returns move together, aiding in diversification.
4. Using the covariance matrix and asset returns, the portfolio's total risk and expected return are optimized.
5. The **efficient frontier** is plotted, showcasing the optimal risk-return combinations.
6. The optimized portfolio is then calculated with the **highest return** for the given risk level or the **lowest risk** for the target return.

## Results:
- The project produces an **efficient frontier** curve that demonstrates the risk-return trade-offs.
- It shows the **optimal asset allocations** for a variety of portfolios, allowing investors to choose portfolios based on their risk tolerance.
- By minimizing risk and maximizing returns, this project enables the **optimization of investment strategies**.

## How to Use:

### Prerequisites:
- Python 3.x
- Required libraries (listed in `requirements.txt`)

### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/melekkr/Risk-Return-Optimization-in-Investment-Portfolios.git
