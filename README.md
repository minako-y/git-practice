段落
hoge

hoge

改行
hoge  
hoge

強調,強い強調
_hoge_ _hoge_
**hoge** **hoge**

インラインのコード
｀＄ hoge = 1 ｀

    ←半角スペース4つ　$hoge1 = 1 //1行目
    ←半角スペース4つ　$hoge2 = 2 //2行目
    ←半角スペース4つ　$hoge3 = 3 //3行目

- リスト 1
- リストリスト 1-2
- リスト 2

1. 順番つきリスト
2. 順番つきリスト
3. 順番つきリスト

# H1 見出し

## H2 見出し

#### H4 見出し

# H1 見出し（イコール行を挿入。）

## H2 見出し（ハイフン行を挿入。）

メールの引用の感じ。途中で改行しても、ダブルクォーテーション内は改行されない。入れ子も OK

> "引用本文引用本文引用本文引用本文
> 引用本文引用本文引用本文引用本文引用本文引用本文。"

> 引用本文引用本文引用本文引用本文
> 引用本文引用本文引用本文引用本文引用本文引用本文。
>
> > 入れ子入れ子
> > 入れ子入れ子
> > 引用本文引用本文引用本文引用本文
>
> - リスト
>   引用本文引用本文引用本文引用本文
>
> 1. 番号リスト
>    引用本文引用本文引用本文引用本文
>    $hgoe = 1 コードを書いてみたり
>    引用本文引用本文引用本文引用本文

リンク
記法は 3 種。リンクのタイトルは省略可能。

■ 自動リンク
アングルブラケット< >で URL を囲う。メアドでも可能

<http://example.com>
<example@example.com>
■ 通常のインライン記法

[リンクのテキスト](リンクのアドレス "リンクのタイトル")
■ 外部参照リンク（段落の外でリンクをまとめれる）

[リンクのテキスト][linkref]

[linkref]: リンクのアドレス "リンクのタイトル"

・実際の例：

I get 10 times more traffic from [Google][] than from
[Yahoo][] or [MSN][].

[google]: http://google.com/ "Google"
[yahoo]: http://search.yahoo.com/ "Yahoo Search"
[msn]: http://search.msn.com/ "MSN Search"

画像
先頭にビックリマーク

![Alt text](/path/to/img.jpg)
![Alt text](/path/to/img.jpg "Optional title")

・リンクと同じように参照表記も可能
![Alt text][id]

[id]: url/to/image "Optional title attribute"


