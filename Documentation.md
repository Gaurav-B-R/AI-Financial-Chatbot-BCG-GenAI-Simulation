# Financial Chatbot Documentation

## Overview
This project involves the development of a rule-based AI chatbot that responds to predefined financial queries using the financial data of three major companies: Microsoft, Tesla, and Apple. The chatbot allows users to ask about financial metrics like total revenue, net income, total assets, liabilities, and cash flow, with responses based on the most recent fiscal data.

## Chatbot Features
The chatbot responds to the following predefined queries:
1. "What is the total revenue?"
2. "How has net income changed over the last year?"
3. "What are the total assets?"
4. "What is the cash flow from operating activities?"
5. "How have liabilities changed?"

## Data Structure
The chatbot uses a CSV file (`financial_data.csv`) containing financial data for Microsoft, Tesla, and Apple. The data is structured in the following columns:
- `Company`: The name of the company (Microsoft, Tesla, or Apple).
- `Fiscal Year`: The fiscal year of the financial data.
- `Metric`: The financial metric (e.g., Total Revenue, Net Income, Total Assets).
- `Value`: The corresponding financial figure.

## Limitations
- **Predefined Queries**: The chatbot can only respond to the predefined financial queries. It will not recognize or respond to other questions.
- **Static Data**: The data is static and needs to be manually updated. It does not pull real-time data from financial sources.

## How to Run the Chatbot
1. Ensure you have Python installed on your system.
2. Install the required library, `pandas`, using the command:
   ```bash
   pip install pandas
