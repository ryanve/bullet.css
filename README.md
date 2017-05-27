# bullet.css

### `.bullet-none`
- Sets `list-style` to `none`
- Can be used on `li` itself or its `ul` or `ol` to affect all children
- Works only when `display` is `list-item`

### `ul` example

```html
<ul class="bullet-none">
  <li>item
  <li>item
</ul>
```

### `li` example

```html
<ul>
  <li class="bullet-none">item
  <li class="bullet-none">item
</ul>
```
