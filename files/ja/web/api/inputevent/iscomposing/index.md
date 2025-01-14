---
title: InputEvent.isComposing
slug: Web/API/InputEvent/isComposing
l10n:
  sourceCommit: 277e5969c63b97cfb55ab4a0e612e8040810f49b
---

{{APIRef("UI Events")}}

**`InputEvent.isComposing`** は読み取り専用プロパティで、このイベントが {{domxref("Element/compositionstart_event", "compositionstart")}} の後、かつ {{domxref("Element/compositionend_event", "compositionend")}} の前に発生したかどうかを示す論理値を返します。

## 値

論理値です。

## 例

```js
const inputEvent = new InputEvent("syntheticInput", false);
console.log(inputEvent.isComposing); // return false
```

## 仕様書

{{Specifications}}

## ブラウザーの互換性

{{Compat}}

## 関連情報

- {{domxref("Element/compositionstart_event", "compositionstart")}} および {{domxref("Element/compositionend_event", "compositionend")}}
- {{domxref("InputEvent")}}
