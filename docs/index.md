<<<<<<< HEAD
 Markdown Playground Demo
=======
# Markdown Playground Demo
>>>>>>> dfde31422c18c90a23078e7a570e32c9f83d66b4

This preview supports *italic*, **bold**, ***bold+italic***, ~~strikethrough~~, and inline code like `npm run dev`.

## Headers

### H3 Section
#### H4 Section
<<<<<<< HEAD
##### H5 Section#
=======
##### H5 Section
>>>>>>> dfde31422c18c90a23078e7a570e32c9f83d66b4

## Lists

- Unordered list item
- Another item with **strong** text

1. Ordered step one
2. Ordered step two

## Image

![Sample chart](/static/home/users-graph.png)

## Code blocks

```python
def greet(name: str) -> str:
    return f"Hello, {name}"
```

```javascript
const users = [{ name: "Alice" }, { name: "Bob" }];
console.log(users.map((u) => u.name).join(", "));
```

```bash
curl -s https://www.devtoolsdaily.com/sitemap.xml | head -n 5
```

## Table

| Feature | Status | Notes |
| --- | :---: | --- |
| GFM Tables | Yes | Uses `remark-gfm` |
| Syntax Highlighting | Yes | Multiple languages |
| Inline Code | Yes | Styled with monospace |
