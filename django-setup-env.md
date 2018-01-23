# Kata 0

On Linux Mint, by default, we are using python 2.7. The latest version of Django require python 3.x.  Python 3.5 is
also installed but not set to be the default.

To change that:

- `sudo update-alternatives --install /usr/bin/python python /usr/bin/python2.7 1`
- `sudo update-alternatives --install /usr/bin/python python /usr/bin/python3.5 2`

Now on, to change the python interpreter, simply do:

- `update-alternatives --config python`


## Install pip

If `pip --version` gives:

`Traceback (most recent call last):`
`  File "/usr/local/bin/pip", line 7, in <module>`
`    from pip import main`
`ImportError: No module named 'pip'`

Then, use the command:

`sudo apt-get install python3-pip`
`sudo apt-get install python3-setuptools`


## Seting up a virtual environment

`python3 -m venv venv`
`source venv/bin/activate`
`pip install --upgrade pip`

## Install django

`pip install Django`
`pip install psycopg2`

Launch the python interpreter by typing `python`:

`>>> import django`
`>>> print(django.get_version())`
`2.0.1`
`>>> exit()`

## Install PostgreSQL

sudo apt-get install postgresql
sudo apt-get install pgadmin3

### TODO: Setup default user / database
