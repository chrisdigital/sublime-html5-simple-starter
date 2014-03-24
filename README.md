# Sublime HTML5 Simple Starter

A Sublime Text snippet to generate a stripped down HTML5 Simple Starter template loosely based on HTML5 Boilerplate. 

This is an exercise in creating a custom Sublime Text snippet.

This is based on Sitepoint post and an excerpt from HTML5 & CSS3 for the Real World, by Alexis Goldstein, Louis Lazaris & Estelle Weyl. [See more details](http://www.sitepoint.com/a-basic-html5-template/).

---

If you looking for something more robust, check out: 
- [HTML5 Boilerplate Snippet](https://github.com/sloria/sublime-html5-boilerplate) by @sloria (which inspired this repo)
- [HTML Snippets](https://github.com/joshnh/HTML-Snippets) by @Joshnh 
- [CSS Reset Sublime Snippet](https://github.com/tinacious/CSS-Reset-Sublime-Snippet) by @tinacious 

Here are notes on [how to create your own snippets](http://www.webtempest.com/sublime-text-2-how-to-create-snippets), or deep dive into the latest "unofficial" [documentation](http://docs.sublimetext.info/en/latest/).

---
## Install

### Option 1: Manual

Copy the files to your Packages directory.

### Option 2: Package Control

In the command pallette (Cmd-Shift+P on Mac) type 'Install' then press enter to see a list of packages. Search for 'HTML5 Simple Starter' then press enter to install. Learn more about "[Package Control](https://sublime.wbond.net/)"

## Usage

With a blank HTML file open, type

    html5starter

and press `TAB`. 

Here are some caveats about "[scope](http://stackoverflow.com/questions/19495269/sublime-text-2-code-snippet-not-working-in-proper-scope)." FYI, this snippet has a "global" scope so hints will appear in the default "plain text" and most others -- however, you won't see code highlighting until you switch to the HTML scope.

That generates:

    <!doctype html>

    <html lang="en">
    <head>
      <meta charset="utf-8">

      <title>"Hello World!" -- HTML5 Simple Starter Template</title>
      <meta name="description" content="Hello World!">
      <meta name="author" content="Chrisdigital">

      <link rel="stylesheet" href="css/styles.css?v=1.0">
    <!-- An excerpt from HTML5 & CSS3 for the Real World, by Alexis Goldstein, Louis Lazaris & Estelle Weyl. See more details: http://www.sitepoint.com/a-basic-html5-template/ 
    -->

      <!--[if lt IE 9]>
      <script src="http://html5shiv.googlecode.com/svn/trunk/html5.js"></script>
      <![endif]-->
    </head>

    <body>
        <!-- Add your site or application content here -->
                <p>Hello world! This is HTML5 Simple Starter Template.</p>
      <script src="js/scripts.js"></script>
    </body>
    </html>

## License 

[MIT Licensed](http://chrisdigital.mit-license.org/).