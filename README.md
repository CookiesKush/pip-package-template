<h1 align="center">Welcome to pip package template 👋</h1>
<p align="center">
  <img alt="Version" src="https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000" />
  <a href="https://github.com/kefranabg/readme-md-generator/graphs/commit-activity" target="_blank">
    <img alt="Maintenance" src="https://img.shields.io/badge/Maintained%3F-no-red.svg" />
  </a>
  <a href="https://github.com/Callumgm/How-to-create-a-pip-package-for-noobs/blob/master/LICENSE" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/license-MIT-yellow.svg" />
  </a>
  <a href="https://twitter.com/Flashouttt" target="_blank">
    <img alt="Twitter: Flashouttt" src="https://img.shields.io/twitter/follow/Flashouttt.svg?style=social" />
  </a>
</p>

> pip package template perfect for noobs with easy straight forward instructions

## Install

```
Download or Gitclone this project
```



## Usage

1. Make sure to ofc have [Python 3.9.7](https://www.python.org/ftp/python/3.9.7/python-3.9.7-amd64.exe) downloaded & added to PATH
2. Open powershell and cd to the project directory
3. Login or create a [pypi](https://pypi.org/) account 
4. Open `setup.up` 
    - Replace `PACKAGE_NAME_HERE` at line 7 with your desired package name 
    - Then replace the folder named `PACKAGE_NAME_HERE` to your desired package name
5. Install twine if you don't have it using `pip install twine`
6. Run these commands
```
python setup.py sdist
python -m twine upload dist/*
```
7. You will then be asked to enter your pypi account details once done u can view your package at the link given



## Update

1. Open powershell and cd to the project directory
2. Open `__init__.py` 
    - And update the version number
3. Run these commands 
```
pip install -e .
python setup.py sdist python setup.py 
bdist_wheel --universal
twine upload dist/*
```
4. You will then be asked to enter your pypi account details once done u can view your package at the link given 

*(u don't have to install new updated version using pip since `pip install -e .` installs it for you)*

## Author

👤 **CookiesKush420**

* Website: http://cookiesservices.xyz/
* Twitter: [@Flashouttt](https://twitter.com/Flashouttt)
* GitHub: [@Callumgm](https://github.com/Callumgm)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/Callumgm/How-to-create-a-pip-package-for-noobs/issues). 

## Show your support

Give a ⭐️ if this project helped you!

## 📝 License

Copyright © 2022 [CookiesKush420](https://github.com/Callumgm).<br />
This project is [MIT](https://github.com/Callumgm/How-to-create-a-pip-package-for-noobs/blob/master/LICENSE) licensed.
