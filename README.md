# Cookiecutters 🍪

Automate repetition away... 

## Prerequisites

- installation of [Python3](https://www.python.org) on your machine  
- installation of [cookiecutter](https://cookiecutter.readthedocs.io/en/2.0.2/installation.html) on your machine
- installation of [pipenv](https://docs.pipenv.org) on your machine (to create virtual environment and install dependencies within ve)

## Steps

1. Navigate to desired folder on your machine and generate your project structure from GitHub project template: 
`$ cookiecutter https://github.com/IBronko/Cookiecutters_Basic_Data_Science.git`

To generate a project from a local cookiecutter template type and follow the displayed prompts:
`$ cookiecutter .`

2. Adjust Pipfile if necessary (include or exclude packages)

3. Create virtual environment for your project and install requirements of template from included pipfile: 
`$ pipenv install`

## Virtual environment basics with pipenv

1. Activate: `$ pipenv shell`

2. Deactivate: `$ pipenv exit`

3. Commands overview: 2. Deactivate: `$ pipenv -h`

