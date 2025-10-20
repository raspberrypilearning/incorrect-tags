仔细检查 HTML 标签、属性和类的拼写。

不正确的标签可能意味着标签文本会显示在网页上，而不是控制布局。

此示例错误地使用了“image”而不是“img”！ `<img>` 是正确的 HTML 标签。

--- code ---
---
language: HTML
filename: index.html
line_numbers: false
---

    <image class="bordered-box" src="happy.png" alt="An outline of an anime style girl with a happy facial expression."/>

--- /code ---

标签中有空格也是不正确的，因此下面的示例是不正确的。

--- code ---
---
language: HTML
filename: index.html
line_numbers: false
---

< h1>Lorem ipsum</h1>

--- /code ---
