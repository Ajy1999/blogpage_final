# 📝 Flask Blog App

A simple blog web application built with Flask. Users can register, log in, create blog posts, and comment. Admins have additional privileges to manage posts. Created the project as a part of 100 days of Python Course

## 🚀 Features

- User Registration & Login (Flask-Login)
- Blog post creation, editing, and deletion (admin only)
- Commenting system
- Rich text editor with CKEditor
- Responsive UI with Bootstrap
- SQLite / PostgreSQL database support

## 🛠️ Tech Stack

- **Backend**: Flask, Flask-Login, Flask-SQLAlchemy, Flask-WTF
- **Frontend**: HTML, Bootstrap, Jinja2, CKEditor
- **Database**: SQLite (default) or PostgreSQL
- **Deployment**: Gunicorn

## 📦 Setup Instructions

### 1. Clone the repo

```bash
git clone https://github.com/your-username/flask-blog-app.git
cd flask-blog-app
```
### 2.  Create and activate a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```
### 3. Install dependencies
```bash
pip install -r requirements.txt
```
### 4. Configure environment variables
Create a .env file in the root folder with the following:

-env
-Copy
-Edit
```env
FLASK_APP=main.py
FLASK_ENV=development
SECRET_KEY=your_secret_key
DATABASE_URL=sqlite:///blog.db  # Or use your PostgreSQL URI

```

🔒 Note: .env is excluded from version control via .gitignore
### 5. Run the app
```bash
flask run
```
## 🗂 Project Structure
```csharp
flask-blog-app/
│
├── templates/          # HTML templates
├── static/             # CSS, JS, images
├── main.py             # Main Flask app
├── models.py           # Database models
├── forms.py            # WTForms classes
├── requirements.txt    # Python dependencies
├── .env.example        # Sample environment variables
├── README.md           # Project overview
└── .gitignore
```
## 🙋‍♀️ About Me
I'm Aishwarya, and this is one of my learning projects as I explore web development with Python and Flask. Feel free to reach out or suggest improvements!







