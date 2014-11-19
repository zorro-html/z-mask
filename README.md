# mask

遮罩层

* 可以通过 `this.shown` 属性和 `[shown]` 特性控制显隐
* 默认为隐藏

# Example

```
<jie-mask shown style="background-color: silver; opacity: 0.25;"></jie-mask>

<script>
  var mask = document.querySelector('jie-mask');

  mask.shown = true;
  mask.shown = false;
</script>
```
