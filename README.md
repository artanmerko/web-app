# Flask Web App
## Video Demo:  [URL](https://www.youtube.com/watch?v=HwySXXy_Njk)
## Description:

 Flask is a small and lightweight Python web framework that provides useful tools and features that make creating web applications in Python easier. It gives developers flexibility and is a more accessible framework for new developers since you can build a web application quickly using only a single Python file. Flask is also extensible and doesn’t force a particular directory structure or require complicated boilerplate code before getting started.
 Flask uses the Jinja template engine to dynamically build HTML pages using familiar Python concepts such as variables, loops, lists, and so on.

 In this project, I built a small web app using Flask and SQLite in Python 3. Users of the application can write notes in your database and edit or delete an existing notes.


  ## Requirements:
  A local Python
  Flask
  Flask-SQLAlchemy
  Flask-login

  https://flask.palletsprojects.com/en/2.1.x/
  https://www.python.org/doc/

  ## --Python website app--
  ### --How to use it--
    1. Create an account
    2. Login
    3. Home
    4. Add Notes
    5. Edit or Delete notes
    6. Logout

  #### Setup & Installtion
   git clone <repo-url>
   pip install -r requirements.txt
 
  #### Running The App
    python app.py runserver


  --Viewing The App
  Go to http://127.0.0.1:5000

  At this course I learned how to make a small web application, run it in a development server, and allow the user to provide custom data via URL parameters and web forms. I also used the Jinja template engine to reuse HTML files and use logic in them. At the end of project, I have a fully functioning web blog that interacts with an SQLite database to create, display, edit, and delete notes using the Python language and SQL queries.

  I can further develop this application by adding user authentication so that only registered users can create and edit notes.See the Flask documentation for more information.

  https://flask.palletsprojects.com/en/2.1.x/

  Flask has many community-made Flask extensions. The following is a list of extensions you might consider using to make your development process easier:

  Flask-Login: manages the user session and handles logging in and logging out and remembering logged-in users.
  https://flask-login.readthedocs.io/en/latest/
  Flask-SQLAlchemy: simplifies using Flask with SQLAlchemy, a Python SQL toolkit and Object Relational Mapper for interacting with SQL databases.
  https://flask-sqlalchemy.palletsprojects.com/en/2.x/
  Flask-Mail: helps with the task of sending email messages in your Flask application.
  https://pythonhosted.org/Flask-Mail/
