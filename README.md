# Library-Chat-Bot
A Python Flask-based chatbot app that helps students and admins manage library operations. Features include book search, borrowing, renewal, admin management, borrowing reports, and exporting book lists. Designed for an intuitive and efficient library experience.

Developed an interactive chatbot application to streamline library management and improve user experience. The system allows students to search for books, borrow and return them, and receive personalized recommendations. Admin features include managing book inventory, tracking borrowing reports, and handling user accounts. Built with Python and Flask, featuring a user-friendly interface and real-time database integration to automate library operations efficiently.

Project Highlights :
- A chatbot-based web app for library management
- Makes tasks like searching, borrowing, and returning books quicker and easier
- Clean interface built for both students and admins

Admin Features :
- Update book information
- Manage student records
- Track returns and renewals
- Generate borrowing reports
- Export book data

Student Features :
- Search books by genre or author
- Renew borrowed books
- Get due date reminders
- View borrowing history
- Receive book recommendations

Tech Stack :
- Frontend: HTML, CSS, JS
- Backend: Python (Flask)
- Database: SQLite
- NLP/Parsing: Regex, Keyword Matching Basic intent detection

## System Workflow

1. **User Login**  
   - Student or Admin login to access role-specific features  

2. **Natural Query Handling**  
   - Chatbot interprets user messages using regex and keyword logic  

3. **Database Interaction**  
   - Performs search, borrow, return, and update operations on the SQLite database  

4. **Admin Panel Access**  
   - Admins can manage records and generate reports from a dedicated dashboard  

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

## Future Enhancements

- Add voice recognition using Speech-to-Text  
- Implement sentiment-based book feedback  
- Improve NLP using spaCy or Transformer models  
- Add email reminders for due dates  
- Enable multiple admin roles and permissions  

## 👤 Author

**Sudarshan A S**  
[LinkedIn](https://www.linkedin.com/in/sudarshanas) • [GitHub](https://github.com/Sudarshan007AS)  

---


