# Awesome Software
A short list of software tools and libraries that I think are awesome :)

## Bash

### Development

* [`shellcheck`](https://github.com/koalaman/shellcheck) performs linting of bash scripts, highlighting "gotchas" in which bash behaves counterintuitively.

## JavaScript

### Development

* [`prettier`](https://prettier.io) is an opinionated, no/low-configuration code formatter for JavaScript and other web languages (including Vue, HTML, CSS, TypeScript, and JSON).  It has plugins for vim, VS Code, and other editors that automatically format a file on save.  I love getting reasonably formatted code on the default settings and having one less configuration file to worry about!

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

## Databases

* [`redis`](https://redis.io/docs/getting-started/) ([python client library](https://github.com/redis/redis-py)) is an in-memory key-value store.  It strikes a nice balance between performance, versatility, and ease of use.  It is easy to install and run locally (from your home directory); it supports data structures like lists, hashes, and sorted sets; if you're using it for a simple key-value cache, it has builtin TTL/expire functionality and a variety of [configuration options for key eviction](https://redis.io/docs/reference/eviction/).  I've used it in a variety of applications and the main limitation I've come across is that each simple value, list item, hash value, etc. has a max size of 512 MB.

## TBA
* cached-path
* python-redis-cache
* requests-cache
* thefuzz
* Docker: curlimages/curl
* Docker: nginx
