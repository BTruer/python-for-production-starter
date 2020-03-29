# Production grade python repo starter
Prereqs:
1. [pyenv](https://github.com/pyenv/pyenv)
2. [pipenv](https://github.com/pypa/pipenv)

## How to use

1. `pyenv install 3.8.0` (basically make sure you have the python version you want)
1.  might need to `pipenv --python /Users/user/.pyenv/versions/3.8.0/bin/python3.8`
2. `pipenv install --dev`
3. `pipenv shell`
4. `pre-commit install`

The following tools have been installed:
1. [flake8](https://medium.com/python-pandemonium/what-is-flake8-and-why-we-should-use-it-b89bd78073f2) - linting tool for clean code
2. [flake8-docstrings](https://gitlab.com/pycqa/flake8-docstrings) - enforces doc strings
3. [black](https://black.readthedocs.io/en/stable/) - auto code formatter:
4. [pre-commit](https://pre-commit.com/) - runs scripts/tools before commiting anything
5. [mypy](http://mypy-lang.org/) - static type checker for Python
6. [tox](https://tox.readthedocs.io/en/latest/) -  automated testing
7. [pydocstyle](https://github.com/PyCQA/pydocstyle) - docstring style checker
8. [pytest](https://docs.pytest.org/en/latest/) - testing framework

TODO:
Add bandit
