# Getting Started
In this package, you will find:
* `Getting Started.md` - The file you are reading now.
* `index.html` - An empty HTML template, ready to be copied and developed into a real email.
* `main.css`* - A copy of the CSS Resets linked in index.html.
* `modules/` - Useful snippets to use in development
* `examples/` - Pre-built HTML templates for you to build off of.

All you need to do is start building! Below are some conventions to follow and reference sheets for you to use during development.

## Necessary Conventions
The following are things you must do for the template to render correctly. Unfortunately, email design still has many quirks and it's hard to find other solutions. Until then, make sure you:
* Resize images using both `width=""` and `style="width:;"`. Outlook only recognizes the former, while all other clients respect the latter.
* Classes that deal with margin and padding must be declared on a `<td>`, for Outlook compatability. Declaring all classes on a `<td>` unless abolutely necessary is a good idea. 
* Buttons are made by adding the `.button` class to a `<table>`. See the file in `examples/` for more information.

## Useful Conventions
These conventions aren't entirely necessary, but they do help make development easier:

* `.container` gives a padding of 20px. It's usually used on the top-most `<td>`, to create margins around the email.
* `.padded` adds 10px of padding to the top and bottom, it's useful when something needs a little breathing room.
* `.full` and `.half` expand to full-width and half-width under 600px, respectively.
* `.column` adds 5px of padding between columns, to help with breathing room.
* `.left`, `.right`, and `.center` can be used to define horizontal alignment.
* `.top`, `.middle`, `.baseline`, and `.bottom` can be used to define vertical alignment.
* `.hide` forces an element not to display.
* `.desktop` and `.mobile` force elements to display only on desktop and mobile, respectively.
* `.big` and `.small` allow for changing font sizes without having to write a bunch of code.

Since you don't have to write inlined CSS, you can create your own classes to use during development. For instance, `.green` might be useful to define all the modules that should have a green background. The sky is the limit!

The `<head>` contains two style blocks, one to create a re-useable template and another to address quirks in any specific email. It's useful for creating a style guide you can copy-and-paste to other emails, while still addressing any problems that come up in development.

## Other Things to Know

The template has a max width of 700px, with 2 break points at 600px and 440px. It uses 14px Arial by default. To explore all the default styles, check out `unit-test.html` in the `examples/` folder.

[http://placehold.it](http://placehold.it) is very useful to quickly create placeholder images. Check out their website to find out how.
 


