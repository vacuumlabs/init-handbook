# Base for handbooks

Steps to run locally:

1. Install ruby [rvm](https://rvm.io/)
2. Run `bundle` to install dependencies
3. Run `bundle exec guard` to start watching changes to the asciidoc files
4. Open `dist/index.html` to view your handbook

For interactions with the guard shell, see [link](https://github.com/guard/guard/wiki/Interacting-with-Guard).
(e.g. `all` will rebuild the project)

To just simply build the handbook run:
```
bundle exec asciidoctor src/index.adoc -D dist
```

