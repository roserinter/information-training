# information-training

## githubとは？

**プログラムのバージョン管理アプリケーション**

プログラムを逐次覚えておいて、それをいつでも見直すことができる

### 利点
* バージョン管理が簡単にできる

    プログラムをいつでも好きなタイミングで好きな時点に復元できる

* 共同編集が可能になる

### 使い方
1. **ソース管理**タブを選択する。
2. **メッセージ**に日付や変更内容を記載して、**コミット(commit)** を押す
3. **変更の同期(push)** を押すと完了できる。

commitは、解決した問題を記憶しておく

pushは、変更履歴をgithub上に保存すること。

pullやmargeなどもあるがそこまではできない。

## Markupとは？

HTMLなどに使われている記法で、文章中に特定の文字や記号などを使って、様々な見え方の調整を行うことができる言語


### HTMLの表示方法（導入編）
1. **拡張機能**タブを選択する。
2. 検索欄に[live server]と入力する。
3. インストールを押す。

### HTMLの表示方法
1. index.htmlを画面に表示する
2. 右下のGo Liveをクリックする

### markdown

マークアップ言語を簡単に記述しようとする記法

マークダウン記法は「#」「*」など使って簡単にしている。

ファイル拡張子は「.md」となる

### HTMLについて

<タグ>で囲うことで文章に意味をつけることができる言語

ウェブぺージの表示に用いられる

~~~html
<h1>タイトル１</h1>
<p>文章</p>
~~~
> mdにおいて、「~~~ ~~~」で囲われた部分をコードブロックといい、プログラムなどをハイライトして記述することができる

> また、このように「>」で注釈などの文章を記述することもできる
>> その中にまた「>」を仕込むこともできる

## cssについて

カスケーティング（連続的な）　スタイル　シートの略

~~~css
h1{
    color: red;
}

p{
    color: green;
}
