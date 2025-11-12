<!-- title: Test
link: test
published_date: 2019-11-23 22:22
is_page: true
make_discoverable: false -->

# Markdown Syntax Test Page

This is a comprehensive test page for **basic Markdown syntax**. Use it to preview how your theme renders common elements.

---

## Headers

# Header 1 (H1)
## Header 2 (H2)
### Header 3 (H3)
#### Header 4 (H4)
##### Header 5 (H5)
###### Header 6 (H6)

---

## Text Styles

**Bold text**  
*Italic text*  
***Bold and italic***  
~~Strikethrough~~  
`Inline code`

> This is a **blockquote** with *emphasis* and `code`.

---

## Lists

### Unordered List
- Item 1
- Item 2
  - Subitem A
  - Subitem B
- Item 3

### Ordered List
1. First step
2. Second step
   1. Substep i
   2. Substep ii
3. Third step

### Task List
- [x] Completed task
- [ ] Incomplete task
- [ ] Another pending item

---

## Code Blocks

### Inline Code
Use `print("Hello, world!")` for quick snippets.

### Fenced Code Block (no language)
```
This is a plain code block
with multiple lines
    indented preserved
```

### Fenced Code Block (with language)
```python
def greet(name):
    return f"Hello, {name}!"

print(greet("Markdown"))
```

```javascript
console.log("Theme test");
document.body.style.background = "#f0f0f0";
```

```css
body {
    font-family: system-ui, sans-serif;
    line-height: 1.6;
    color: #333;
}
```

---

## Horizontal Rules

Above HR

---

Below HR

* * *

Above alt HR

___

Below alt HR

---

## Links and Images

[Visit xAI](https://x.ai)  
[Relative link](/path/to/page)

![Markdown Logo](https://markdown-here.com/img/icon256.png)

*(If the image fails to load, it tests broken image rendering.)*

---

## Tables

| Feature       | Syntax Example           | Rendered Result       |
|---------------|:------------------------:|-----------------------|
| **Bold**      | `**text**`               | **text**              |
| *Italic*      | `*text*`                 | *text*                |
| Code          | `` `code` ``             | `code`                |
| Link          | `[text](url)`            | [text](url)           |

*Right-aligned* | **:---:**
*Centered*     | **:---:**
*Left-aligned* | **---:**

---

## Blockquote Nesting

> Level 1 blockquote
>> Level 2 blockquote
>>> Level 3 blockquote with **bold** and `code`

---

## Inline HTML (if supported)

<span style="color: red;">Red text via HTML</span>  
<div style="background: #eee; padding: 10px; border-left: 4px solid #ccc;">
Custom styled div using inline HTML
</div>

---

## Miscellaneous

Superscript: x^2^  
Subscript: H~2~O  
Emoji: :rocket: :sparkles: :thumbsup:

---

*End of test page. Refresh or toggle dark/light mode to verify theme consistency.*