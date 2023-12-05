# 『オブジェクト設計スタイルガイド』のススメ

<a href="https://www.amazon.co.jp/%E3%82%AA%E3%83%96%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E8%A8%AD%E8%A8%88%E3%82%B9%E3%82%BF%E3%82%A4%E3%83%AB%E3%82%AC%E3%82%A4%E3%83%89-Matthias-Noback/dp/4814400330?&linkCode=li2&tag=smeghead-22&linkId=5051a06b19a3f55d2a2d413b5bd6fb09&language=ja_JP&ref_=as_li_ss_il" target="_blank"><img border="0" src="//ws-fe.amazon-adsystem.com/widgets/q?_encoding=UTF8&ASIN=4814400330&Format=_SL160_&ID=AsinImage&MarketPlace=JP&ServiceVersion=20070822&WS=1&tag=smeghead-22&language=ja_JP" ></a><img src="https://ir-jp.amazon-adsystem.com/e/ir?t=smeghead-22&language=ja_JP&l=li2&o=9&a=4814400330" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />

今年読んだ本『オブジェクト設計スタイルガイド』は、実用的で有効な設計スタイルが網羅的に紹介されていてとても良い本です。自分の最近の業務のプログラミングでも、紹介されている設計スタイルを採用しています。

簡単に実践できる設計スタイルを紹介してみたいと思います。

この本に出てくるサンプルコードは、PHPのようですがPHPではありません。以下のような幾つかの点でPHPではない架空の言語で書かれています。

 * 変数の`$`が無い
 * メソッド呼び出しの`->`が`.`になっている

これは、PHPコードを見難いと感じる人に配慮しているのかもしれません。しかし普通に`json_encode`のようなPHP特有の関数が出てきたりするので、完全にPHPを前提にして構成されていると思います。(個人的にはPHPで書いてくれた方が嬉しかったです)


## まとめ

簡単な指針をいくつか紹介してみました。他にもオブジェクトを使うさまざまな場面での指針が沢山示されています。
もちろん、全ての指針に準拠しなければならないという強制的なものではありません。自分の考え方と合わない指針もあるかもしれません。それぞれの指針の意図するあるべき姿を考えてみることで、オブジェクト設計で考慮すべきポイントを学ぶことができる、多くのPHPerにお勧めの本です。



## Development

### Open shell

```bash
docker compose build
docker compose run --rm php_cli bash
```

### install dependencies

```bash
composer install
```

### execute tests

```bash
composer test
```

