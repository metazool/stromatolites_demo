# Linux

# Postgres

Run in docker via docker-compose.yml in this directory:

* `docker-compose up -d`

## Setup

* `make local_setup` - create various tables based on the seed data

## Client

* `sudo apt install postgresql-client`

# Python

Is 2.7 specific. Create a virtualenv and install dependencies

 * `python2.7 -m pip install virtualenv`
 * `python2.7 -m virtualenv env`
 * `. ./env/bin/activate`
 * `pip install -r requirements.txt`

## Finally

 * `python run.py` - see output and dump results.csv

# Windows

Postgres installer - https://www.postgresql.org/download/windows/

Add `C:\Program Files\PostgreSQL\11\bin` in PATH (Search for Edit environment variables)

## Python

Creating a python2 virtual environment

```
C:\Python27\python.exe -m pip install virtualenv

C:\Python27\python.exe -m virtualenv pyenv

.\py2env\Scripts\activate

pip install -r .\requirements.txt

```

Run database setup script

* `python setup\setup.py`

Run application demo

* `python run.py`






