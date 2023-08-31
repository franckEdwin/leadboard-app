# Leadboard App

The Leadboard App is a simple Flask application for managing a team leaderboard with their points. Administrators can update points and create new teams.

## Dependencies

- Python 3.8+
- Flask 2.0.1+
- Flask-Login 0.5.0+
- Flask-SQLAlchemy 3.0+
- Flask-Migrate 3.0+

## Installation

1. Clone this repository and set up the virtual environment:
   ```bash
   git clone https://github.com/YourUsername/leadboard-app.git
   cd leadboard-app
   python -m venv venv
2. Activate the virtual environment and install dependencies:
   - On Windows:
     ```bash
     .\venv\Scripts\activate
     pip install -r requirements.txt
     ```
   - On macOS and Linux:
     ```bash
     source venv/bin/activate
     pip install -r requirements.txt
     ```

3. Set up the secret key in the `.env` file:
