Simple REST API to create users and track their weight using FastAPI

# Instructions
1. Create a new virtual environment
```
python -m venv venv
```
2. Activate your virtual environment
- Linux (bash)
```
$ source venv/bin/activate
```
- Windows
```
C:\Users\...> venv/Scripts/activate.bat
```
3. Install packages
```
pip install -r requirements.txt
```
4. Start application:
```bash
uvicorn sql_app.main:app --reload
```

__NOTE__: Packages listed in the `requirements.txt` file are meant to work on Windows. If you run into problems installing then, look for the specific version / name of the package that works on your OS.
