# Base for handbooks

Steps to run locally:

1. Install ruby [rvm](https://rvm.io/)
1. Run `bundle` to install dependencies
1. Run `bundle exec guard` to start watching changes to the asciidoc files
1. Open `dist/index.html` to view your handbook

> **Note**: For interactions with the guard shell, see [the Interacting with Guard documentation](https://github.com/guard/guard/wiki/Interacting-with-Guard) e.g. `all` will rebuild the project.

To just simply build the handbook run:

```sh
bundle exec asciidoctor src/index.adoc -D dist
```
