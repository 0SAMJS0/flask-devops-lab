# Flask DevOps Lab

A diagnostic Flask application built to practice Git, GitHub, and Docker workflows.

## Usage

```bash
.venv\Scripts\activate
pip install -r requirements.txt
python app.py
```

## API Endpoints

- `/api/health` — returns a simple status check confirming the app is running
- `/api/config` — returns the application configuration from config.json
- `/api/report` — returns hostname, Python version, and uptime in seconds
