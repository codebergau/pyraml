# [PyRAML](https://github.com/salsita/pyraml) <a href='https://github.com/salsita'><img align='right' title='Salsita' src='https://www.google.com/a/cpanel/salsitasoft.com/images/logo.gif?alpha=1' /></a>

[RAML (REST API Markup Language)](http://raml.org/) enhanced loader, parameter converter, and API wrapper.

[![Version](https://img.shields.io/github/tag/salsita/pyraml.svg?label=version)]
(https://github.com/salsita/pyraml/tags)
[![PyPI package](https://img.shields.io/pypi/v/PyRAML.svg?label=pypi+package)]
(https://pypi.python.org/pypi/PyRAML/)
[![Downloads](https://img.shields.io/pypi/dm/PyRAML.svg)]
(https://pypi.python.org/pypi/PyRAML/)
[![Supported Python versions](https://img.shields.io/pypi/pyversions/PyRAML.svg)]
(https://pypi.python.org/pypi/PyRAML/)
[![License](https://img.shields.io/pypi/l/PyRAML.svg)]
(https://pypi.python.org/pypi/PyRAML/)


## Supported Platforms

* [Python](http://www.python.org/) >= 2.6, 3.3


## Get Started

Install using [pip](https://pip.pypa.io/) or [easy_install](http://pythonhosted.org/setuptools/easy_install.html):
```bash
pip install PyRAML
easy_install PyRAML
```

Optionally, you can specify `yaml` or `raml` extras to install related dependencies:
```bash
pip install "PyRAML[yaml,raml]"
easy_install "PyRAML[yaml,raml]"
```

## Features

- Load [RAML](http://raml.org/) API specification stored in any of supported markup languages using [PyDataLoader](https://github.com/salsita/pydataloader).
  - Support [YAML](http://yaml.org/) using [PyYAML](http://pyyaml.org/wiki/PyYAML).
  - Support [RAML](http://raml.org/) using [pyraml-parser](https://github.com/an2deg/pyraml-parser).
  - Support [JSON](http://json.org/) using [Python 2.6+ json module](https://docs.python.org/2/library/json.html), or [Python 3.x json module](https://docs.python.org/3/library/json.html).
- Provide extensible API model with access to resources and methods.
- Provide extensible parameter converter and validator.

## Changelog

### 0.2.0

#### Features

- Add AuthError exception.

#### Fixes

- Fix API options issues.
- Update dependencies to support Python 3.
- Fix package setup on Python 3.

### 0.1.9

#### Fixes

- Fix Python 2.6 support with updated PyDataLoader 0.1.2.

### 0.1.8

#### Fixes

- Fix Python 2.6 support.

### 0.1.7

#### Fixes

- Fix RAML loader to not fail on method-less resources, or empty responses and bodies.

### 0.1.6

#### Features

- Add default option to ignore empty parameters unless '' is specified in enum.

### 0.1.5

#### Fixes

- Fix package setup to not require dependencies preinstalled.

### 0.1.4

#### Features

- Initial release.

#### Fixes

- PyPI package structure.
