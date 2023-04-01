# pythonlogin

file structure

\-- pythonlogin
    |-- main.py
    \-- static
        |-- style.css
    \-- templates
        |-- index.html
        |-- register.html
        |-- home.html
        |-- profile.html
        |-- layout.html
        
        
main.py — This will be our main project file, all our Python code will be in this file (Routes, MySQL connection, validation, etc).
index.html — The login form template created with HTML5 and CSS3.
register.html — The registration form template created with HTML5 and CSS3.
home.html — The home template which is restricted to logged-in users.
profile.html — The profile template which is restricted to logged-in users. The user's details will be populated on this page.
layout.html — The layout template for the home and profile templates.
style.css — The CSS3 stylesheet for our login and registration system.

Requirements
Download and install Python, for this tutorial I'll be using Python 3.7.2. Make sure to check the Add Python to PATH option on the installation setup screen.
Download and install MySQL Community Server and MySQL Workbench. You can skip this step if you already have a MySQL server installed.
Open command line and Install Python Flask with the command: pip install flask
Install Flask-MySQLdb with the command: pip install flask-mysqldb
