# PIP is basically how to manage packages

## Python pip
python -m pip --version                         → show pip version
python -m pip list                              → list installed packages
python -m pip show <package>                    → show package information
python -m pip install <package>                 → install package
python -m pip uninstall <package>               → uninstall package
python -m pip install --upgrade <package>       → upgrade package
python -m pip freeze                            → list installed packages and versions
python -m pip freeze > requirements.txt         → save installed packages to requirements.txt
python -m pip install -r requirements.txt       → install packages from requirements.txt

## Common Packages
python -m pip install pandas
python -m pip install numpy
python -m pip install requests
python -m pip install pytest

## Common Workflow
python -m pip install pandas
python -m pip freeze > requirements.txt
python -m pip install -r requirements.txt

## Useful Checks
python -m pip --version
python -m pip list
python -m pip show pandas
