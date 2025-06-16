# JMeter API Chaining: Dmoney Performance Testing

## Project Overview
This project demonstrates performance testing of a REST API using Apache JMeter. The API under test is the **Dmoney** system, where various financial operations like deposits, money transfers, and payments are executed in chained workflows.

## Project Scenario:
- 5 Agents perform deposits for 10 different Customers.  
- Theb 5 Customers send money to another 10 Customers.  
- Then 5 Customers make payments to 2 Merchants. 

## 🛠 Tools & Features
- **Apache JMeter**
- **CSV Data Set Config**
- **Random Variable Controller**
- **Response Assertion**
- **JSON Extractor**
- **HTML Report Generation**
- **Postman**

## Prerequisites
- Apache JMeter installed
- Java JDK 17.0.12 (LTS) installed and configured in your system PATH

## HTML Report Screenshot:
![image alt](https://github.com/abhishek11das/jmeter-api-chaining/blob/cb92e7f4bb6bee694597f7c56c1220467cd9e2aa/Dmoney.png)

###### Caution: Make sure to delete the previous `Report/` folder and `.jtl` file before generating a new report to avoid data conflicts.
