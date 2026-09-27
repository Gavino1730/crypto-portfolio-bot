# Crypto Portfolio Bot

A Telegram bot for keeping a personal crypto portfolio, checking market prices, and setting price alerts.

## What it does

- Saves portfolio holdings locally
- Looks up market prices and news
- Lets users set price alerts
- Supports optional AI-powered replies when an API key is configured

## Run it locally

Create a virtual environment, install the requirements, then copy `.env.example` to `.env` and enter your own keys.

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
python main.py
```

The bot is for personal tracking and information only. It does not provide financial advice.

## Privacy

Runtime data and logs stay local and are excluded from version control.

## License

MIT. See [LICENSE](LICENSE).
