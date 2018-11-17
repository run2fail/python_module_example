# About
Python package example based on https://packaging.python.org/tutorials/packaging-projects/

# Dependencies
```
python3 -m pip install --upgrade setuptools wheel twine
```

# Building
```
python3 setup.py sdist bdist_wheel
```

# Upload to PyPI Repository
```
twine upload --repository-url https://test.pypi.org/legacy/ dist/*
```

# Installing the Module
```
python3 -m pip install --index-url https://test.pypi.org/simple/ example
```

