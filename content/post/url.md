---
title: "URLには何が書いてあるの？"
date: 2020-07-07T15:24:24+09:00
draft: false
tags: ['web']

---
## URL

頻繁に目にするURLですが，これにはどんな情報が書き込まれているのでしょうか．

結論から言うと，URLとは，**ブラウザからサーバーへのアクセス内容**を示すものです．具体的には，1. どういうやり取りの手順で 2. どのサーバーに 3. 何のコンテンツを取りに行くかが書かれています．

## 例

このページのURLを例にとって解読してみましょう．

```
https://fukucchi.github.io/blog/post/url/
```


3つの部分に分けて説明しましょう．まず冒頭には `https://`と書かれています．これは，WebブラウザとWebサーバの間のやり取りをHTTPSという**ルール**で行うことを意味しています．HTTPSとは，HyperText Transfer Protocol Secureの略で，HTTPのセキュリティを高めたルールのことです．

次に，`fukucchi.github.io/`で，`fukucchi.github.io/`という名前の**Webサーバー**にアクセスしていることがわかります．

最後に`blog/post/url/`で，このWebサーバーに対して`blog/post/url/`という**コンテンツ**を取りに行くということが書かれています．

<script data-ad-client="ca-pub-2296667233758798" async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>

<!-- admax -->
<script src="https://adm.shinobi.jp/s/8ae62ddfcb928c284dec1bddeaf8bca1"></script>
<!-- admax -->