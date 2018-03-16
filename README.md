# try_flask
## Steps 

1. Install python *version>3 preferred*
2. Create virtual environment and activate
    ```bash
    D:\Ergazi\Workspace\try_flask>python -m venv venv

    D:\Ergazi\Workspace\try_flask>venv\Scripts\activate.bat
    (venv) D:\Ergazi\Workspace\try_flask>python --version
    Python 3.6.4
    ``` 
3. install flask 
    ```bash 
    (venv) D:\Ergazi\Workspace\try_flask>pip install flask 
    ``` 
4. freeze 
    ```bash 
    (venv) D:\Ergazi\Workspace\try_flask>pip freeze 
    ``` 
5. set FLASK_APP
    ```bash
    (venv) D:\Ergazi\Workspace\try_flask>set FLASK_APP=app.py 
    ```
6. run & check on browser
    ```bash
    (venv) D:\Ergazi\Workspace\try_flask>flask run
     * Serving Flask app "app"
     * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
    127.0.0.1 - - [16/Mar/2018 16:05:59] "GET / HTTP/1.1" 200 -
    ```
