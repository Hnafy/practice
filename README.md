# practice
## make file.html
## make base
```html
<!DOCTYPE html>
<html>
<head>

</head>
<body>

</body>
</html> 
```
```html
> <!DOCTYPE html> declaration represents the document type, and helps browsers to display web pages correctly
```

## title
```html
<title> tag defines the title of the document.
```

## format
```html
<b> - Bold text
<strong> - Important text
<i> - Italic text
<em> - Emphasized text
<mark> - marked/highlighted text
<small> - Smaller text
<del> - Deleted text
<ins> - Inserted text
<sub> - Subscript text
<sup> - Superscript text
```

## heading
```html
<h1> defines the most important heading. <h6> defines the least important heading
```

## paragraph
```html
<p> element defines a paragraph
```

## paragraph_formatted
```html
<pre>	Defines pre-formatted text example
 
<pre>
This is
a paragraph
with line breaks.
</pre> 

the same 

<p>This is<br>a paragraph<br>with line breaks.</p>
```

## link
```html
<a href="your link" target="_blank">This is a link</a>
```

| Value | Description |
| ------ | ------ |
| _blank | Opens the linked document in a new window or tab |
| _parent | Opens the linked document in the parent frame |
| _top | Opens the linked document in the full body of the window |

## image
```html
<img> tag. The source file (src), alternative text (alt), width, and height are provided as attributes
@ -163,11 +157,13 @@
> <div> The element is often used as a container for other HTML elements.
> <span> The element is an inline container used to mark up a part of a text, or a part of a document.
```

## new line
```html
<br> This elements to make new line
```
> [!NOTE]
> <br> do not have an end tag

## forms
```html
<label> tag defines a label for many form elements.
<input type="text">	Displays a single-line text input field
<input type="email"> is used for input fields that should contain an e-mail address.
<input type="radio">	Displays a radio button (for selecting one of many choices)
<input type="checkbox">	Displays a checkbox (for selecting zero or more of many choices)
<input type="submit">	Displays a submit button (for submitting the form)
<input type="button">	Displays a clickable button
<textarea>	Defines a multiline input control (text area)
<fieldset>	Groups related elements in a form
<select>	Defines a drop-down list
<option>	Defines an option in a drop-down list
<datalist>	Specifies a list of pre-defined options for input controls
```
> [!NOTE]
> The for attribute of the <label> tag should be equal to the id attribute of the <input> element to bind them together.
