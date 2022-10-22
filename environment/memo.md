# Section1

- バージョン指定でのインストール
```sh
$ gem install rails -v 6.0.4
$ gem install bundler -v 2.2.17
$ mkdir environment     # environmentディレクトリを作成
$ cd environment/       # 作成したenvironmentディレクトリに移動
$ cd ~/environment
$ rails _6.0.4_ new hello_app
$ cd hello_app/
Gemfileの編集
$ bundle _2.2.17_ install
$ rails webpacker:install
$ rails server
```

ディレクトリ	用途
```
app/	モデル、ビュー、コントローラ、ヘルパーなどを含む主要なアプリケーションコード
app/assets	アプリケーションで使うCSS（Cascading Style Sheet）、JavaScriptファイル、画像などのアセット
bin/	バイナリ実行可能ファイル
config/	アプリケーションの設定
db/	データベース関連のファイル
doc/	マニュアルなど、アプリケーションのドキュメント
lib/	ライブラリやモジュール置き場
log/	アプリケーションのログファイル
public/	エラーページなど、一般（Webブラウザなど）に直接公開するデータ
bin/rails	コード生成、コンソールの起動、ローカルのWebサーバーの立ち上げなどで使うRailsスクリプト
test/	アプリケーションのテスト
tmp/	一時ファイル
README.md	アプリケーションの簡単な説明
Gemfile	このアプリケーションに必要なGemの定義ファイル
Gemfile.lock	アプリケーションで使われるgemのバージョンを確認するためのリスト
config.ru	Rackミドルウェア用の設定ファイル
.gitignore	Gitに取り込みたくないファイルを指定するためのパターン
```