---
title: "『リーダブルコード』を読み始めました"
date: 2020-07-18T20:14:01+09:00
draft: false
tags: ["books"]
---

## 変数名はコメント
業務でコードを書く際のバイブル扱いされている『リーダブルコード』をついに読み始めました．これまでコードは動きさえすればいいとさえ思っていた人なので大変参考になりそうです．

たとえ競プロでコードを書くのであっても，バグ率を下げるために有用そうです．例えば，配列`clubs, members, users`のインデックスを，たんに`i,j,k`ではなく，配列名の頭文字を使って，`ci, mi, ui`とするなど．

あとは，単位を変数名に入れる．閉区間の範囲を指定するときは`first, last`を使うなど．（右半開区間は`begin, end`．）　**変数名とは簡単なコメント**だという意識を今後持ちたいです．

<script data-ad-client="ca-pub-2296667233758798" async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>