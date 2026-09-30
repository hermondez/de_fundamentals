# Python Commands

## Quick Reference
python --version                            → show Python version
python                                      → open Python interactive shell
python <file>.py                            → run Python script
python -c "<code>"                          → run Python code directly

which python                                → show Python executable location
python -m pip --version                     → show pip version
python -m pip list                          → list installed packages
python -m pip show <package>                → show package information
python -m pip freeze                        → list installed packages and versions

python -m pip install <pkg>                 → install package
python -m pip uninstall <pkg>               → uninstall package
python -m pip install --upgrade <pkg>       → upgrade package

python -m venv .venv                        → create virtual environment
python -m pip freeze > requirements.txt     → save dependencies

python -m pip install -r requirements.txt   → install dependencies from file


## Running Python
python script.py
python -c "print('Hello World')"


## Packages
python -m pip install pandas
python -m pip uninstall pandas
python -m pip list
python -m pip show pandas
python -m pip freeze


## Dependencies
python -m pip freeze > requirements.txt
python -m pip install -r requirements.txt


## Virtual Environment
python -m venv .venv
source .venv/bin/activate or deactivate


## Useful Checks
python --version
which python
python -m pip --version
python -m pip list

