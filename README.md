# `<z-mask>`

Mask element, which could toggle with `this.shown` or `[shown]` attribute

## Import

```
<link rel="import" href="z-mask/z-mask.html">
```

## Examples

```
<z-btn id="z-mask-toggle">Show Mask for 1 seconds</z-btn>
<z-mask id="z-mask-test" style="background-color: silver; opacity: 0.25;"></z-mask>

<script>
  var mask = document.querySelector('html /deep/ #z-mask-test');
  var btn = document.querySelector('html /deep/ #z-mask-toggle');

  btn.addEventListener('click', function () {
    mask.shown = true;
    setTimeout(function () {
      mask.shown = false;
    }, 1000);
  });
</script>
```
