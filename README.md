# Poetry Study

[Official Documentation](https://python-poetry.org/docs/basic-usage/)

[Tutorial](https://dev.to/ciphertron/beauty-of-poetry-1ne8)

## Installation

<https://python-poetry.org/docs/#installation>

## Configuration

Allow Poetry to create .venv folder in each project folder, instead of using the default virtualenvs directory in {cache-dir}/virtualenvs:

````bash
poetry config virtualenvs.in-project true
````

## Usage

Starting a new project with poetry:

````bash
poetry new poetry-study --name src
cd poetry-study
````

Accessing virtual enviroment mode:

````bash
poetry shell
````

Install project dependencies:

````bash
poetry add flask
````

Run Python code with Poetry:

````bash
poetry run python ./src/main.py
````
