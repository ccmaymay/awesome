# Awesome Software
A curated collection of software tools and libraries that I find rather awesome. :)

## Python

* [`click`](https://click.palletsprojects.com/) helps you build command-line interfaces quickly, requiring much less boilerplate than `argparse` while maintaining plenty of flexibility.
* [`fastapi`](https://fastapi.tiangolo.com/) helps you build web services (APIs) quickly, requiring much less boilerplate and customization than rolling your own solution via `bottle` or `flask`.  FastAPI integrates with ASGI web servers like Uvicorn and Hypercorn and is not limited to development settings.
* [`flake8`](https://flake8.pycqa.org/en/latest/) performs basic static analysis of Python code and checks code style against [PEP 8](https://peps.python.org/pep-0008/).  Beyond enforcing style, it also highlights symptoms of potential problems like unexpected indentation and undeclared variables.  [`autopep8`](https://pypi.org/project/autopep8/) is the automatic code formatter corresponding to flake8.
* [`pydantic`](https://docs.pydantic.dev/) is the data validation and parsing library underlying FastAPI, and it is very useful itself.  I'm particularly fond of [its settings functionality](https://docs.pydantic.dev/latest/usage/pydantic_settings/), which streamlines [configuring an application via environment variables](https://12factor.net/config) (and, optionally, dotenv files).

## TBA
* cached-path
* humanfriendly
* jsonlines
* overrides
* python-redis-cache
* requests-cache
* word2number
* Docker: curlimages/curl
* Docker: nginx
* JSON Typedef
