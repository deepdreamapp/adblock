##Superblock for iOS9
2chまとめサイトなどの広告をすべて消せます。  
[Superblock](https://itunes.apple.com/us/app/superblock-guang-gaoburokku/id1041786553?l=ja&ls=1&mt=8)  

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
2.[◆iV/mj2eF/.移植版](http://sugokunemui.github.io/superblock/domain.html)  
  
※追加し過ぎるとSafariの動作が重くなるかもしれません
  
##カスタムフィルターを使う  
現在インポート機能などが無いため、カスタムフィルターを使う場合は注意が必要です。  
すでに入力されているカスタムフィルターを全て消して空の状態にしてから、使いたいフィルターリストをペーストしてください。  
すでに入っているものの下に追記していくとエラーが出る可能性があります  
  
1.[アダルト広告＆ポップアップブロック](http://sugokunemui.github.io/superblock/adult.html)  
  
今後複数のフィルターをインポートし統合する機能を追加します。  
  
##カスタムフィルターを作る
この機能は上級者向けです  
WebkitのContent Blockersの仕様に従って記述します  
[Introduction to WebKit Content Blockers](https://www.webkit.org/blog/3476/content-blockers-first-look/)