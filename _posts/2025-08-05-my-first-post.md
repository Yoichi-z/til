---
title: "はじめてのTIL投稿"
date: 2025-08-05 21:00:00 +0900
categories: [Python, 入門]
tags: [リスト内包表記, 初学者]
---

これはJekyll minima テーマでの初めてのTIL投稿サンプルです。

## 例：リスト内包表記

Pythonで0から4までの数を2乗するリストを作成するには、以下のように書きます。

```python
squares = [x**2 for x in range(5)]
print(squares)
```

上記コードの実行結果は次の通りです。

```
[0, 1, 4, 9, 16]
```
