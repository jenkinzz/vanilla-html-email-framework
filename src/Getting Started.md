# Getting Started
In this package, you will find:
* `Getting Started.md` - The file you are reading now.
* `index.html` - An empty HTML template, ready to be copied and developed into a real email.
* `main.css`* - A copy of the CSS Resets linked in index.html.
* `modules/` - Useful snippets to use in development
* `examples/` - Pre-built HTML templates for you to build off of.

All you need to do is start building! Below are some conventions to follow and reference sheets for you to use during development.

## Necessary Conventions
The following are things you must do for the template to render correctly. 

* Inline your CSS before sending. I recommend [Putsmail](http://putsmail.com/inliner)
* Declare background color on `#body-fix`, not `<body>`, for Yahoo compatability.
* Resize images using both `width=""` and `style="width:;"`. Outlook only recognizes the former, while all other clients respect the latter.

## Useful Tips
Here are some things Vanilla includes to make development easier:

Since you don't have to write inlined CSS, you can create your own classes to use during development. For instance, `.green` might be useful to define all the modules that should have a green background. The sky is the limit!

The `<head>` contains two style blocks, one to create a re-useable template and another to address quirks in any specific email. It's useful for creating a style guide you can copy-and-paste to other emails, while still addressing any problems that come up in development.

There are baked-in classes you can use:

* `.container` gives a padding of 20px. It's usually used on the top-most `<td>`, to create margins around the email.
* `.padded` adds 10px of padding to the top and bottom, it's useful when something needs a little breathing room.
* `.full` and `.half` expand to full-width and half-width under 600px, respectively.
* `.column` adds 5px of padding between columns, to help with breathing room.
* `.button` creates a button when placed on a `<table>`.
* `.left`, `.right`, and `.center` can be used to define horizontal alignment.
* `.top`, `.middle`, `.baseline`, and `.bottom` can be used to define vertical alignment.
* `.hide` forces an element not to display.
* `.desktop` and `.mobile` force elements to display only on desktop and mobile, respectively.
* `.big` and `.small` allow for changing font sizes without having to write a bunch of code.

[http://placehold.it](http://placehold.it) is very useful to quickly create placeholder images. Check out their website to find out how.
 


