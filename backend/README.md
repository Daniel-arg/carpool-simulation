# How to run

Create a virtual environment

```console
python3 -m venv env
```

Activate it

```console
source env/bin/activate
```

Install dependencies

```console
pip install -r requirements.txt
```

Deactivate

```console
deactivate
```

You may need to add this line to your `settings.json` file

```json
"python.defaultInterpreterPath": "./backend/env/bin/python"
```