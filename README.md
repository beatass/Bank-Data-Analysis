# Bank Data Analysis

Project refers to analysis of bank data i.e. customers and transactions.

## General info

The project includes the analysis of example bank data with **SQL**.  The data contains information about **Customers** and **Transactions**. The analysis was prepared with **MS SQL Server** database.

## Dataset

The dataset was prepared especially for this project and contains sample data about bank customers and transactions. It includes two tables named **Customer** and **Transactions**.

##Table descriptions:

•	Customer
      o	**customer_id**: customer identifier (**unique**)
      o	**customer_type**: customer type (**standard, premium, VIP**)
      o	**age**: customer's age
      o	**income**: customer's income/earnings (**total value**)
•	Transactions
      o	customer_id: identyfikator klienta powiązany z transakcją
      o	transaction_type: typ transakcji (incoming, outgoing)
      o	amount: kwota transakcji
      o	transaction_month: miesiąc transakcji (1-12)
      o	transaction_year: rok transakcji
