### How to deploy it (on a Linux machine):

First of all, clone this repository:

    git clone https://github.com/codepictor/net.git
    cd net/

Create a new virtual environment

    virtualenv --python=python3.6 shopenv

Activate the environment

    source shopenv/bin/activate

Install required dependencies

    pip install -r net/requirements.txt

Run test server

    python net/manage.py runserver

Check localhost:8000 in your browser and have fun!
