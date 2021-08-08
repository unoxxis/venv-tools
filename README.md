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

### venv-setup
Set up a virtual environment for a specific python version, and fill it with requirements.
Can handle preexisting environments.

Usage `venv-setup -n <venv> -p <py version> -r <reqs1.txt> -r <reqs2.txt>`
More options see `venv-setup -h`.