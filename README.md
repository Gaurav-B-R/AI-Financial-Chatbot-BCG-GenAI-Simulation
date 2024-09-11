# AI Financial Chatbot - BCG GenAI Job Simulation

## Overview
This repository contains my completed project for the BCG X GenAI Job Simulation. The project involved two main tasks:

1. **Data Extraction and Analysis**: Extracted and analyzed key financial data from the 10-K filings of Microsoft, Tesla, and Apple.
2. **AI-Powered Financial Chatbot**: Developed a rule-based chatbot to respond to predefined queries about financial metrics based on the extracted data.

## Project Breakdown

### Task 1: Data Extraction and Analysis
- Extracted financial data including Total Revenue, Net Income, Total Assets, Total Liabilities, and Cash Flow from Operating Activities.
- The financial data was organized into a CSV file for further analysis and integration into the chatbot.

### Task 2: Developing an AI-powered Financial Chatbot
- The chatbot uses a simple rule-based logic to respond to predefined queries like:
  - "What is the total revenue?"
  - "How has net income changed over the last year?"
  - "What are the total assets?"
  - "What is the cash flow from operating activities?"
  - "How have liabilities changed?"
- It fetches the data from a CSV file containing the financial metrics for Microsoft, Tesla, and Apple.
  
## Technologies Used
- **Python**: The main programming language used to build the chatbot and handle data analysis.
- **Pandas**: Used for data handling and analysis.
- **Flask** (Optional): Used for building a simple web-based interface (not included in the current version).

## How to Run the Project
1. Clone the repository.
2. Ensure Python and Pandas are installed.
3. Place the `financial_data.csv` file in the project directory.
4. Run the `chatbot.py` script.
5. Start asking predefined financial questions in the terminal, such as "What is the total revenue?".

## Example Queries
- "What is the total revenue?"
- "How has net income changed over the last year?"
- "What are the total assets?"

## Certificate
I successfully completed the BCG X GenAI Job Simulation and received a certificate of completion for my work on this project. 

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
