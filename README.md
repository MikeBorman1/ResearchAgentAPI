# ResearchAgentAPI

1. Clone repo
```
git clone https://github.com/axcelerateai/ResearchAgentAPI
```

2. Install requirements

```bash
python3 -m venv .venv
source .env/bin/activate

pip install -r requirements.txt
```

3. Create `.env` file in dir and save following API keys

```
SERP_API_KEY=XXXXXXXXXX
BROWSERLESS_API_KEY=XXXXXXXXXX
OPENAI_API_KEY=XXXXXXXXXX
```

4. Run fastapi

```bash
uvicorn app:app --host 0.0.0.0 --port 8000
```
