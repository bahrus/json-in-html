[![Install](https://img.shields.io/badge/vscode-install-blue.svg)](https://marketplace.visualstudio.com/items?itemName=andersonbruceb.json-in-html)

# JSON-in-HTML Syntax Support

This VSCode extension provides syntax highlighting support for HTML:

First, extends [this great extension](https://github.com/panoply/vscode-json-script-tag), and supports two addition script types:

`<script></script>` tags using 

1.  `type=application/json` or
2.  `type=application/ld+json` or
3.  `type=json` or 
4.  `type=importmap` attributes.

will provide JSON editing capabilities inside the script tags.

In addition, json-in-html supports editing json within html tag attributes.

This is helpful for web components, which often make heavy use of JSON-serialize attributes.

## Examples

```html
<script type="application/json">
  /* JSON HERE */
</script>

<script type="application/ld+json">
  /* JSON HERE */
</script>

<script type="importmap">
    /* JSON HERE */
</script>

<script type="json">
    /* JSON HERE */
</script>

<script type='application/json'>
  /* JSON HERE */
</script>

<script type='application/ld+json'>
  /* JSON HERE */
</script>

<script type='importmap'>
    /* JSON HERE */
</script>

<script type=json>
    /* JSON HERE */
</script>

<script type=application/json>
  /* JSON HERE */
</script>

<script type=application/ld+json>
  /* JSON HERE */
</script>

<script type=importmap>
    /* JSON HERE */
</script>

<script type=json>
    /* JSON HERE */
</script>

<div attr='
  {"x": "hello"}
'></div>
```