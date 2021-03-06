# APP Pipenv
![Python](https://img.shields.io/badge/Python-3.7-brightgreen.svg)

A simple *Flask* application "Hello, Earth!" using `Pipenv` and `Python 3.7.4`.

> Pipenv is both a package and virtual environment management tool.



### Cloning this repo

You can clone this repository by using:
 
 `git clone git@github.com:mariahsonja/app_pipenv.git`
 
 
 
### Installing Pre-requisites

The prerequisites for this project are located on `Pipfile` and `Pipfile.lock`. You can manually install them or:


`pipenv install --dev`


> The Pipfile specifies packages requirements for a Python application or library - to development and execution.
>
> The Pipfile.lock specifies the version of the packages present in Pipfile to be used. It eliminates the risk of automatically upgrading packages that depend upon each other and break of the project dependency tree.
>


 
### Running locally

When running locally the **app_pipenv** application you will need to:


`pipenv install` 


Next, you will need to create a new virtual environment.


`pipenv shell`


Now, to run the app, you need to: 


`FLASK_APP=app.app flask run`



#### Referencies

- Pipenv: https://github.com/pypa/pipenv

**Thank you!**
