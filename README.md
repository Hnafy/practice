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

## image
```html
<img> tag. The source file (src), alternative text (alt), width, and height are provided as attributes
```
> [!NOTE]
> alt attribute for an image, if the image for some reason cannot be displayed. This can be due to a slow connection, or an error in the src attribute, or if the user uses a screen reader.

## space before sentence
```html
<blockquote> Defines a section that is quoted from another source
```
## list
```html
<ul> tag defines an unordered (bulleted) list.
<ol> tag defines an ordered list. An ordered list can be numerical or alphabetical.
<li> tag is used to define each list item.
```

## Block and Inline Elements
### block-level elements
```html
- <address>
- <article>
- <aside>
- <blockquote>
- <canvas>
- <dd>
- <div>
- <dl>
- <dt>
- <fieldset>
- <figcaption>
- <figure>
- <footer>
- <form>
- <h1>-<h6>
- <header>
- <hr>
- <li>
- <main>
- <nav>
- <noscript>
- <ol>
- <p>
- <pre>
- <section>
- <table>
- <tfoot>
- <ul>
- <video>
```
### inline elements
```html
- <a>
- <abbr>
- <acronym>
- <b>
- <bdo>
- <big>
- <br>
- <button>
- <cite>
- <code>
- <dfn>
- <em>
- <i>
- <img>
- <input>
- <kbd>
- <label>
- <map>
- <object>
- <output>
- <q>
- <samp>
- <script>
```
```html
- <select>
- <small>
- <span>
- <strong>
- <sub>
- <sup>
- <textarea>
- <time>
- <tt>
- <var>
```

```html
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

## css
CSS stands for Cascading Style Sheets
The style definitions are normally saved in external .css files
Internal CSS
> Internal styles are defined within the <style> element, inside the <head> section of an HTML page
Inline CSS
> Inline styles are defined within the "style" attribute of the relevant element
External CSS
> If some properties have been defined for the same selector (element) in different style sheets after the link to the external style sheet by <link> element, inside the <head> section of an HTML page
> [!NOTE]
> universal selector (*) selects all HTML elements on the page.
> write a period (.) character, followed by the class name.
> write a hash (#) character, followed by the id of the element.

## color
In CSS, colors can also be specified using RGB values, HEX values, HSL values, RGBA values, and HSLA values
```css
background-color: DodgerBlue;
color: Tomato;
border: 2px solid Violet;
```

## background
### background-color
background-color property specifies the background color of an element.
opacity property specifies the opacity/transparency of an element. It can take a value from 0.0 - 1.0. The lower value, the more transparent
### background-image
background-image property specifies an image to use as the background of an element.
By default, the image is repeated so it covers the entire element we can use background-repeat: no-repeat;
background-position property is used to specify the position of the background image.
The background-attachment property specifies whether the background image should scroll or be fixed (will not scroll with the rest of the page)
background-size property specifies the size of the background images.