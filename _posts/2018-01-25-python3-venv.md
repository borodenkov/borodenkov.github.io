---
layout: post
title: Виртуальное окружение в python3.6
date: '2018-01-25 00:00:00'
tags:
- python
- venv
---

#VirtualEnv

```code
$ python -m venv .venv
$ . .venv/bin/activate
(.venv) $ pip install django
(.venv) $ pip freeze > requirements.txt
```


#Intro to pip-tools
```code
$ [sudo] pip install pip-tools
$ echo django >> requirements.in
$ pip-compile --output-file requirements.txt requirements.in
```