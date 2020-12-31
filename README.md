
Book-Exchanger-Web
The AIM is to provide a web app wherein students can easily exchange,buy or sell books. We presume a lot of students struggle to find the required books according to their college syllabus. It’s hard to gather notes from different online sites and libraries because of their high costs. So, we have created a mobile app and web app wherein students can easily exchange books in mutual understanding with each other. It works in association with our Book-exchanger-app



#Requirements
The code requires the following software for installation (older versions may work, but haven't been tested):

Python 3.7 or later.
Tech Stack
Back-End: - Python, Django, sqlite3
Front-End:- HTML/CSS, Bootstrap, JQuery, JavaScript, AJAX
Installation
Clone the repository
Run pip install virtualenvto install virtualenv system-wide (if not installed before)
Make a virtual environment in directory by running python -m venv myvenv
Activate the virtual environment by:
myvenv\Scripts\activate on Windows
source myvenv/bin/activate on MacOS, Linux, Ubuntu
Run pip install requirements.txt
cd Book-Exchanger-Web-master
python manage.py makemigrations app
python manage.py migrate
python manage.py runserver


#Future Features
Give recommendation for user based on their interests of the books by using Machine Learning
