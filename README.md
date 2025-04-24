FinIntent Agent
FinIntent Agent is a local, intelligent system that detects the intent behind financial queries. It uses LLaMA3 (via Ollama) and LangChain to classify user input and route it to the right logic handler. Everything runs offline — no API keys required.

Features
Detects intent in financial queries

Uses LangChain + LLaMA3 with Ollama (runs locally)

Routes each intent to a specific Python class

Calculates a confidence score

Visualizes results with Plotly

Supports multiple languages (English, Hindi, Marathi, Spanish, etc.)

Supported Intents
RevenueQuery

RiskAssessment

FinancialSummary

InvestmentSummary

MarketVisualization

ComparativeAnalysis

ReportSummary

ForecastRequest

CreditScoreSummary

DebtRatioAnalysis

KPIRequest

EntityExtraction

AnomalyDetection

How to Run
Clone this repo: git clone https://github.com/your-username/fin-intent-agent.git

Go into the folder: cd fin-intent-agent

Install required libraries: pip install -r requirements.txt

Make sure Ollama is installed and running: ollama run llama3

Open Jupyter Notebook: jupyter lab

Run all cells in the notebook Intent Agent Assignment.ipynb

Example Queries
What is the revenue for Q4 2023?

Compare 2022 and 2023 income

Summarize the investment risks

Forecast next quarter’s growth

Each query is detected and routed with a confidence score and a response from its class.

Output
You’ll see detected intent, confidence score, and a Plotly bar chart showing confidence levels across queries.

Author
Yash Pise
GitHub: https://github.com/yp0505
LinkedIn: https://linkedin.com/in/yash-pise0505

