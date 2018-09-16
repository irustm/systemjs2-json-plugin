SystemJS 2 Json Plugin
===

## Usage

```html
<script src="systemjs/dist/system.js"></script>
<script src="dist/systemjs2-json-plugin.js"></script>
<script>
  System.import('/test/conf.json').then(res=>console.log(res));
</script>
```

## TODO

- Add tests

## LICENSE

MIT