# Markdown Notes Driven by Docsify

My manually created markdown notes using docsify.

[Docsify](https://docsify.js.org/) is "A magical documentation site generator".

It is more recommended to use `docsify-template` project:

https://github.com/docsifyjs/docsify-template

## Quick Start


```bash
mkdir ./docs

cat << EOL |  tee ./docs/index.html
<!-- index.html -->

<!DOCTYPE html>
<html>
  <head>
    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />
    <meta name="viewport" content="width=device-width,initial-scale=1" />
    <meta charset="UTF-8" />
    <link
      rel="stylesheet"
      href="//cdn.jsdelivr.net/npm/docsify@4/themes/vue.css"
    />
  </head>
  <body>
    <div id="app"></div>
    <script>
      window.$docsify = {
        //...
      };
    </script>
    <script src="//cdn.jsdelivr.net/npm/docsify@4"></script>
  </body>
</html>

EOL

cat << EOL |  tee ./docs/README.md
Docsify test page
EOL

```

## Release on GitHub Pages

```bash
touch ./docs/.nojekyll
```

## Customization / Improvement

### More pages

### navbar

### Cover Page

### Markdown Configuration

