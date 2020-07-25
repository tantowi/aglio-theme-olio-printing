# aglio-theme-olio-printing
a printable olio-based theme (with attributes instead of schema)

Daniel Taylor's [aglio](https://github.com/danielgtaylor/aglio) tool is a nice
renderer for API Blueprints. Aglio comes with a handsomely-styled theme called
[olio](https://github.com/danielgtaylor/aglio/tree/olio-theme#readme). This
repo contains a modified version of [olio-attributes](https://github.com/hajimeni/aglio-theme-olio-attributes)
for printing. Changes:

- @hajimeni's changes in https://github.com/hajimeni/aglio-theme-olio-attributes to add attributes to the aglio output
- removal of the schema's (in favor of attributes only)
- removal of the nav bar
- removal of the 'back to top' floating text
- expand all by default

# Quickstart

```bash
$ sudo npm install -g aglio
$ sudo npm install -g aglio-theme-olio-printing
$ aglio -t olio-printing -i blueprint.apib -o blueprint-printing.html
```

# Original License

Aglio[https://github.com/danielgtaylor/aglio]

Copyright &copy; 2016 Daniel G. Taylor

http://dgt.mit-license.org/

# Acknowledgements

This package is incremental changes on top of [@hajimeni aglio-theme-olio-attributes](https://github.com/hajimeni/aglio-theme-olio-attributes)

This packages (as changes to @hajimeni aglio-theme-olio-attributes) was developed with support from the [National Motor Freight Traffic Association](http://www.nmfta.org) to produce standalone documentation for the [Open Telematics API](https://github.com/nmfta-repo/nmfta-opentelematics-api)
