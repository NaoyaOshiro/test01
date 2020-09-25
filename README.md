## [HouseQR](http://houseqr.ryukyuupdate.com)
---
#### このリポジトリは主に Amazon Connect で IVR の処理を行うためのバックエンドプログラムです。
 
 

## HouseQR
--- 
#### このリポジトリは主に通知系の処理を行うためのプログラムです。
##### my_email.py は SendGrid のライブラリを利用し通知メールなどの送信を行います。
##### my_call.py は Amazon Connect のライブラリを利用し通知電話などの発信を行います。
 
 
 
## HouseQR
---
#### このリポジトリは主にフロントエンド、DBと連携しバックエンド処理全般を行うためのバックエンドプログラムです。
##### my_api.py はAPIのURLごとに関数を用意し my_mysql.py をインポートしCRUD処理を行います。
##### my_mysql.py はMySQLのライブラリ、mysql.connector を利用し AWS RDS へSQLを実行します。
