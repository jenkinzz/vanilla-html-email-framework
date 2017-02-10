# The Vanilla HTML Email Framework

The Vanilla Framework is a lean HTML template combined with an external CSS stylesheet to make emails easy.

Vanilla leverages CSS inliners to allow designers to use the full power of HTML/CSS to build robust emails, while still displaying uniformly across all clients. No additional software or coding languages are required.

## Quick start
Choose one of the following options:

* Download the latest release [here](https://github.com/jenkinzz/vanilla-html-email-framework/releases) and open [Getting Started.md](src/Getting Started.md)  
* Just link the CSS Resets into your template like so: `<link rel="stylesheet" type="text/css" href="http://git.jasonjensen.co/src/main.css">`

Make sure to inline your CSS before sending. I recommend [Putsmail](https://putsmail.com/inliner)

## Features

* Uses only vanilla HTML/CSS
* As semantic and lean as possible. No useless nested tables
* CSS is embedded, not inlined, so you can use classes, ids, and selectors
* Includes useful snippets and example templates
* Modular design for mixing and matching
* Comments to guide you, and cheat-sheets for reference

## Client Support
All clients are supported unless listed here:

Mostly Supported:

* Outlook 2003
  * Ignores email width
* Android IMAP
  * Ignores media queries
  * Ignores font-family
  
Unsupported:

* Lotus Notes
