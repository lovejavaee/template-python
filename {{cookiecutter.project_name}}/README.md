{{cookiecutter.project_name}}
======
{{cookiecutter.project_short_description}}

[![Build Status](http://img.shields.io/travis/{{cookiecutter.github_username}}/{{cookiecutter.github_repo}}/master.svg)](https://travis-ci.org/{{cookiecutter.github_username}}/{{cookiecutter.github_repo}})
[![Coverage Status](http://img.shields.io/coveralls/{{cookiecutter.github_username}}/{{cookiecutter.github_repo}}/master.svg)](https://coveralls.io/r/{{cookiecutter.github_username}}/{{cookiecutter.github_repo}})
[![Scrutinizer Code Quality](http://img.shields.io/scrutinizer/g/{{cookiecutter.github_username}}/{{cookiecutter.github_repo}}.svg)](https://scrutinizer-ci.com/g/{{cookiecutter.github_username}}/{{cookiecutter.github_repo}}/?branch=master)
[![PyPI Version](http://img.shields.io/pypi/v/{{cookiecutter.project_name}}.svg)](https://pypi.python.org/pypi/{{cookiecutter.project_name}})
[![PyPI Downloads](http://img.shields.io/pypi/dm/{{cookiecutter.project_name}}.svg)](https://pypi.python.org/pypi/{{cookiecutter.project_name}})


Getting Started
===============

Requirements
------------

* Python 2.7+ or Python 3.3+

Installation
------------

{{cookiecutter.project_name}} can be installed with pip:

```
$ pip install {{cookiecutter.project_name}}
```

or directly from the source code:

```
$ git clone https://github.com/{{cookiecutter.github_username}}/{{cookiecutter.github_repo}}.git
$ cd {{cookiecutter.github_repo}}
$ python setup.py install
```

Basic Usage
===========

After installation, the package can imported:

```
$ python
>>> import {{cookiecutter.package_name}}
>>> {{cookiecutter.package_name}}.__version__
```

{{cookiecutter.project_name}} doesn't do anything, it's a template.
