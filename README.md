# Setup

This assumes you already have pyenv and poetry installed.

Pyenv is used for python version management, and poetry is for package management. 

If you don't have either, installation instructions are on pyenv and poetry's websites, respectively. 

```
# set up virtual environment
poetry init
poetry add pandas ipykernel jupyter

# start jupyter notebook
poetry run jupyter notebook
```
