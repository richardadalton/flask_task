# Flask Task

## Overview
Example of a Task Manager Application built using Python Flask, with a MongoDB in Docker.

## Implementation
The categories in the Task Manager are implemented as separate collections in the MongoDB.

## Installation

Just clone this repository

```bash
$ git clone https://github.com/richardadalton/flask_task.git
```

Create the virtual environment, and install dependencies.

```bash
$ python3 -m venv .venv
$ . .venv/bin/activate
$ pip install -r requirements.txt
```

Edit the docker-compose.yml file to set the root user name and password.
Run the Docker container.

```bash
$ docker-compose up
```

Edit the PyCharm run configuration to set the username and password in the MONGO_URI env variable.


## Running the task manager

Run using the Run Configuration in PyCharm.

