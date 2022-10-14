# AWS-lecture.03/

・　APサーバーの名前とバージョンは

・　Puma version: 5.6.4 

・　サーバー終了時は「コントロール+C」

・　^C- Gracefully stoppingと出てくれば停止

・　再接続は「bundle exec rails s」で出来ました。


・　DBサーバーの名前とバージョンは

・　mysql  Ver 8.0.30 for Linux on x86_64 

・　MYSQLログイン前だと、「mysql --version」で調べられる

・BDサーバー起動と確認は　「sudo service mysqld start && sudo service mysqld status」

・サーバーの接続終了するときは「exit」

・　「gem install bundler」で構成管理のbundlerをインストールをする

・「bundle install」でgemのインストールをする

・その他調べたり質問し解決したこと

・GPGキーのエラー解決
https://blog.katsubemakito.net/mysql/mysql-update-error-gpg

・MYSQLのrootパスワード変更

・database.ymlの１７行目のパスワードを変更して保存

・mysql -u root -pで変更したパスワードでログインできればOK

・Can't connect to local MySQL server through socket '/tmp/mysql.sock'はソケットのパスが合わないというエラー

・database.ymlの２２行目と３０行目のsoketを/tmp/mysql.sock から/var/lib/mysql/mysql.sockに変更して保存

・　ブラウザで表示しようとしたらwebpackerのエラーが出てくるので、yarnインストール、node.jpはインストール済みだったのでwebpackerインストール

https://1ed540e49ba846e0bfa8647aa4268049.vfs.cloud9.us-west-1.amazonaws.com/fruits
