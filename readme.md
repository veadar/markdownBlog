#markdownBlog

##これは何？

一時的なMarkdownファイルを作り、指定したテキストエディタで編集した後、その内容を各種ブログサービスに投稿するアプリです。

使い慣れたアプリでブログを書けます。

##対応 OS

macOS 10.12(他のバージョンでも動くかもだけれど未検証) 

##スクリーンショット

![スクリーンショット](./screenshot.png)

##対応サービス

- はてなブログ(タグ未対応)
- はてなダイアリー
- Livedoor Blog
- FC2ブログ
- WordPress
- ローカルフォルダ

## 準備
1. 「Safari」>「環境設定」>「詳細」から「メニューバーに"開発"メニューを表示」にチェックを入れておく
2. 開発メニューの「AppleEventからのJavaScriptを有効」にチェック
3. 「システム環境設定」 > 「セキュリティとプライバシー」>「プライバシー」>「アクセシビリティ」にこのアプリを登録しておく(ウィンドウリサイズ機能のため)

## テンプレート中に使える変数一覧

<dl>
<dt>__year__</dt>
<dd>4桁の西暦</dd>
<dt>__month__</dt>
<dd>1から2桁の月</dd>
<dt>__day__</dt>
<dd>1から2桁の日</dd>
<dt>__hour__</dt>
<dd>1から2桁の時</dd>
<dt>__minutes__</dt>
<dd>1から2桁の分</dd>
<dt>__seconds__</dt>
<dd>1から2桁の秒</dd>
<dt>__month2__</dt>
<dd>0埋め2桁の月</dd>
<dt>__day2__</dt>
<dd>0埋め2桁の日</dd>
<dt>__hour2__</dt>
<dd>0埋め2桁の時</dd>
<dt>__minutes__</dt>
<dd>0埋め2桁の分</dd>
<dt>__seconds2__</dt>
<dd>0埋め2桁の秒</dd>
<dt>__account__</dt>
<dd>ログインしているユーザ名</dd>
<dt>__fullname__</dt>
<dd>設定しているユーザ名</dd>
<dt>__clipboard__</dt>
<dd>現在のクリップボードのテキスト</dd>
</dl>

##ダウンロード

Downloadをクリック → [Download](https://github.com/veadar/markdownBlog/releases)


##参考にさせていただいたコード

- [MenuBarAppleScript](http://memogakisouko.appspot.com/MenuBarAppleScript.html)
- [MMMarkdown](https://github.com/mdiep/MMMarkdown)
- [HOW TO FILL OUT FORMS ON WEBSITES WITH APPLESCRIPT](http://www.cubemg.com/how-to-fill-out-forms-on-websites-with-applescript/)
- [HOW TO CLICK A BUTTON ON A WEB PAGE WITH APPLESCRIPT](http://www.cubemg.com/how-to-click-a-button-on-a-web-page-with-applescript/)
- [aami flat: New Year Resolutions!](https://www.iconfinder.com/icons/897241/article_blog_blogging_compose_resolutions_sign_write_icon#size=128)