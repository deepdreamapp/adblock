##Superblock for iOS9
2chまとめサイトなどの広告をすべて消せます。

##使い方
**インストールするだけでは効きません。**設定アプリから  
「Safari」  
↓  
「コンテンツブロッカー」  
↓  
「Superblock」をオン  

にしてください

##ドメイン指定
読み込みをブロックしたいURLのドメインを指定します  
サブドメインは全てマッチします  
例）  
zzz.aaa.jpやxxx.aaa.jpにマッチさせたい場合、aaa.jpだけを指定します  
  
入力する際はドメインごとに改行してください  
  
その他有志によるドメインリストです  
1.[Weblock List for Japanese [iOS] [日本語] [domains]](http://cosmonote.blogspot.jp/2014/02/weblock-list-for-japanese-ios-domains.html?m=1)  
2.[◆iV/mj2eF/.移植版](https://raw.githubusercontent.com/sugokunemui/adblock/master/domain.txt)  
  
※追加し過ぎるとSafariの動作が重くなるかもしれません

##カスタムフィルター
この機能は上級者向けです  
WebkitのContent Blockersの仕様に従って記述します  
[Introduction to WebKit Content Blockers](https://www.webkit.org/blog/3476/content-blockers-first-look/)

###とりあえず使いたい人向け
[アダルト広告ブロック（軽量版）](https://www.webkit.org/blog/3476/content-blockers-first-look/)
[アダルト広告ブロック](https://www.webkit.org/blog/3476/content-blockers-first-look/)
  
現在いずれか一つのみ適用可能です。すべて詰め込むとエラーが出る可能性があります。  
使用する場合は、カスタムフィルター欄の内容を全て削除してからペーストしてください。  
下にそのまま追加していくとJSONのパースエラーが起きます。    