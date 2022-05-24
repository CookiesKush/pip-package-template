# How to create pip package perfect for noobs
<p align="center">
  <a href="https://github.com/Callumgm">
    <img src="https://img.shields.io/badge/maintained-very little-critical?style=flat-square" alt="Maintained Very Little" />
  </a>
  <img src="https://img.shields.io/badge/python-3.9.7-blue?style=flat-square" alt="Python 3.9.7" />
</p>

## About 

How to create a pip package perfect for noobs with easy straight forward instructions


## How To Upload Template Package

1. Make sure to ofc have [Python 3.9.7](https://www.python.org/ftp/python/3.9.7/python-3.9.7-amd64.exe) downloaded & added to PATH on install
2. Open powershell and cd to the project directory
3. Create a [pypi](https://pypi.org/) account 
4. Open `setup.up` and replace `PACKAGE_NAME_HERE` at line 7 with your desired package name & then replace the folder also named `PACKAGE_NAME_HERE` to your desired package name
5. Install twine if you don't have it using `pip install twine`
6. Run `python setup.py sdist`
7. After thats done run `python -m twine upload dist/*` and enter your pypi account details once done u can view your package at the link given


## How To Update Template Package

1. Open powershell and cd to the project directory
2. Find and open `__init__.py` and update the version number
2. Run `pip install -e .`
3. Once done run `python setup.py sdist`
4. Once done run `python setup.py bdist_wheel --universal`
5. Once done run `twine upload dist/*` and enter your pypi account details once done u can view your package at the link given (u don't have to install new updated version using pip since `pip install -e .` installs it for you)


## Contact
Email - Callumgm20052005@gmail.com



