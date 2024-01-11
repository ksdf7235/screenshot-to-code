cd backend
echo "OPENAI_API_KEY=sk-your-key" > .env
poetry install
poetry shell
poetry run uvicorn main:app --reload --port 7001
