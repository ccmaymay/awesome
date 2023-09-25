# Awesome Software
A curated collection of software tools and libraries that I find rather awesome. :)

## Bash

### Development

* [`shellcheck`](https://github.com/koalaman/shellcheck) performs linting of bash scripts, highlighting "gotchas" in which bash behaves counterintuitively.

## Python

### Development

* [`flake8`](https://flake8.pycqa.org/en/latest/) performs basic static analysis of Python code and checks code style against [PEP 8](https://peps.python.org/pep-0008/).  Beyond enforcing style, it also highlights symptoms of potential problems like unexpected indentation and undeclared variables.  [`autopep8`](https://pypi.org/project/autopep8/) is the automatic code formatter corresponding to flake8.
* [`mypy`](https://www.mypy-lang.org/) performs static type checking for Python, allowing you to programmatically verify that all of those helpful [type annotations](https://docs.python.org/3/howto/annotations.html) you added to your code actually line up with each other.
* [`overrides`](https://pypi.org/project/overrides/) provides decorators for indicating that a method should override a superclass method, optionally validating that the method signatures match.

### Data and Services

* [`fastapi`](https://fastapi.tiangolo.com/) helps you build web services (APIs) quickly, requiring much less boilerplate and customization than rolling your own solution via `bottle` or `flask`.  FastAPI integrates with ASGI web servers like Uvicorn and Hypercorn and is not limited to development settings.
* [`humanfriendly`](https://pypi.org/project/humanfriendly/) provides tools for performing user-related tasks like converting byte counts to textual descriptions (for example, converting `1408012330` to `"1.41 GB"`).
* [`pydantic`](https://docs.pydantic.dev/) is the data validation and parsing library underlying FastAPI, and it is very useful itself.  I'm particularly fond of [its settings functionality](https://docs.pydantic.dev/latest/usage/pydantic_settings/), which streamlines [configuring an application via environment variables](https://12factor.net/config) (and, optionally, dotenv files).

### Command-Line Interaction

* [`click`](https://click.palletsprojects.com/) helps you build command-line interfaces quickly, requiring much less boilerplate than `argparse` while maintaining plenty of flexibility.  Beyond parsing command-line arguments and generating help text, click can do things like load configuration options from environment variables when present, prompt the user for text, and output colored text when a terminal is detected.

## TBA
* cached-path
* jsonlines
* python-redis-cache
* requests-cache
* thefuzz
* Docker: curlimages/curl
* Docker: nginx
* JSON Typedef
