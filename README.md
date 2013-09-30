abn-input
=========

A simple jQuery plugin to give your inputs validation handling for Australian Business Numbers (ABN)

### Demo

http://clockwerx.github.io/abn-input/

  
### Usage

Include the library

``` html
<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.10.2/jquery.min.js"></script>
<script src="abn.js"></script>
```
   
Add hooks to your inputs

``` html
<input class="abn" placeholder="XX XXX XXX XXX" />
```
   
Bind the controls
``` html
<script type="text/javascript">
  $().ready(function () {
   $('.abn').bindABNControls();
  });
</script>
```

### Licensing


This component is licensed under the AGPL, however commercial users can purchase a [commercial license](http://www.binpress.com/license/view/l/a9589a069180d1419ddcda5a59c959d6).

[Read on to find out more](http://clockwerx.github.io/abn-input/)
