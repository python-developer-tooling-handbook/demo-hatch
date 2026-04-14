# Hatch

This is a companion example for the [Hatch](https://pydevtools.com/handbook/reference/hatch/) reference page on the [Python Developer Tooling Handbook](https://pydevtools.com).

This package is an example project for building a Python package (i.e., wheel or sdist).
It relies on [Hatch](https://hatch.pypa.io/) as a build backend with `pyproject.toml`
for configuration.

## Commands:

* Setting up the project environment:
```shell
hatch env create
```
* Activating the project environment:
```shell
hatch shell
```
* Run code in the project environment:
```shell
hatch run python -c "import demo"
```
* Build:
```shell
hatch build
```
* Upload to PyPI:
```shell
hatch publish
```