# Sublime HTML5 Simple Starter

A Sublime Text snippet to generate a stripped down HTML5 Simple Starter template loosely based on HTML5 Boilerplate (v4.3.0) template.

## Install

### Option 1: Manual

Copy the files to your Packages directory.

### Option 2: Package Control

In the command pallette (Cmd-Shift+P on Mac) type 'Install' then press enter to see a list of packages. Search for 'HTML Boilerplate' then press enter to install.

## Usage

With a blank HTML file open, type

    htmlstarter

and press `TAB`.

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