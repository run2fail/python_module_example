# About
Python package example based on https://packaging.python.org/tutorials/packaging-projects/

Further information can be found here: https://packaging.python.org/guides/distributing-packages-using-setuptools/

# Install Dependencies
```
python3 -m pip install --upgrade setuptools wheel
python3 -m pip install -r requirements.txt
```

# Building
```
python3 setup.py sdist bdist_wheel
```

# Updating Dependencies
```
python3 -m pip freeze > requirements.txt
```

# Upload to PyPI Repository
```
twine upload --repository-url https://test.pypi.org/legacy/ dist/*
```

# Installing the Module
```
python3 -m pip install --index-url https://test.pypi.org/simple/ example
```

