# python-template

Modifying the approach from Noah Gift (Assimilate Python)

## Project scafold

* Create GitHub repo: 'python-template'

* Create Conda/Venv, matching reponame: 
```
$ conda create -n python-template python=3 -y
$ conda activate python-template
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

