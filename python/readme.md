# Python commands

## Table of Contents

- [Virtual Environment](#virtual_environment)
- [Generate `requirements.txt`](#generate-requirementstxt)


## Virtual Environment

Create and activate a virtual environment:

```bash
py -m venv env
```
macOS/Linux

```bash
source ./env/scripts/activate
```
Windows

```bash
./env/scripts/activate
```
Deactivate

```bash
deactivate
```

## Generate `requirements.txt`

Generate a `requirements.txt` file with all installed packages

```bash
pip freeze > requirements.txt
