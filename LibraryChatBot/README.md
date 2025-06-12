## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Sudarshan007AS/Library-Chat-Bot.git
cd Library-Chat-Bot
```

### 2. (Optional) Create and activate a virtual environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
python app.py
```

Visit `http://localhost:5000` in your browser.

##  Project Structure

- `app.py`: Main Flask backend  
- `chatbot.py`: Chat logic and intent detection  
- `database.py`: SQLite helper functions  
- `templates/`: HTML pages for chatbot and admin views  
- `static/`: CSS and JS assets  

## Example Use Case

A student logs in and types:  
> “Search books by author Dan Brown”

The chatbot:
- Matches the query using keyword detection  
- Queries the SQLite database  
- Returns a list of books by Dan Brown  
- Offers options to borrow or get more info  
