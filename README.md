# custom-inputs


Custom radio buttons and checkboxes with jQuery

## Markup

### Checkboxes

``` html
  <ul class="custom-inputs">
    <li>
      <input id="checkbox1" type="checkbox" name="checkbox1" value="1">
      <label for="checkbox2">Checkbox 1</label>
    </li>
    <li>
      <input id="checkbox2" type="checkbox" name="checkbox2" value="2">
      <label for="checkbox2">Checkbox 2</label>
    </li>    
  </ul>
```

### Radio Buttons

``` html
  <ul class="custom-inputs">
    <li>
      <input id="radio1" type="radio" name="radio" value="1">
      <label for="radio1">Radio 1</label>
    </li>
    <li>
      <input id="radio2" type="radio" name="radio" value="2">
      <label for="radio2">Radio 2</label>
    </li>
  </ul>
```


## Initialize

### Checkboxes

``` js
  <script>
    $('.custom-inputs').customInput('checkbox');
  </script>

```

### Radio Buttons

``` js
  <script>
    $('.custom-inputs').customInput('radio');
  </script>
```