---
marp: true
theme: uncover
header: "Lumos Lightning Talks !!!"
paginate: true
footer: "by tomoyahiroe"
---

# TypeScript の@デコレータを触ってみた

tomoyahiroe

---

## 自己紹介

![bg brightness:0.2](./images/my_picture.JPG)

<!--
 _color: #FFF
-->

---

Name：Tomoya Hiroe

Keyword：bass, soft-tennis, Lumos

Language：JavaScript, TypeScirpt

---

![bg brightness:0.3](./images/kusa.jpg)

<!--
_color: #FFF
-->

## @decorator とはなんぞや

---

### nestJS のルーティング処理

![](./images/nest_controller.png)

---

### nestJS のエンティティファイル

![height:500px](./images/nest_entity.png)

---

## どうやら、<br> experimental support らしい？

---

![bg brightness:0.3](./images/kusa.jpg)

<!--
_color: #FFF
-->

## デコレータ作ってみたい

---

## ググってみると...

---

### 色々あるらしい

- クラスデコレータ
- メソッドデコレータ
- アクセサデコレータ
- プロパティデコレータ
- パラメータデコレータ

---

![bg brightness:0.3](./images/kusa.jpg)

<!--
_color: #FFF
-->

## クラスデコレータ触ってみた

---

### デコレータファクトリがこちら

![width:945px](./images/decorator_factory.png)

---

### デコレートするクラスがこちら

![height:500px](./images/decorated_class.png)

---

### 以下のコードで出力すると

![](./images/error_consolelog.png)

---

### デコレータファクトリで定義した<br>プロパティが認識されてない

![](./images/error_output.png)

---

### そこで、とりま@ts-ignore

![](./images/consolelog.png)

---

### 出力結果

![](./images/output.png)

---

![bg brightness:0.3](./images/kusa.jpg)

<!--
_color: #FFF
-->

## 感想

---

- まだ自分で使うことはない
- 初めてリリースされてない言語の機能を触って面白かった
- LT いいわ。好きだわ。みんなの発表聞きたいわ

---

## 以上！

---

## 参考文献

- [TypeScript の Decorator について – 公式ドキュメント日本語訳](https://mae.chab.in/archives/59845)
- [TypeScript によるデコレータの基礎と実践](https://qiita.com/taqm/items/4bfd26dfa1f9610128bc)
- [もう怖くない TypeScript のデコレータ機能](https://zenn.dev/miruoon_892/articles/365675fa5343ed)
- [TypeScript をブラウザで実行できる Playground](https://www.typescriptlang.org/)
- [TypeScript の公式ドキュメント](https://www.typescriptlang.org/docs/handbook/decorators.html)
- [Property does not exist のエラー](https://github.com/machty/ember-concurrency-decorators/issues/30)
- [今こそ伝えたい@ts-ignore の魅力](https://scrapbox.io/terrierscript/%E4%BB%8A%E3%81%93%E3%81%9D%E4%BC%9D%E3%81%88%E3%81%9F%E3%81%84%EF%BC%81@ts-ignore%E3%81%AE%E9%AD%85%E5%8A%9B)
