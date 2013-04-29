# sematj サイト 試作版

##仕組み
Twitter Bootstrap をベースにしています。

##更新の方法
* Github はWeb経由で直接ファイルを編集する機能がありますので、そこから編集していただくことが可能です。
* かなりシンプルなHTMLですので、編集は容易かとおもいます。
   * こちらに全てのファイルがあります。 > https://github.com/kawaguti/semat-j/tree/master/site/ja
   * 各ファイルを開いて [edit]ボタン押下で内容を編集できます。(編集権限をもたれている方なら)

* 本番サイトへの反映は、
   * 本番サイト側で Github から git pull します。
   * 定期的に実行することも容易と思います。

* CMSと比べた長所短所
   * デメリット
　　   * 書き込んだらすぐ反映するような仕組みがない
　　   * HTMLを直接編集することになる

   * メリット
       * 見た目がよい
       * 表示のスピードが圧倒的に速い (Webサーバ以外のプログラムが動かないので)
       * 静的なHTMLであるため、検索サイト対策上(SEO)は強い ... はず
       * 履歴が github で管理される。システム＆データバックアップを兼ねる
