# Cus-select.js

Plugin for create custom form selects.

## Example for markup
```sh
<select name="name" class="select">
    <option value="Type1">Type1</option>
    <option value="Type2">Type2</option>
    <option value="Type3">Type3</option>
    <option value="Type4">Type4</option>
</select>
<div class="select_block">
    <p class="value">Cuisine Type</p>
    <ul class="list">
        <li class="item">Type1</li>
        <li class="item">Type2</li>
        <li class="item">Type3</li>
        <li class="item">Type4</li>
    </ul>
</div>
```

## Initialization plugin
```sh
$(".select_block").cusSelect()
```

You can use params:
```sh
$(".select_block").cusSelect({
    selectSelector: "#select"
})
```

## Current version
1.0