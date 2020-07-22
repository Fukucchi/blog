---
title: "ステータスコード"
date: 2020-07-06T21:33:47+09:00
draft: false
tags: ['web']
#categories: ['haha']
---

アウトプットのためにブログを始めます．まずは先日の面接で答えられなかったことで思い出深いステータスコードから．

ステータスコードというのは，HTTPリクエストに対する対してWebサーバーが返す処理結果のことです．100番台から500番台の5種類に大きく分けられます．

まずは，100-300番台について．
- 100番台はリクエストが継続中であるということを
- 200番台はリクエストが正常に受理されたことを
- 300番台はコンテンツURLが移動したとかで，追加の処理が必要なこと
を示します．

### クライアントエラーとサーバーエラー
そして重要なのが400,500番台で，これらはエラーを示します．
- 400番がクライアントエラー，つまりブラウザ側のエラー
  - 400: Bad Request
  - 404: Not Found
- 500番台はWebサーバーのエラーです．
  - 500: Internal Server Error
  - 503: Service Unavailable

400,500については必須ですね．


<script data-ad-client="ca-pub-2296667233758798" async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>

<!-- admax -->
<script src="https://adm.shinobi.jp/s/8ae62ddfcb928c284dec1bddeaf8bca1"></script>
<!-- admax -->