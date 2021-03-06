[![Build Status](https://api.travis-ci.com/sportorg/pysport.svg?branch=develop)](https://travis-ci.com/sportorg/pysport)
[![Python 3.8](https://img.shields.io/badge/python-v3.8-blue.svg?logo=pythonlang)](https://www.python.org/downloads/)
[![License: GPL v3](https://img.shields.io/badge/license-GPLv3-blue.svg)](https://github.com/sportorg/pysport/blob/develop/LICENSE)
[![Orienteering](https://img.shields.io/badge/sport-orienteering-blue.svg)](https://github.com/sportorg)
[![Sportorg version](https://img.shields.io/github/v/release/sportorg/pysport)](https://github.com/sportorg/pysport)
[![Orienteering](https://img.shields.io/github/stars/sportorg/pysport?style=social)](https://github.com/sportorg/pysport)

# SportOrg

```commandline
pip install poetry
poetry install
poetry install -E win  # for Windows
```

Run

Add `DEBUG=True` to `.env` file or `cp .env.example .env`

```commandline
poetry run python SportOrg.pyw
```

![Mainwindow sportorg](img/mainwindow.png)

![Dialogedit sportorg](img/dialogedit.png)
![Bibprintout sportorg](img/bibprintout.png)


## build

### cx_Freeze

`python setup_.py build`


## Roadmap

- [ ] Publish to pypi
- [ ] Deploy to telegram
