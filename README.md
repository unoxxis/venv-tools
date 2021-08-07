# venv-tools
A collection of scripts to manage virtual environments using [pyenv](https://github.com/pyenv/pyenv) and [pyenv-virtualenv](https://github.com/pyenv/pyenv-virtualenv).

## Scripts

### venv-version-check
Check if the virtual environment uses the correct python version

Usage `venv-version-check <venv> <target version>`. Returns `0` on correct version, and `1` on incorrect version and `2` if `venv` does not exist.

If `<target version>` is omitted, print python version of `<venv>` to stdout.

### venv-create
Creates a virtual environment for a specified python version and name. Ensures that the
python version requested is installed.

Usage `venv-create <venv> <target version>`