# pisense setup

Dependencies for building pisense

```zsh
$ sudo apt-get install libjpeg-dev zlib1g-dev
```

Keep things sanitary by using virtualenv


``` zsh
$ python3.7 -m venv ~/.virtualenvs/sense
$ source  ~/.virtualenvs/sense/bin/activate
$ pip install -U pip
$ pip install wheel
```
