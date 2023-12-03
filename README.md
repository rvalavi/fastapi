# API for PostgreSQL database using FastAPI
 FastAPI for PostgreSQL database

## Installing
First create a Python environment and activate it:

```bash
# mkdir ~/fastapi
cd ~/fastapi
python -m venv ./venv

```

```bash
# cd ~/fastapi
source ./venv/bin/activate
```

Now install all the Python packages and save the into the `requirements.txt` file.

```bash
# install packages with pip
pip install fastapi "uvicorn[standard]"

# freeze packages
pip freeze > requirements.txt
```

This will be used to install the required package in the docker image or AWS lambda.

Use `pip` to install the packages in a different system or in docker images:

```bash
pip install -r requirements.txt
```