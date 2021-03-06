---
description: Text about this post
images:
- home.png
title: "『リーダブルコード』を読みました"
date: 2020-07-18T20:14:01+09:00
draft: false
tags: ["books"]
---
（最終更新：2020/7/22）

業務コーディングのバイブル扱いされている『リーダブルコード』をついに読みました．これまでコードは動きさえすればいいとさえ思っていた人なので大変参考になりました．

* Boswell, Dustin & Foucher, Trevor『リーダブルコード------より良いコードを書くためのシンプルで実践的なテクニック』角征典訳，オライリー・ジャパン，2012年．[amazonリンク](https://www.amazon.co.jp/%E3%83%AA%E3%83%BC%E3%83%80%E3%83%96%E3%83%AB%E3%82%B3%E3%83%BC%E3%83%89-%E2%80%95%E3%82%88%E3%82%8A%E8%89%AF%E3%81%84%E3%82%B3%E3%83%BC%E3%83%89%E3%82%92%E6%9B%B8%E3%81%8F%E3%81%9F%E3%82%81%E3%81%AE%E3%82%B7%E3%83%B3%E3%83%97%E3%83%AB%E3%81%A7%E5%AE%9F%E8%B7%B5%E7%9A%84%E3%81%AA%E3%83%86%E3%82%AF%E3%83%8B%E3%83%83%E3%82%AF-Theory-practice-Boswell/dp/4873115655/ref=sr_1_1?__mk_ja_JP=%E3%82%AB%E3%82%BF%E3%82%AB%E3%83%8A&dchild=1&keywords=%E3%83%AA%E3%83%BC%E3%83%80%E3%83%96%E3%83%AB%E3%82%B3%E3%83%BC%E3%83%89&qid=1595379061&sr=8-1)

## 時短しよう
コーディングにあたってのキーワードは，「大切なのはコードの短さではなく読み手の理解時間の短さ」．それを達成するために簡単に意識できることを，上書の「第I部　表面上の改善」から2つだけまとめておきましょう．1つ目は，変数名はコメントだということ，2つ目は，コメントは監督のコメンタリーだということです．

## 1. 変数名はコメント

変数名はコメントです．

私がコードを書くのは基本競プロにおいてで，そうすると`i`とか`j`とかの1文字変数ばかり使いがちですが，たとえ競プロであっても，バグ率を下げるために変数名を工夫するのは有用そうです．例えば，配列`clubs, members, users`のインデックスを，配列名の頭文字を使って，`ci, mi, ui`とするなど．

あとは，単位を変数名に入れる．閉区間の範囲を指定するときは`first, last`を使うなど．（右半開区間は`begin, end`．）

## 2. コメントは監督のコメンタリー

コメントにはコードからすぐに抽出できること，調べればわかることを書くべきでは**ありません**．むしろ書かれるべきなのは，それを書いたあなたの意図，言わば監督のあなたがこのコードのドキュメンタリーで話す内容のことです．書いた時のモチベを書きましょう．工夫したことを書きましょう．他の書き方がありうるなら，それではなくこれを選んだポイントを書きましょう．間違いがあると分かっている箇所には，欠陥を`TODO:`, `FIXME:`，`XXX: // 重大な欠陥`などとして示しておきましょう．


<!-- admax -->
<script src="https://adm.shinobi.jp/s/8ae62ddfcb928c284dec1bddeaf8bca1"></script>
<!-- admax -->