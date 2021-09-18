# JSON-in-HTML Syntax Support

Syntax highlighting support for HTML `<script></script>` tags using `type=application/json` and `type=application/ld+json` and `type=importmap` attributes.



Any script tag containing "json" in the type attribute, as well as any attribute that starts with '{ or '[ (hopefully).

And import maps.

Acknowledgements:  This owes a huge amount of debt to [this great extension](https://github.com/panoply/vscode-json-script-tag).

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
```