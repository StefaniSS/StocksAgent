Stock Market Analysis with AI
![Captura de ecrã 2024-08-22 025817](https://github.com/user-attachments/assets/0fa267c2-9704-49da-94a3-a60e8c3f1fa0)


This project is a comprehensive AI-powered solution for analyzing stock prices and market news. It was developed as part of the "IA na Prática" event by Rocketseat. The application uses advanced AI agents to gather stock price data, analyze market trends, and generate insightful reports, all accessible via a Streamlit web interface.

Features
Stock Price Analysis: Fetches and analyzes historical stock price data using Yahoo Finance.
Market News Analysis: Gathers and summarizes relevant market news, assessing market sentiment using a fear/greed score.
Automated Report Generation: Produces a detailed newsletter-style report, including a summary of key insights and predictions for the future trends.
How It Works
Data Collection: The system fetches historical stock data and current market news for a specified stock ticker.
AI Analysis: The data is processed by specialized AI agents:
Stock Price Analyst: Evaluates stock price trends (up, down, or sideways).
News Analyst: Analyzes news sentiment and provides a fear/greed score.
Stock Analyst Writer: Compiles the analyses into a comprehensive report.
Output: The final output is a well-structured report presented in markdown format, ready for review or publication.
Getting Started
Prerequisites
Python 3.7 or higher
Streamlit
Required Python packages: yfinance, langchain, crewai, streamlit
Installation
Clone this repository:

bash
Copiar código
git clone https://github.com/yourusername/stock-market-analysis-ai.git
cd stock-market-analysis-ai
Install the required packages:

bash
Copiar código
pip install -r requirements.txt
Set your OpenAI API key in the Streamlit secrets:

bash
Copiar código
echo "[general]" > ~/.streamlit/secrets.toml
echo "OPEN_API_KEY = 'your-openai-api-key'" >> ~/.streamlit/secrets.toml
Run the application:

bash
Copiar código
streamlit run app.py
Open your browser and go to http://localhost:8501 to interact with the app.

Usage
Enter the stock ticker you want to analyze in the sidebar form and click "Run Research."
The application will fetch the data, run the AI analysis, and display the results directly on the page.
Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.
