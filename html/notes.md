# HTML Notes

- HTML is a markup language.
- It is made up of tags.
- Tags are enclosed in angle brackets. (<>)

## HTML has a general boilerplate structure

```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>

</body>

</html>
```

- Tags can be of 2 types:
    - Independent tags (tags that do not need a closing tag) - ```<tagname>```
    - Dependent tags (tags that need a closing tag) -  ```<tagname></tagname>```

- Main HTML Tags

| Tag | Description |
| --- | ----------- |
| ```<html></html>``` | The root element of an HTML document. |  
| ```<head></head>``` | Contains metadata/information about the document. |
| ```<title></title>``` | Defines the title of the document. |
| ```<body></body>``` | Defines the document's body. |

- HTML Attributes
    - Attributes provide additional information about HTML elements.
    - Attributes are always specified in the start tag.
    - Attributes usually come in name/value pairs like: name="value"
    - Attributes can be used to add styles to HTML elements.

- HTML Elements

### HTML Headings

- Type: Dependent Tag & Block Element

| Tag | Description |
| --- | ----------- |
| ```<h1></h1>``` | Defines the most important heading. |
| ```<h2></h2>``` | Defines the second most important heading. |
| ```<h3></h3>``` | Defines the third most important heading. |
| ```<h4></h4>``` | Defines the fourth most important heading. |
| ```<h5></h5>``` | Defines the fifth most important heading. |
| ```<h6></h6>``` | Defines the least important heading. |

### HTML Paragraphs

- Type: Dependent Tag & Block Element

| Tag | Description |
| --- | ----------- |
| ```<p></p>``` | Defines a paragraph. |

### HTML Span

- Type: Dependent Tag & Inline Element

| Tag | Description |
| --- | ----------- |
| ```<span></span>``` | Defines a section in a document. |

### HTML Links

- Type: Dependent Tag & Inline Element
  
| Tag | Description |
| --- | ----------- |
| ```<a></a>``` | Defines a hyperlink. |

| Attribute | Description |
| --------- | ----------- |
| ```href``` | Specifies the URL of the page the link goes to. |
| ```target``` | Specifies where to open the linked document. |

### Text Formatting

- Type: Dependent Tag & Inline Element

| Tag | Description |
| --- | ----------- |
| ```<b></b>``` | Defines bold text. |
| ```<strong></strong>``` | Defines important text. |
| ```<i></i>``` | Defines a part of text in an alternate voice or mood. |
| ```<em></em>``` | Defines emphasized text. |
| ```<mark></mark>``` | Defines marked/highlighted text. |
| ```<small></small>``` | Defines smaller text. |
| ```<del></del>``` | Defines deleted text. |
| ```<ins></ins> or <u></u>``` | Defines inserted text or Underline. |
| ```<sub></sub>``` | Defines subscripted text. |
| ```<sup></sup>``` | Defines superscripted text. |

### HTML Comments

- Use comments to explain code, and to prevent execution when testing alternative code. 
- <!-- This is a comment -->

### HTML Images

- Type: Independent Tag & Inline Element

| Tag | Description |
| --- | ----------- |
| ```<img>``` | Defines an image. |

| Attribute | Description |
| --------- | ----------- |
| ```src``` | Specifies the path to the image. |
| ```alt``` | Specifies an alternate text for the image. |
| ```width``` | Specifies the width of the image. |
| ```height``` | Specifies the height of the image. |

### HTML Tables

- Type: Dependent Tag & Block Element
  
| Tag | Description |
| --- | ----------- |
| ```<table></table>``` | Defines a table. |
| ```<tr></tr>``` | Defines a row in a table. |
| ```<th></th>``` | Defines a header cell in a table. |
| ```<td></td>``` | Defines a cell in a table. |

### HTML Lists

- Type: Dependent Tag & Block Element

| Tag | Description |
| --- | ----------- |
| ```<ul></ul>``` | Defines an unordered list. |
| ```<ol></ol>``` | Defines an ordered list. |
| ```<li></li>``` | Defines a list item. |

### HTML Iframes

- Type: Dependent Tag & Inline Element

| Tag | Description |
| --- | ----------- |
| ```<iframe></iframe>``` | Defines an inline frame. |

| Attribute | Description |
| --------- | ----------- |
| ```src``` | Specifies the URL of the page to embed. |
| ```width``` | Specifies the width of the iframe. |
| ```height``` | Specifies the height of the iframe. |

### HTML Div

- Type: Dependent Tag & Block Element

| Tag | Description |
| --- | ----------- |
| ```<div></div>``` | Defines a section in a document. |
