# Financial Dashboard
This repository contains a financial dashboard developed using Python with Streamlit, pandas, and various data processing techniques. The dashboard allows users to explore and analyze financial data for different companies and years, providing insights into key sections of the financial reports.

# Features
*Company and Year Selection:* Users can select a specific company and year from the sidebar to view financial summaries for that period.

*Section-wise Analysis:* Users can choose to view summaries for different sections of the financial reports, enabling a more focused analysis.

*Topic Extraction:* The dashboard also provides insights into important words or topics extracted from the text, helping users identify significant trends or terms in the financial reports.

*Sentiment Analysis:* Sentiment analysis is included to assess the overall sentiment of the text within each section.

# How to Use
1. Clone this repository to your local machine.
2. Install the required Python packages listed in the requirements.txt file.
3. Run the app.py script using Streamlit to launch the financial dashboard.
4. Select the company, year, and analysis options from the sidebar to explore the financial data.

# Data Sources
The financial data used in this dashboard is loaded from CSV files specified in the config.py file.

# File Structure
* app.py: The main Streamlit application script.
* functions.py: Contains functions for displaying summaries, topics, and sentiment analysis.
* config.py: Configuration file specifying the paths to the CSV data files.
* datasets/: Directory containing the CSV data files.

Feel free to explore the code and customize the dashboard to suit your specific financial analysis needs.
