## 仮想環境の作成
### py -3 -m venv venv 

## 仮想環境をactivate
### venv\Scripts\activate

## Flaskをinstall
### pip install Flask 

## Flaskアプリを設定
### set FLASK_APP=アプリ名　例）set FLASK_APP=app

## デバックモード
### set FLASK_ENV=development

## サーバ立ち上げ
### flask run

## データベース作成
### from app import db → db.create_all()

## bootstrapの適用(普通のbootstrapではなくflask-bootstrap)
### pip install flask-bootstrap
