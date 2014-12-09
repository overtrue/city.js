city.js
=======

城市选择控件

#Usage

html:

```html
省：<select name="province" id="province"></select> 
市：<select name="city" id="city"></select> 
区：<select name="area" id="area"></select> 
```

js:
```js

<script src="assets/js/city.js"></script>
<script>
$(function(){
   city_selector();
});
</script>
```

#Settings

```js
var config = {
    province: '#province',
    city: "#city",
    area: "#area",
};
city_selector(config);
```
