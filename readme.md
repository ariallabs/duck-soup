virtualenv venv -p python3
source venv/bin/activate
pip install -r requirements.txt

pyinstaller --name=duck-soup --windowed --onefile --icon=icon.ico Note_App.py 

# to do
