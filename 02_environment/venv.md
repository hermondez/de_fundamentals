# Python Virtual Environments
python -m venv .venv          → create virtual environment
source .venv/bin/activate     → activate environment
deactivate                    → deactivate environment
which python                  → verify active Python
python --version              → check Python version

## Create & Activate
python -m venv .venv
source .venv/bin/activate

## Verify
which python
python --version

-- The Python path should point to:
    .venv/bin/python

## Deactivate
deactivate

## Recreate Environment
rm -rf .venv
python -m venv .venv
source .venv/bin/activate

## Project Convention
project/
├── .venv/
├── src/
├── tests/
├── .gitignore
└── requirements.txt