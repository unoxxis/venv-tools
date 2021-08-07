# venv-tools
A collection of scripts to manage virtual environments using [pyenv](https://github.com/pyenv/pyenv) and [pyenv-virtualenv](https://github.com/pyenv/pyenv-virtualenv).

## Scripts

### venv-version-check
Check if the virtual environment uses the correct python version

Usage `venv-version-check <venv> <target version>`. Returns `0` on correct version, and `1` on incorrect version and `2` if `venv` does not exist.