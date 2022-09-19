# 212-arcade

## virtual environment -- mac
python3 -m venv env
source env/bin/activate
pip install flask

## virtual environment -- windows
py -m venv env  
env\Scripts\activate.bat
pip install Flask

## running flask --mac
source env/bin/activate
export FLASK_APP=run.py
export FLASK_DEBUG=1
flask run

## running flask --win
env/Scripts/ 
export FLASK_APP=run.py
export FLASK_DEBUG=1
py -m 
