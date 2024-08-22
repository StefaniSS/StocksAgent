# Stock Market Analysis with AI

This project is a comprehensive AI-powered solution for analyzing stock prices and market news. It was developed as part of the "IA na Prática" event by Rocketseat. The application uses advanced AI agents to gather stock price data, analyze market trends, and generate insightful reports, all accessible via a Streamlit web interface.

## Features

- **Stock Price Analysis:** Fetches and analyzes historical stock price data using Yahoo Finance.
- **Market News Analysis:** Gathers and summarizes relevant market news, assessing market sentiment using a fear/greed score.
- **Automated Report Generation:** Produces a detailed newsletter-style report, including a summary of key insights and predictions for the future trends.

## How It Works

1. **Data Collection:** The system fetches historical stock data and current market news for a specified stock ticker.
2. **AI Analysis:** The data is processed by specialized AI agents:
   - **Stock Price Analyst:** Evaluates stock price trends (up, down, or sideways).
   - **News Analyst:** Analyzes news sentiment and provides a fear/greed score.
   - **Stock Analyst Writer:** Compiles the analyses into a comprehensive report.
3. **Output:** The final output is a well-structured report presented in markdown format, ready for review or publication.

## Getting Started

### Prerequisites

- Python 3.7 or higher
- Streamlit
- Required Python packages: `yfinance`, `langchain`, `crewai`, `streamlit`

### Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/stock-market-analysis-ai.git
    cd stock-market-analysis-ai
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Set your OpenAI API key in the Streamlit secrets:
    ```bash
    echo "[general]" > ~/.streamlit/secrets.toml
    echo "OPEN_API_KEY = 'your-openai-api-key'" >> ~/.streamlit/secrets.toml
    ```

4. Run the application:
    ```bash
    streamlit run app.py
    ```

5. Open your browser and go to `http://localhost:8501` to interact with the app.

### Usage

- Enter the stock ticker you want to analyze in the sidebar form and click "Run Research."
- The application will fetch the data, run the AI analysis, and display the results directly on the page.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

![Captura de ecrã 2024-08-22 025817](https://github.com/user-attachments/assets/74a6d1cc-3726-40fe-ac57-5b350e4404f3)
