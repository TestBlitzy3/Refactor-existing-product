# hao-backprop-test
test project for backprop integration. Do not touch!

## Requirements
- Python 3.8 or higher
- Flask 2.0.1

## Installation

1. Clone the repository
2. Create and activate a Python virtual environment:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

## Running the Server

Start the server using one of the following commands:

```
python app.py
```

Or alternatively:

```
flask run --host 127.0.0.1 --port 3000
```

The server will run at http://127.0.0.1:3000/ and return "Hello, World!" for all requests.