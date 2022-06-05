Python api example project

## Steps to run the api locally
#### 1. Pre-requisites
- Ensure [the poetry is installed](https://python-poetry.org/docs/#installation)
- Check venv path of poetry by running 'poetry env info' 
- Copy the venv path and add it to your Python intepreter path 

#### 2. Install dependencies
```
  poetry install
```
#### 3. Launch the app (from root folder of project)
```
  uvicorn src.main:app --reload
```
```
  Call the API running locally on: http://127.0.0.1:8000
```

## Code formatting
Save brainpower and let the [Black](https://black.readthedocs.io) does the work. 

Before commiting the code, run the following command:

```
  black ./src
```

The source code will be re-formatted by Black's sensible default config