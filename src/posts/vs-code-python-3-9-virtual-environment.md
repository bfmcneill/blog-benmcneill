---
title: Windows10 + VSCode + Python 3.9 Virtual Environment
description: How to setup a  virtual environment with vscode and python39
author: Ben McNeill
date: 2021-08-18T06:26:57.111Z
tags:
  - python
---

https://youtu.be/iIf1jtywd_A

## steps

1. verify python is installed
2. create virtual environment
3. upgrade pip
4. activate virtual environment

## verify python is installed

```bash
python -V
```

## create virtual environment

```bash
python -m venv .venv
```

## upgrade pip

```bash
.venv\scripts\python -m pip install --upgrade pip
```

## activate virtual environment

```bash
.venv\scripts\activate
```
