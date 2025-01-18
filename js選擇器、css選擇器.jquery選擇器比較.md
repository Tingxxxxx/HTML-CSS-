# CSS 選擇器、JavaScript 選擇器 和 jQuery 選擇器

## 1. CSS 選擇器
CSS 選擇器用於選擇頁面中的元素並設置樣式。

| 選擇器           | 語法           | 說明                                   | 示例                     |
|-------------------|----------------|----------------------------------------|--------------------------|
| **標籤選擇器**    | `tagname`      | 選擇所有特定標籤                      | `div { color: red; }`   |
| **類選擇器**      | `.classname`   | 選擇特定類名的元素                    | `.box { color: blue; }` |
| **ID 選擇器**     | `#id`          | 選擇特定 ID 的元素                    | `#header { font-size: 20px; }` |
| **層級選擇器**    | `parent child` | 根據層級關係選擇元素                  | `div p { margin: 0; }`  |
| **通配選擇器**    | `*`            | 選擇所有元素                          | `* { margin: 0; }`      |

---

## 2. JavaScript 選擇器
JavaScript 提供內建方法選擇並操作 DOM 元素。

| 選擇器           | 方法                       | 說明                                   | 示例                                      |
|-------------------|----------------------------|----------------------------------------|-------------------------------------------|
| **標籤選擇器**    | `document.getElementsByTagName` | 選擇所有特定標籤                     | `document.getElementsByTagName('div')`   |
| **類選擇器**      | `document.getElementsByClassName` | 選擇所有擁有特定類名的元素          | `document.getElementsByClassName('box')` |
| **ID 選擇器**     | `document.getElementById` | 選擇特定 ID 的元素                    | `document.getElementById('header')`      |
| **CSS 選擇器**    | `document.querySelector`  | 選擇符合 CSS 選擇器的第一個元素       | `document.querySelector('.box')`         |
| **所有符合元素**  | `document.querySelectorAll` | 選擇所有符合 CSS 選擇器的元素         | `document.querySelectorAll('div.box')`   |

---

## 3. jQuery 選擇器
jQuery 基於 CSS 選擇器的語法，簡化了元素選擇和操作。

| 選擇器           | 語法            | 說明                                   | 示例                  |
|-------------------|-----------------|----------------------------------------|-----------------------|
| **標籤選擇器**    | `$("tagname")`  | 選擇所有特定標籤                      | `$("div")`           |
| **類選擇器**      | `$(".classname")` | 選擇所有特定類名的元素               | `$(".box")`          |
| **ID 選擇器**     | `$("#id")`      | 選擇特定 ID 的元素                    | `$("#header")`       |
| **層級選擇器**    | `$("parent child")` | 根據層級關係選擇元素                | `$("div > p")`       |
| **複合選擇器**    | `$("selector1, selector2")` | 同時選擇多種元素                  | `$("div, p")`        |

---

## 用法對比範例
以下範例展示選擇類名為 `box` 的元素的不同方式：

### **CSS**
```css
.box {
    background-color: yellow;
}
