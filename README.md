HAML HTML5 Boilerplate
======================

### A leaner HAML HTML5 boilerplate for "mobile first" responsive web design

Whilst HTML5 boilerplates are great tools, they can sometimes in the wrong hands result in over bloated HTML5. Ditch the excess boilerplate markup that's there "just in case" and adopt leaner "mobile first" responsive web design.
Haml doesn't have both start and end for each element like eRuby. eRuby syntax looks a lot like HTML and is thereby more HTML-like while Haml is more CSS-like. Haml uses indentation to nest tag elements whereas eRuby uses the same HTML representation.

By utilising HAML comments, this boilerplate still includes the kitchen sink "just in case", however, all but the most essentials have been commented out. As a result, it compiles to just:

```html
<!DOCTYPE html>
<html class="no-js" lang="en">
    <head>
        <meta charset="utf-8">
        <title></title>
        <meta content="" name="description">
        <meta content="width=device-width, initial-scale=1" name="viewport">
        <link href="/favicon.ico" rel="shortcut icon">
        <link href="/css/base.css" rel="stylesheet">
    </head>
    <body>
    </body>
</html>
```

This should be enough to get started. If you need anything else, just uncomment and compile.

### Legacy IE and "mobile first"

There are several options included for dealing with legacy IE browsers for "mobile first" design:

1. Choose between Paul Irish's `<html>` tag conditional classes hack or the more traditional conditional stylesheets. Paul Irish's hack is disabled by default as it's not always necessary on every site.

2. Use a CSS3 media query polyfill such as respond.js (this can be included in a custom [Modernizr](http://modernizr.com/) build) to enable media queries in older IE.

3. Adopt a fixed-width layout for legacy IE (no polyfills), [using SASS to help compile the IE stylesheets](http://nicolasgallagher.com/mobile-first-css-sass-and-ie/).

#### Credits

- Rachael Andrew's "HTML5 boilerplate" in her excellent article [Stop solving problems you don’t yet have](http://www.rachelandrew.co.uk/archives/2012/03/21/stop-solving-problems-you-dont-yet-have/) was a big infulence on the default markup this boilerplate compiles to.
- Whilst you're there, also read [Responsibly Responsive: developing the Greenbelt website](http://www.rachelandrew.co.uk/archives/2012/03/16/responsibly-responsive-developing-the-greenbelt-website/).
- Jeremy Keith's [dConstruct optimisation](http://adactio.com/journal/5439/) is an excellent starting point for "mobile first" optimisation.
