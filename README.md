# FastAPI Project

A FastAPI application with Python virtual environment setup.

## Setup

1. Clone the repository
2. Set up the virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Running the Application

Start the FastAPI server:
```bash
uvicorn main:app --reload
```

The application will be available at http://localhost:8000

## API Documentation

- Interactive API documentation: http://localhost:8000/docs
- Alternative API documentation: http://localhost:8000/redoc
