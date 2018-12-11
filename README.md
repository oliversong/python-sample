# Sample Python Repo

This is a sample repo. Use this to make sure that setting up a Python environment
works properly before the day of your onsite.

This is not an interview question; you will not be evaluated for this.

## Setup steps

1. `git clone` this repo
2. `cd` into the project directory
3. install python if you do not already have it
4. install pip if you do not already have it
5. install virtualenv if you do not already have it

```
pip install virtualenv
```

6. create a virtualenv for the repo

```
virtualenv env
```

7. activate the env

```
source env/bin/activate
```

8. install requirements

```
pip install -r requirements.txt
```

9. run pytest

```
pytest
```
