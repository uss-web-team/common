# CSS

## Reading

* http://www.w3.org/community/webed/wiki/CSS/Training
* http://www.w3.org/Style/Examples/007/units.en.html

## Bookmarks

http://www.w3.org/community/webed/wiki/CSS

## Exercise

### Getting Started

Create a working copy of the [HTML template](css1.html).

The source of this html is borrowed from [Project Gutenberg](http://www.gutenberg.org/files/1162/1162-h/1162-h.htm).

In this exercise, you are going to make the html look much nicer than Gutenberg does.

### General text formatting

Add new CSS code for the `<body>` tag.

```css
body {
  /* your properties go here */
}
```

Set the following properties to values you think look good:

* `width`
* `margin`
* `font-family`
* `font-size`
* `line-height`
* `text-align`
* `letter-spacing`
* `color`
* `background-color`

To get some ideas, read this [blog post](http://www.uxbooth.com/articles/4-tips-and-tricks-for-more-legible-content/) on readability in web documents.

### Fonts

By default, you have only the browser's fonts to work with. Across browsers, you can be certain of little more than a common `monospace`, `sans-serif`, and `serif` family font (Times New Roman, Arial, Courier, etc.). Sometimes these fonts look really nice. Other times you want your text to stand out.

Try importing a custom font. Google offers a font-hosting service you can [experiment with](http://www.google.com/fonts/).

### Media

By default, your CSS will be used for the `screen` [media](http://www.w3.org/TR/CSS2/media.html) type, and potentially any other media from which the HTML is viewed. Without specification, this decision is left to the rendering device (browsers vary in their behavior!). To be specific, add a new CSS rule just for the `print` media. Remember to use the [recommended units](http://www.w3.org/Style/Examples/007/units.en.html) for each distinguished media type.

You can test your `print` style in a browser that supports `print` media by ... .

### Selectors

Add new CSS code to make all paragraphs except the first indented.

```css
p + p {
  /* your code goes here */
}
```

Add new CSS code to make the first letter of the first paragraph of the chapter stand out.

You may find the W3C documentation on [Selectors](http://www.w3.org/community/webed/wiki/CSS/Selectors) helpful.

### Feedback

When you're done, show your work to a coworker and get their feedback. Make changes so that everyone is happy.
