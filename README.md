# LingoBot Translation API

A FastAPI-based translation service supporting text and voice translation.

## Setup

1. Clone the repository:
```bash
git clone https://github.com/Oterochris/lingobot-translation-api.git
cd lingobot-translation-api
```

2. Create and activate virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run the application:
```bash
uvicorn src.main:app --reload
```

5. Visit http://127.0.0.1:8000/docs for the API documentation

## Features

- Text translation
- Language detection
- Translation history
- CORS support
- API documentation

## API Endpoints

- `GET /`: Welcome message
- `POST /api/v1/translate/text`: Translate text
- `GET /api/v1/translation-history`: Get translation history

## Development

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request
