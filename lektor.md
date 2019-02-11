Lektor
--------
* [Lektor](https://www.getlektor.com/)
* [Lektor - GitHub](https://github.com/lektor/lektor/)

### Memo

* [Python製のWebサイト生成ツールLektorで、github pagesに自分のサイトを公開する](https://qiita.com/ryokomy/items/044b45e211d200159664)
* [Lektorを使ってみる](http://www.takunoko.com/blog/lektor%E3%82%92%E4%BD%BF%E3%81%A3%E3%81%A6%E3%81%BF%E3%82%8B/)

Lektorのコマンド
-----

プロジェクト作成

    $ lektor quickstart

テストサーバ起動

    $ lektor server

静的ファイルを出力し、

    $ lektor build

    ビルドの出力先を調べる
    $ lektor project-info --output-path

    出力先を指定
    $ lektor build --output-path <my-folder>
    例) $ lektor build --output-path ./temp

登録済みのgithubサイトにpushしデプロイできるようになっている。

    $ lektor deploy
