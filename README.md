# Production grade python repo starter
Prereqs:
1. [pyenv](https://github.com/pyenv/pyenv)
2. [pipenv](https://github.com/pypa/pipenv)

## How to use

0. Pick a python version (set to 3.7.0 by default) and update the following files to match that version: tox.ini, pyproject.toml, .pre-commit-config.yaml, .python-version, Pipfile, mypy.ini
1. Install the python version you want `pyenv install 3.7.0` 
1. Point pipenv to the python version `pipenv --python /Users/user/.pyenv/versions/3.7.0/bin/python3.7`
2. `pipenv install --dev`
3. `pipenv shell`
4. `pre-commit install`

The following tools have been installed:
1. [flake8](https://medium.com/python-pandemonium/what-is-flake8-and-why-we-should-use-it-b89bd78073f2) - linting tool for clean code
2. [flake8-docstrings](https://gitlab.com/pycqa/flake8-docstrings) - enforces doc strings
3. [black](https://black.readthedocs.io/en/stable/) - auto code formatter
4. [pre-commit](https://pre-commit.com/) - runs scripts/tools before commiting anything
5. [mypy](http://mypy-lang.org/) - static type checker for Python
6. [tox](https://tox.readthedocs.io/en/latest/) - automated testing
7. [pytest](https://docs.pytest.org/en/latest/) - testing framework

To change the version of Python you will need to change the python version references on all configuration files.

TODO:
Add [bandit](https://github.com/PyCQA/bandit) for security and [logging standards](https://docs.python-guide.org/writing/logging/)
