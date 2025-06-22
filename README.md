# ToDo AI Backend

Detta är en enkel backend byggd med Flask och OpenAI:s API. Den svarar på frågor som t.ex:
- Vad händer i Stockholm idag?
- Aktiviteter för barn nära Sundsvall
- Gratis aktiviteter i sommar

## Endpoints

### POST /ask
Skicka en JSON med en `question`:
```json
{
  "question": "Vad händer i Stockholm idag?"
}
```

## Setup (lokalt)
1. Skapa `.env`-fil och lägg in:
```
OPENAI_API_KEY=ditt_openai_api_key
```

2. Kör:
```
pip install -r requirements.txt
python main.py
```

## Deployment
Klar att användas på Render.com eller Replit.
