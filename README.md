# MyFastAPI

An API created from the FastAPI python framework.\
This was created from following a freeCodeCamp.org tutorial.

## Running the app

Install the necessary packages from pip.
```
pip install fastapi
pip install uvicorn
```

Run the app.
```
uvicorn myapi:app
```

Access the api docs using `{URL_PATH}/docs`

## Development

Run the app with an additional parameter, to reload the web server on file changes
```
uvicorn myapi:app --reload
```
