# Assimilate Python from Zero

Noah Gift

## Project scafold

* Create GitHub repo: 'assimilate-python'

* Create Conda/Venv, matching reponame: 
```
$ conda create -n assimilate-python python=3 -y
$ conda activate assimilate-python
```

* Create Makefile for common tasks:

In 'Makefile':
```
install:
    pip install --upgrade pip &&\
        pip install -r requirements.txt
```

* Test Python Script

In 'hello.py':
```
#!usr/bin/env python
print("hello")
```

1. Change permission: $ chmod +x hello.py
2. Run with:          $ ./hello.py

