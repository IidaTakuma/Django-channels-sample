# Readme

## Overview
djangoでwebsocket通信を行うための機能サンプル

[チュートリアル](https://channels.readthedocs.io/en/latest/tutorial/part_1.html)

## Version
チュートリアル通りに進めて動作が確認できたもの
```
Python 3.8.1
Django 3.1.7
channels 3.0.3
channels-redis 3.2.0
```

## SetUp
```
pipenv install
pipenv python manage.py runserver
```

## Operation Check
1. `http://127.0.0.1:8000/chat/<room_name>/` にブラウザの2つのウィンドウでアクセス(room_nameは同一)．
2. 一方のウィンドウの入力がもう片方のウィンドウに表示されれば正しく動作している．
