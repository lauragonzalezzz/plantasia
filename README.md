# Plantasia

[Taskboard](https://dry-caverns-85168.herokuapp.com/)

# Steps to setup environment
1. [Download and install Python](https://www.python.org/downloads/) (install to local hard drive in install menu)
2. Verify Python is version 2.7.13 (python -V)
3. Verify pip is installed (pip -V)
4. Install the virtual environment (pip install virtualenv)
5. Clone project file
6. Navigate into project file
7. Create virtual env executable: `virtualenv venv`
8. Activate virtual environment
* For Mac: `. venv/bin/activate`
* For Windows: `venv\Scripts\activate`
9. Install Flask `pip install Flask`
10. Run project:
* For Mac: 
	
    `export FLASK_APP=app.py`
	
    `flask run`
* For Windows:
	
    `set FLASK_APP=app.py`
	
    `flask run`