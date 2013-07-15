# Introduction to Javascript

## Reading

Please read MDN's guide before starting the excercise below:
* https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide
 
Here are some ideas on how to style your code:
* Architect: http://javascript.crockford.com/code.html
* Corporate: http://google-styleguide.googlecode.com/svn/trunk/javascriptguide.xml
* Freelance: https://github.com/airbnb/javascript

## Bookmarks

* https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference

## Exercise: HTML5 Graphics

### Overview

Using the `<canvas>` element, please write [Conway's Game of Life](http://en.wikipedia.org/wiki/Conway%27s_Game_of_Life).

There are skeleton [html](life.html) and [js](life.js) files to get you started.

### Canvas

For this exercise, you will be using the [2D Context]((http://www.w3.org/TR/2dcontext2/) for `<canvas>`.

Drawing basic shapes is straightforward:
```javascript
var ctx = canvas.getContext('2d');
ctx.fillRect(x, y, w, h);
```

### Data Modeling

Design your game as an [MVC](http://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller). That is, your data model shouldn't contain any view or controller instructions, your view should not directly manipulate data, etc.

### Event-based programming

Please write event handlers to *Start*, *Stop*, and *Erase* the simulation, and attach these to `<button>` elements.

Clicking on a pixel in the `<canvas>` element should toggle a cell from dead-to-alive.

### Code Isolation

Please read about [self-executing anonymous functions](http://markdalgleish.com/2011/03/self-executing-anonymous-functions/).

### Feedback

When you are done, show your work to a coworker for feedback.
