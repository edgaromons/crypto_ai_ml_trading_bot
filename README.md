# crypto_ai_ml_trading_bot
In this project, I will show you how I built a Crypto AI Trading Bot using ML Models.

Here, we:

•	Utilized Python and technical analysis libraries, such as TA-Lib and yfinance, to develop and implement a cryptocurrency trading bot, focusing on market trend analysis and order execution.

•	Developed data extraction techniques using requests-html and lxml to scrape real-time market data from Yahoo Finance, providing up-to-date insights for informed trading decisions.

•	Applied machine learning principles, particularly Long Short-Term Memory (LSTM) networks, to predict cryptocurrency closing prices and enhance the bot's trading strategies.

•	Integrated Alpaca API for seamless order execution and portfolio management within the trading bot, ensuring real-time interaction with market data and order placement.

•	Built a system for monitoring the bot's performance using Python's logging module, facilitating debugging and ensuring the bot's reliable and efficient operation.

Installing Dependencies from requirements.txt
Follow these steps to install the required Python dependencies on your system.
✅ Prerequisites:
•	Ensure Python (>=3.x) and pip (>=21.x) are installed.
•	Check Python and pip versions:
sh
CopyEdit
python --version
pip --version
📌 Installation Instructions
🖥️ Windows:
1.	Open Command Prompt or PowerShell.
2.	Navigate to the project directory:
sh
CopyEdit
cd path\to\your\project
3.	Run:
sh
CopyEdit
pip install -r requirements.txt
🍏 macOS & 🐧 Linux:
1.	Open Terminal.
2.	Navigate to the project directory:
sh
CopyEdit
cd /path/to/your/project
3.	Run:
sh
CopyEdit
pip install -r requirements.txt
🔍 Additional Tips:
•	If using a virtual environment, activate it before running the installation:
sh
CopyEdit
# Windows (CMD)
venv\Scripts\activate

# Windows (PowerShell)
venv\Scripts\Activate.ps1

# macOS/Linux
source venv/bin/activate
•	If you face permission issues, try:
sh
CopyEdit
pip install --user -r requirements.txt
•	For system-wide installation, use:
sh
CopyEdit
sudo pip install -r requirements.txt
🛠️ Verifying Installation:
Run:
sh
CopyEdit
pip list
to check if all packages are installed.
