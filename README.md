# iff-foecon
Repository for IFF FoE Con event.

Jinja2 macros were used in development to have repeatable components.
These can be found in `components.html`, but the markup in `index.html`
is simple HTML and can be run independently of `components.html`.

To use Jinja2 for development,
```shell
pip install jinja2-cli

jinja2 components.html -o index.html
```

Jinja2 CLI: [Jinja2 CLI](https://github.com/mattrobenolt/jinja2-cli)
