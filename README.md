# Bank Data Analysis

Project refers to analysis of bank data i.e. customers and transactions.

## General info

The project includes the analysis of example bank data with **SQL**.  The data contains information about **Customers** and **Transactions**. The analysis was prepared with **MS SQL Server** database.

### Dataset

The dataset was prepared especially for this project and contains sample data about bank customers and transactions. It includes two tables named **Customer** and **Transactions**.

### Table descriptions:

#### Customer:
- **customer_id**: customer identifier (**unique**)
- **customer_type**: customer type (**standard, premium, VIP**)
- **age**: customer's age
- **income**: customer's income/earnings (**total value**)

#### Transactions
- **customer_id**: customer identifier associated with the transaction
- **transaction_type**: transaction type  (**incoming, outgoing**)
- **amount**: transaction amount
- **transaction_month**: transaction month (**1-12**)
- **transaction_year**: transaction year
