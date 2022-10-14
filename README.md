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

・その他調べて解決したこと

・GPGキーのエラー解決
https://blog.katsubemakito.net/mysql/mysql-update-error-gpg

・MYSQLのrootパスワード変更



https://1ed540e49ba846e0bfa8647aa4268049.vfs.cloud9.us-west-1.amazonaws.com/fruits
