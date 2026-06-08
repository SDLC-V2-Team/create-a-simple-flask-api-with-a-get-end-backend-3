# Simple Flask API

A minimal Flask API that provides two endpoints:

- `GET /` – returns "Hello World"
- `GET /health` – returns HTTP 200 with body "OK"

## Getting Started

1. Clone the repository.
2. Create a virtual environment:
   bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   
3. Install dependencies:
   bash
   pip install -r requirements.txt
   
4. Run the application:
   bash
   python app.py
   
5. Access the endpoints:
   - http://localhost:5000/
   - http://localhost:5000/health

## Testing

Run tests with:
bash
pytest

