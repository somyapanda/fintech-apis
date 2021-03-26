# fintech-apis-homework 

This repository contains the Jupyter notebook and accompanied library code as part of the Fintech homework assignment **Unit 5 - Financial Planning**.

## Background

As part of this problem, we've decided to start a FinTech consultancy firm, and we want to make a difference by working on projects with high social impact in local communities. We just won the first contract to help one of the biggest credit unions in our area. They want to create a tool that helps their members enhance their financial health. The Chief Technology Officer (CTO) of the credit union asked us to develop a prototype application to demo in the next credit union assembly.

The credit union board wants to allow the union's members to assess their monthly personal finances, and also be able to forecast a reasonably good retirement plan based on cryptocurrencies, stocks, and bonds.

In this homework activity, we will use all the skills that we have learned until now - focusing on using APIs as part of the technical solution - to create two financial analysis tools.

The first will be a personal finance planner that will allow users to visualize their savings composed by investments in shares and cryptocurrencies to assess if they have enough money as an emergency fund.

The second tool will be a retirement planning tool that will use the Alpaca API to fetch historical closing prices for a retirement portfolio composed of stocks and bonds, then run Monte Carlo simulations to project the portfolio performance at 30 years. We will then use the Monte Carlo data to calculate the expected portfolio returns given a specific initial investment amount.

---

## Files

### [Personal Finance Planner](financial-planner.ipynb)

This is the Jupyter notebook which contains the solution where:

- We create a personal finance planner application with a savings portfolio and perform a savings health analysis.
- We create a retirement portfolio and perform Monte Carlo simulation to project the portfolio performance at `30`, `10` and `5` years.

### [MCForecastTools toolkit](MCForecastTools.py)

A Python class for runnning Monte Carlo simulation on portfolio price data.

---






