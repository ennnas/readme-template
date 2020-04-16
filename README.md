# Product Name
> Short blurb about what your product does.

[![Python 3.7](https://img.shields.io/badge/Python-3.7-green.svg)](https://shields.io/)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

One to two paragraph statement about your product and what it does.

![](header.png)

## Development setup

You need to install the following software:

* Python ≥ 3.7 (older versions are not supported)
* [poetry](https://python-poetry.org/) ≥ 1.0

### Poetry installation
To install and configure `poetry` run 
```shell script
curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python3
poetry config virtualenvs.in-project true
```

## Installation

First, to install all the required dependencies run
```shell script
poetry install
```

You now have access to these entry points (executables) in your virtual environment:

* `entrypoint`: description of what it does 
* `another_entrypoint`: description of what it does

All these entry points accept multiple options. To obtain documentation for any one of them, run it with the `-h` flag.
Example:

```bash
$ entrypoint -h

PUT THE SHELL OUTPUT HERE
```

## Usage example

A few motivating and useful examples of how your product can be used. Spice this up with code blocks and potentially more screenshots.

_For more examples and usage, please refer to the [Wiki][wiki]._


## Release History

* 0.1.1
    * FIX: Crash when calling `baz()`
* 0.1.0
    * The first proper release
    * CHANGE: Rename `foo()` to `bar()`
* 0.0.1
    * Work in progress

## Meta

Ennio Nasca – [@YourTwitter](https://twitter.com/dbader_org) – nascae@example.com

Distributed under the XYZ license. See ``LICENSE`` for more information.

[https://github.com/yourname/github-link](https://github.com/dbader/)

## Contributing

Tho contribute to this project follow this steps:

1. Fork it (<https://github.com/yourname/yourproject/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request


