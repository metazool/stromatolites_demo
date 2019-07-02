# Postgres

Run in docker via docker-compose.yml in this directory:

* `docker-compose up -d`

## Setup

* `make local_setup` - create various tables based on the seed data

# Python

Is 2.7 specific. Create a virtualenv and install dependencies

 * `python2.7 -m pip install virtualenv`
 * `python2.7 -m virtualenv env`
 * `. ./env/bin/activate`
 * `pip install -r requirements.txt`

## Finally

 * `python run.py` - see output and dump results.csv




