# DEPENDENCIES is how a project records and reproduces its packages

# Python Dependencies
requirements.txt                                        → list of project dependencies
python -m pip freeze                                    → list installed packages and versions
python -m pip freeze > requirements.txt                 → save installed packages to requirements.txt
python -m pip install -r requirements.txt               → install packages from requirements.txt
python -m pip install --upgrade -r requirements.txt     → upgrade packages from requirements.txt
python -m pip install <package>                         → install a package
python -m pip uninstall <package>                       → uninstall a package
python -m pip install --upgrade <package>               → upgrade a package
python -m pip list                                      → list installed packages
python -m pip show <package>                            → show package information

## Common Workflow
python -m pip install pandas
python -m pip install pytest
python -m pip freeze > requirements.txt
python -m pip install -r requirements.txt
