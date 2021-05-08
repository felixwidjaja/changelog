# Delivery-docs Theme

Monkey see, monkey do. What's in this directory is just the upstream examples / references with some minor tweaks for color scheme and some basic modifications for for things like the "home" page. These are the source references for context:

* General theme:
    * https://github.com/facelessuser/pymdown-extensions/tree/master/docs/theme
    * https://github.com/squidfunk/mkdocs-material/tree/master/src
* Mermaid setup:
    * https://facelessuser.github.io/pymdown-extensions/extras/mermaid/
* Tabbed extension (see css)
    * https://facelessuser.github.io/pymdown-extensions/extensions/tabbed/
* Snippets
    * https://facelessuser.github.io/pymdown-extensions/extensions/snippets/

The "partials" is just the actual HTML for the component but with our customizations. It's 1-2 line delta and something based on research shouldn't require much maintenance.

The only "custom" part of the assets is our logo and some minor css additions for table formatting, otherwise it's completely stock Pymdown extensions + material.
