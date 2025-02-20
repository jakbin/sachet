# apt-pro

A python package for better update and manage your debian packages.

[![Python package](https://github.com/jakbin/apt-pro/actions/workflows/publish.yml/badge.svg)](https://github.com/jakbin/apt-pro/actions/workflows/publish.yml)
[![PyPI version](https://badge.fury.io/py/apt-pro.svg)](https://pypi.org/project/apt-pro)
[![Downloads](https://pepy.tech/badge/apt-pro/month)](https://pepy.tech/project/apt-pro)
[![Downloads](https://static.pepy.tech/personalized-badge/apt-pro?period=total&units=international_system&left_color=green&right_color=blue&left_text=Total%20Downloads)](https://pepy.tech/project/apt-pro)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/jakbin/apt-pro)
![GitHub last commit](https://img.shields.io/github/last-commit/jakbin/apt-pro)

## Introduction

When you run "apt list --upgradable" in your terminal, you find around 1000 upgradable packages (if you are using parrot os or kali linux like distibution). It hard to find your important package or security releases.  

For this solution, here is "apt-pro".

## Demo

![Demo](demo/demo.png)

### Add and Remove package from your list
![Demo](demo/demo2.png)

### Upgrade packages matching a pattern only from apt upgradable list
![Demo](demo/demo3.png)

## Compatability

Python 3.6+ is required.

## Installation

```sh
pip install apt-pro
```

or 

```sh
pip3 install apt-pro
```

## Then run it with:

```sh
apt-pro -h
```

## Todo-List

- [x] Pretty Output 
- [x] Update and upgrade packages from Here
- [x] Add or Remove packages form list
- [x] Use sqlite 
