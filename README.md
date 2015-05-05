# `<z-mask>`

Mask element, which could toggle with `this.shown` or `[shown]` attribute

## Examples

```
<z-mask id="z-mask-test" shown style="background-color: silver; opacity: 0.25;"></z-mask>

<script>
  var mask = document.querySelector('html /deep/ #z-mask-test');

  mask.shown = true;
  mask.shown = false;
</script>
```
