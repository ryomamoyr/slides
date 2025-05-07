---
marp: true
theme: jrw-template
size: 16:9
paginate: true
header: |
  <span class="conf-label">CONFIDENTIAL&nbsp;&nbsp;取扱注意</span>
  <div class="jr-logo"></div>
---

<!-- _class: title -->
<!-- paginate: false -->

# Main Title

## 2025-mm-dd ｜ ご挨拶・ご紹介資料

---

<!-- _class: agenda -->

# Table of Contents

1. Agenda
2. Outline
3. Introduction
4. Overview

---

<!-- paginate: true -->
<!-- _class: divider -->

# 1

## Sub Title

---

# Images Center Format

一番良く使うフォーマット

![c](./images/sample.png)
c:は center の略です. 簡単に書くために jrw_theme.css で定義しています

- 図 1: 注釈\*

画像の下にドキュメントを書けます

---

# Images Align Format

![c h:250](./images/sample.png) ![c h:250](./images/sample.png) ![c h:250](./images/sample.png)

横に並べることもできます
収まるようにサイズを変更します。h は height の略です

---

# Images Align Format

![c h:200](./images/sample.png)
![c h:200](./images/sample.png)

縦に並べることもできます

---

# Images Split Format

<div class="split-layout">
<div class="left-content">

## 左側の見出し

![c](./images/sample.png)

- リストも
- 書くことが
- できます

</div>
<div class="right-content">

## 右側の見出し

![c](./images/sample.png)

右側に表示したい文章はここに書きます。
こちらも複数行書けます。

1. 番号付きリスト
2. なども
3. 使えます

</div>
</div>

---

# Images Split Format

<div class="split-layout">
<div class="left-content">

## 左側の見出し

![c h:200](./images/sample.png)![c h:200](./images/sample.png)

画像を二枚画面半分左側に配置したいこともあります

</div>
<div class="right-content">

## 右側の見出し

### 右側には文章を書きます

右側には文章だけを書きたいこともあります

</div>
</div>

---

<!-- _class: divider -->

# 2

## Other format

---

# Code Block

## Shell

```bash
echo "Hello World"
```

<!-- Pythonのコードもかける -->

## Python

```python
while True:
    if slide is None:
        break
```

---

# Table Block

## テーブル

<!-- 対象のページのテーブルのみ文字サイズを変えたい時 -->

  <style scoped>
    table th{ font-size: 24px; },
    table td{ font-size: 16px; }
  </style>

| 1   | 2   |
| --- | --- |
|     |     |
|     |     |

| 1   | 2   | 3   |
| --- | --- | --- |
|     |     |     |
|     |     |     |
|     |     |     |

| 1   | 2   | 3   | 4   |
| --- | --- | --- | --- |
|     |     |     |     |
|     |     |     |     |
|     |     |     |     |

---

# 数式表現

## インライン数式

文章の中に $E=mc^2$ や $\sum_{i=1}^{n} i$ のような数式を入れることができます。

## ブロック数式

独立した数式ブロックも作成できます：

$$
\begin{align}
\frac{d}{dx}e^x &= e^x\\
\int_0^1 x^2 dx &= \frac{1}{3}\\
\lim_{n\to\infty}\frac{1}{n} &= 0
\end{align}
$$

---

# 各フォントの変更

<font color="green">
    色つきの文字
</font>

<span style="font-size: 24px">大きい文字</span>
<span style="font-size: 12px">小さい文字</span>
<span style="text-decoration: underline">下線</span>
<span style="background-color: yellow">黄色の背景</span>

<!-- 空白行 -->

<div align="left">この部分は左端から</div>
<div align="center">この部分は中央から</div>
<div align="right">この部分は右端から</div>

**太字**

_斜体_

**_太字かつ斜体_**

~~取り消し線~~

`インラインコード`

[リンク](https://example.com)

キーボード
<kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Del</kbd>
<kbd>Enter</kbd>

emoji
:smile: :chart_with_upwards_trend: :warning: :information_source:

---

# 注釈

## 引用スタイルの注釈

> 重要な注意事項や引用文をこのように目立たせることができます。
> 複数行にまたがる注釈も使えます。

## 定義リスト

<dl>
  <dt>用語</dt>
  <dd>用語の説明</dd>

  <dt>別の用語</dt>
  <dd>別の用語の説明</dd>
</dl>

通常の文章に脚注を付けることができます<sup>1</sup>。

<div class="footnote">
<span style="font-size: 14px">
<sup>1</sup>脚注の詳細説明はここに記載します。
</span>
</div>
