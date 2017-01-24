# GWCFlask

## Running the server from Codeanywhere
- Access the online IDE [here] (https://codeanywhere.com/s/l/iXa2MWVc3U9hyzrWn2DnS5Umd3ygaRcBxxfiw8EWMB3TIK6a6cPFM5nFWr9ldG21).
- Go to the "Test Flask" tab with the ssh terminal icon. If it is not there, go the folder view on the left side, right click and select SSH Terminal.
- In the terminal run the following:
```
cd GWCFlask
export FLASK_APP=hello.py
flask run --host=0.0.0.0
```
You can now access the site at http://port-5000.test-flask-hannakohxt104966.codeanyapp.com/.

## Running the server locally
- Clone this repo
- Make sure pip is installed (Python package installer)
- Run the following
```
pip install Flask
cd GWCFlask
export FLASK_APP=hello.py
flask run
```
- You can now access the site at http://localhost:5000.
