# Day 4


## HTML Comments

```html
<!-- This is a comment -->
```

- Comments are not displayed in the browser.
- You can use comments to explain your code, which can help you when you edit the source code at a later date.
- Comments can also be used to prevent execution, when testing alternative code.
- Comments are written with `<!--` at the beginning, and `-->` at the end.
- You can also use comments to hide parts of the code you do not want to run. 
- This is useful, if you have a lot of code, and you want to test parts of the code.



## HTML Anchor Tag

```html
<a href="https://www.google.com">Visit Google</a>
```

- The `<a>` tag defines a hyperlink, which is used to link from one page to another.
- The `href` attribute specifies the URL of the page the link goes to.
- The `href` attribute is required, and the `href` attribute value is the URL of the page you want to link to.
- The content inside the `<a>` element is the visible part of the link.
- The `href` attribute can also take an email address or a `url` or a local path to the page.


## Target Attribute

```html
<a href="https://www.google.com" target="_blank">Visit Google</a>
```

1. `_blank`
2. `_self`
3. `_parent`
4. `_top`
5. `framename`
6. `windowname`

- The `target` attribute specifies where to open the linked document.
- The `target` attribute can have one of the following values:
  - `_blank` - Opens the linked document in a new window or tab.
  - `_self` - Opens the linked document in the same frame as it was clicked (this is the default).
  - `_parent` - Opens the linked document in the parent frame.
  - `_top` - Opens the linked document in the full body of the window.
  - `framename` - Opens the linked document in a named frame.
  - `windowname` - Opens the linked document in a new window.