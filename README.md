# Spendly — Personal Expense Tracker

A web application to log expenses, understand spending patterns, and take control of your financial life — one transaction at a time.

## Features

- User registration and login
- Log expenses with category, amount, date, and description
- View spending breakdowns by category
- Filter expenses by time period
- Monthly summaries

## Tech Stack

- **Backend:** Python, Flask
- **Database:** SQLite
- **Frontend:** Jinja2 templates, HTML, CSS, JavaScript
- **Testing:** pytest, pytest-flask

## Project Structure

```
expense-tracker/
├── app.py                  # Flask app and route definitions
├── database/
│   ├── __init__.py
│   └── db.py               # Database connection, init, and seed helpers
├── templates/
│   ├── base.html
│   ├── landing.html
│   ├── login.html
│   └── register.html
├── static/
│   ├── css/style.css
│   └── js/main.js
└── requirements.txt
```

## Getting Started

### Prerequisites

- Python 3.9+

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sonusinha1707/Spendly.git
   cd Spendly
   ```

2. Create and activate a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the App

```bash
python3 app.py
```

The app will be available at `http://localhost:5001`.

## Running Tests

```bash
python3 -m pytest
```
