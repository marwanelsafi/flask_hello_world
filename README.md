# flask 
## install virtualenv
### run once 

```bash
   python -m pip install virtualenv
```
## make app
```bash
   mkdir (appname)
   virtulenv (appname)
cd (appname)
    python -m pip install flask
cd scripts
activate


```
### make main.py
#### go to app dir make a new file name.py
```python
from flask import Flask
app = Flask(__name__)

@app.route('/')
def hello_world():
    return 'Hello, World!'
if __name__ == "__main__":
    app.run(debug=True)

```
