  Simple Blogging Website
  
Blog is a minimalistic blogging website built using Flask, SQLite, and SQLAlchemy. It provides users with the ability to create, edit, and delete their blog posts, as well as view and comment on posts by other users. 
Blogging website

Features
User Authentication: Users can register and log in to their accounts securely.
Create and Edit Blog Posts: Authenticated users can create and edit their blog posts using a rich text editor.
Category-Based Posts: Posts are organized into categories, making it easier for users to find content of interest.
User Profile: Users can view their profile and see the list of their own blog posts.
Admin Dashboard: An admin dashboard is available for managing blog posts and categories.
Requirements
Before you get started, ensure you have the following software and tools installed:

Python (>=3.6)
Flask
SQLite
SQLAlchemy
Installation

Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/blogzen.git
cd blogzen
Create a virtual environment and activate it:

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows, use venv\Scripts\activate
Install the project dependencies:

bash
Copy code
pip install -r requirements.txt
Initialize the SQLite database:

bash
Copy code
flask db init
flask db migrate
flask db upgrade
Configure environment variables by creating a .env file in the project root:

env
Copy code
FLASK_APP=app.py
FLASK_ENV=development  # Change to 'production' for production deployment
SECRET_KEY=your_secret_key
DATABASE_URL=sqlite:///blog.db
Start the development server:

bash
Copy code
flask run
Open your web browser and go to http://localhost:5000 to access the website.

Usage
Register an account or log in if you already have one.
Create, edit, or delete your blog posts.
Explore and comment on posts by other users.
Visit the admin dashboard by going to /admin to manage posts and categories.
Contributing
We welcome contributions to improve this project. If you'd like to contribute, please follow these steps:


Acknowledgments
Flask - A lightweight Python web framework.
Bootstrap - A popular front-end framework.
TinyMCE - A rich text editor for creating blog posts.

