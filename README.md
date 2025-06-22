### Flask To-Do List App

A simple web-based To-Do List app built using Flask (Python web framework). It allows users to add and delete tasks dynamically, all stored in memory

Features
	•	Add new tasks<br>
	•	Delete tasks<br>
	•	Live update without reloading the server<br>
	•	In-memory data (no database, ideal for learning Flask basics)<br>

## Project Structure
<pre>
	todo_list/
│
├── templates/
│   └── todo_flask_templates.html   # Main HTML template
│
├── app.py                          # Flask application code
└── README.md
</pre>

## Requirements

Make sure you have Python 3 and Flask installed.

You can install Flask using:
<pre>
	pip install flask
</pre>

How to Run
<pre>python app.py</pre>

Then open your browser and visit Local Host visible on your terminal

How It Works
	•	The homepage (/) displays a form and a list of tasks<br>
	•	When a task is submitted, it’s added to the in-memory tasks list<br>
	•	Clicking “Delete” removes a task by its index<br>
	•	All changes reflect immediately without restarting the app<br>

Notes
	•	This app doesn’t use a database. Tasks are stored temporarily in a Python list and will reset when the server restarts<br>
	•	Perfect for learning Flask routing, HTML templating, and basic form handling<br>

## License

This project is free to use and modify. No license required.
