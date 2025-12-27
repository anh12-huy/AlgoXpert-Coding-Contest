AlgoXpert Coding Contest – Backtest Engine
Files:
- main.py: Core backtester (three strategies) per problem spec.
- input_SPY.txt: If generated, contains dataset and parameters for evaluation.
- generate_input_spy.py: Optional helper to fetch SPY data via yfinance and produce input_SPY.txt.
- AI_USAGE_[YourName].txt: AI usage narrative.
- REPORT_[YourName].txt: Strategy analysis report.

Build/run (Python):
- Install Python 3.8+.
- Optional: python -m venv venv; source venv/bin/activate
- Run: python main.py < input_SPY.txt > output.txt
