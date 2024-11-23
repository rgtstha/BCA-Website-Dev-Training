# Day 3


## HTML Text Formatting

- HTML text formatting elements were designed to display special types of text:
  - ```<b>``` - Bold text
  - ```<strong>``` - Important text
  - ```<i>``` - Italic text
  - ```<em>``` - Emphasized text
  - ```<del>``` - Deleted text
  - ```<sub>``` - Subscript text
  - ```<sup>``` - Superscript text
  - ```<pre>``` - Preformatted text
  - ```<u>``` - Underlined text
  - ```<br> ``` - Line break

You can find the complete code for this day [here](./index.html).

### Important Points:
- ```<br>``` tag is used to break the line. This tag does not have a closing tag. So, we call it a self-closing tag. A self-closing tag is a tag that doesn't have a closing tag.


## Horizontal Lines
- The ```<hr>``` tag defines a thematic break in an HTML page.
```html
<p>This is a paragraph.</p>
<hr>
<p>This is another paragraph.</p>
```

## HTML Images
```html

<!-- local image -->
<img src="image.jpg" alt="Image Description">

<!-- url image -->
<img src="https://picsum.photos/seed/picsum/200/300" alt="A Random Image">
```

- The ```<img>``` tag is used to embed an image in an HTML page.
- The ```src``` attribute specifies the URL (web address) of the image.
- The ```alt``` attribute provides an alternate text for an image, if the image cannot be displayed.
- The ```alt``` attribute is important for accessibility. It provides text for screen readers to read.
- The ```alt``` attribute should describe the content of the image.
- The ```src``` attribute is required, and the ```alt``` attribute is optional.
- The ```<img>``` tag is an empty tag, which means it does not have a closing tag.
- The ```<src>``` tag can take a `url` or a local path to the image.
