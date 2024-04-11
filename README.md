# chatbot
Simple streamlit chatbot

## Why?
- Utilize OpenAI strictly through the API
- Begin learning more about LangChain

## Dependencies
Requires a .env file with contents:
```
OPENAI_API_KEY=<your-api-key>
```

## Development

```bash
python3 -m venv env
source env/bin/activate
pip install poetry
poetry install
streamlit run --server.address 0.0.0.0 chat.py
```