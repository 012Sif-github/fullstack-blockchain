**Activate the virtual environment**

```
source blockchain-env/Scripts/activate

```

**virtual environment editor interpreter**

Make sure the vs code editor is using is not the same interpreter that you're running when you run the server .

on the bottom left corner you should be able to see Python 3.x.x, click it, and make sure it is pointing to your system python

 # https://stackoverflow.com/questions/65694813/import-flask-could-not-be-resolved-from-source-pylance


**Install All Packages**

```
pip install -r requirements.txt
```

**Running tests**

Make sure to activate virtual env
```
python -m pytest backend/tests

```

**Run the application and API**

Make sure to activate virtual env
```
python -m backend.app

```


**Seed the backend with data**

Make sure to activate virtual env 
```
export SEED_DATA=True && python -m backend.app
```
