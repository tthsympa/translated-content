---
title: HTMLTableElement.createTBody()
slug: Web/API/HTMLTableElement/createTBody
---

{{APIRef("HTML DOM")}}

**`createTBody()`** は {{domxref("HTMLTableElement")}} オブジェクトのメソッドで、この {{HtmlElement("table")}} に関連付けられた新しい {{HTMLElement("tbody")}} 要素を返します。

> **Note:** {{domxref("HTMLTableElement.createTHead()")}} や {{domxref("HTMLTableElement.createTFoot()")}} とは異なり、 `createTBody()` は既に 1 つ以上の本体があった場合でも、必ず新しい `<tbody>` 要素を生成します。その場合、新しいものは既存のものの後に挿入されます。

## 構文

```js
table.createTBody();
```

### 返値

{{domxref("HTMLTableSectionElement")}}

## 例

```js
let mybody = mytable.createTBody();
// mybody == mytable.tBodies.item(mytable.tBodies.length - 1) は真になります
```

## 仕様書

{{Specifications}}

## ブラウザーの互換性

{{Compat}}
