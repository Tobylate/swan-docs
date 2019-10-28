---
title: CanvasContext.font
header: develop
nav: api
sidebar: canvas_CanvasContext_font
---

 

**解释**：设置当前字体样式的属性。

**方法参数**：String value

**`value` 参数说明**：符合 CSS font 示例的 DOMString 字符串，至少需要提供字体大小和字体族名，默认值为 10px sans-serif 。 

**value 支持的属性有**：

| 属性 | 说明 |
|---- | ---- |
| style | 字体样式，仅支持 italic, oblique, normal。 |
| weight | 字体粗细，仅支持 normal, bold。 |
| size | 字体大小 |
| family | 字体族名，注意确认各平台所支持的字体 。|

**示例**：

```js
canvasContext.font = value;
```
