**💼 FININTENT AGENT – Finance Intent Detection with Ollama + LangChain**



FinIntent Agent is an offline, intelligent system that detects the intent behind finance-related queries using LLaMA3 and LangChain.
It routes user input to specific Python handler classes and calculates a confidence score for each prediction.



**🚀 Features**



✅ Detects the intent of financial queries

🧠 Uses LLaMA3 (via Ollama) and LangChain

🔁 Routes queries to Python intent handler classes

📊 Calculates a confidence score

📈 Visualizes results using Plotly

🔒 100% local and private — no API keys needed



**🎯 Intent Classes Implemented**



💵 RevenueQuery

⚠️ RiskAssessment

📑 FinancialSummary

📊 InvestmentSummary

📈 MarketVisualization

📉 ComparativeAnalysis

📃 ReportSummary

🔮 ForecastRequest

📉 CreditScoreSummary

📊 DebtRatioAnalysis

📌 KPIRequest

🔍 EntityExtraction

🚨 AnomalyDetection



**⚙️ How to Run**



Clone this repository
git clone https://github.com/your-username/fin-intent-agent.git
cd fin-intent-agent

Install dependencies
pip install -r requirements.txt

Start the LLaMA3 model using Ollama
ollama run llama3

Launch the notebook
jupyter lab

Open and run all cells in:
fin-intent-detection-ollama.ipynb



**💬 Example Queries**





What is the revenue for Q4 2023?

Compare 2022 and 2023 income

Summarize the investment risks

Forecast next quarter’s growth

Each query will be:
✅ Parsed by the LLM
✅ Classified into an intent
✅ Scored for confidence
✅ Routed to a custom handler class
✅ Visualized with a Plotly chart



**📈 Output Includes**



✅ Detected intent class and description

✅ Confidence score

📊 A Plotly bar chart showing all predictions



**👤 Author**



Yash Pise
🔗 GitHub
💼 LinkedIn
