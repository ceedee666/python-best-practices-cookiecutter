# Python Best Practices Cookiecutter

Best practices [cookiecutter](https://github.com/audreyr/cookiecutter) template as described in this [blogpost](https://sourcery.ai/blog/python-best-practices/).

## Features
- Testing with [pytest](https://docs.pytest.org/en/latest/)
- Formatting with [black](https://github.com/psf/black)
- Import sorting with [isort](https://github.com/timothycrosley/isort)
- Static typing with [mypy](http://mypy-lang.org/)
- Linting with [flake8](http://flake8.pycqa.org/en/latest/)
- Git hooks that run all the above with [pre-commit](https://pre-commit.com/)
- Deployment ready with [Docker](https://docker.com/)
- Continuous Integration with [GitHub Actions](https://github.com/features/actions)

## Quickstart
```sh
cookiecutter gh:ceedee666/python-best-practices-cookiecutter

# Enter project directory
cd <repo_name>

# Initialise git repo
git init

# Install dependencies
pipenv install --dev

# Setup pre-commit and pre-push hooks
pipenv run pre-commit install -t pre-commit
pipenv run pre-commit install -t pre-push
```
