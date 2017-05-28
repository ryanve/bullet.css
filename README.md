# bullet.css

## [Classes](bullet.css)

- work on `li` itself or its `ul` or `ol` to affect all children
- only apply `list-item` display

### `.bullet-disc`
- sets `list-style` to `disc`

### `.bullet-circle`
- sets `list-style` to `circle`

### `.bullet-square`
- sets `list-style` to `square`

### `.bullet-none`
- sets `list-style` to `none`

## [Examples](https://ryanve.github.io/bullet.css/)

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

## [Setup](https://www.npmjs.com/package/bullet.css)

```
npm install bullet.css
```

```css
@import 'node_modules/bullet.css/bullet';
```
