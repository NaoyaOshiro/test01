### このリポジトリは主に Amazon Connect で IVR の処理を行うためのバックエンドプログラムです。
 
 
 
### このリポジトリは主に通知系の処理を行うためのプログラムです。
#### my_email.py は SendGrid のライブラリを利用し通知メールなどの送信を行います。
#### my_call.py は Amazon Connect のライブラリを利用し通知電話などの発信を行います。
 
 
 
 
### このリポジトリは主にフロントエンド、DBと連携しバックエンド処理全般を行うためのバックエンドプログラムです。
#### my_api.py はAPIのURLごとに関数を用意しCRUD処理を行います。
#### my_mysql.py は MySQL ライブラリ、mysql.connector を利用し AWS RDS へSQLを実行します。
