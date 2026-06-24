# Flask Task

## Overview
Example of a Task Manager Application built using Python Flask, with a MongoDB in Docker.

## Implementation
The categories in the Task Manager are implemented as separate collections in the MongoDB.

## Installation

Clone the repository:

```bash
git clone https://github.com/richardadalton/flask_task.git
cd flask_task
```

Create the virtual environment and install dependencies:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Running locally (PyCharm + Docker MongoDB)

Start MongoDB in Docker:

```bash
docker compose up -d
```

Then run `app.py` from PyCharm or the terminal:

```bash
python app.py
```

The app will be available at http://localhost:5000. No environment variables or configuration needed.

## Running fully containerised

```bash
docker compose --profile full up --build
```

Both MongoDB and the Flask app will start. The app will be available at http://localhost:5000.
