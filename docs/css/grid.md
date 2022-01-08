# Grid
We are using a standard 12 column fluid responsive grid system. The grid helps you layout your page in an ordered, easy fashion.

## Container

The `matify:container` class is not strictly part of the grid but is important in laying out content. It allows you to center your page content. The `matify:container` class is set to ~70% of the window width. It helps you center and contain your page content. We use the `matify:container` to contain our body content.

<iframe height="300" style="width: 100%;" scrolling="no" title="Matify container" src="https://codepen.io/ManuTheCoder/embed/preview/NWaLxve?default-tab=result&editable=true&theme-id=light" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/ManuTheCoder/pen/NWaLxve">
  Matify container</a> by ManuTheCoder (<a href="https://codepen.io/ManuTheCoder">@ManuTheCoder</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>


## Grid

<iframe height="300" style="width: 100%;" scrolling="no" title="Untitled" src="https://codepen.io/ManuTheCoder/embed/preview/VwMGeWz?default-tab=result&editable=true&theme-id=light" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/ManuTheCoder/pen/VwMGeWz">
  Untitled</a> by ManuTheCoder (<a href="https://codepen.io/ManuTheCoder">@ManuTheCoder</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>


```html
<div class="matify:row">
    <div class="matify:ripple matify:col-12">100%</div>
  </div>

  <div class="matify:row">
    <div class="matify:ripple matify:col-6">50%</div>
    <div class="matify:ripple matify:col-6">50%</div>
  </div>

  <div class="matify:row">
    <div class="matify:ripple matify:col-4">33%</div>
    <div class="matify:ripple matify:col-4">30%</div>
    <div class="matify:ripple matify:col-4">33%</div>
  </div>

  <div class="matify:row">
    <div class="matify:ripple matify:col-3">25%</div>
    <div class="matify:ripple matify:col-3">25%</div>
    <div class="matify:ripple matify:col-3">25%</div>
    <div class="matify:ripple matify:col-3">25%</div>
  </div>

  <div class="matify:row">
    <div class="matify:ripple matify:col-1">10%</div>
    <div class="matify:ripple matify:col-1">10%</div>
    <div class="matify:ripple matify:col-1">10%</div>
    <div class="matify:ripple matify:col-1">10%</div>
    <div class="matify:ripple matify:col-1">10%</div>
    <div class="matify:ripple matify:col-1">10%</div>
    <div class="matify:ripple matify:col-1">10%</div>
    <div class="matify:ripple matify:col-1">10%</div>
    <div class="matify:ripple matify:col-1">10%</div>
    <div class="matify:ripple matify:col-1">10%</div>
    <div class="matify:ripple matify:col-1">10%</div>
    <div class="matify:ripple matify:col-1">10%</div>
  </div>

  <div class="matify:row">
    <div class="matify:ripple matify:col-7">~70%</div>
    <div class="matify:ripple matify:col-5">~30%</div>
  </div>

  <div class="matify:row">
    <div class="matify:ripple matify:col-2">2</div>
    <div class="matify:ripple matify:col-4">4</div>
    <div class="matify:ripple matify:col-4">4</div>
    <div class="matify:ripple matify:col-2">2</div>
  </div>

```

### Responsive 
Add `@md` for tablet, and `@sm` for mobile phone
<iframe height="300" style="width: 100%;" scrolling="no" title="Untitled" src="https://codepen.io/ManuTheCoder/embed/preview/dyVqGeV?default-tab=result&editable=true&theme-id=light" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/ManuTheCoder/pen/dyVqGeV">
  Untitled</a> by ManuTheCoder (<a href="https://codepen.io/ManuTheCoder">@ManuTheCoder</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>

```html
<div class="matify:row">
  <div class="matify:ripple matify:col-6 matify:col-12@md">50%, but on a tablet it will be 100%</div>
  <div class="matify:ripple matify:col-6 matify:col-12@md">50%, but on a tablet it will be 100%</div>
</div>

<div class="matify:row">
  <div class="matify:ripple matify:col-6 matify:col-12@sm">50%, but on a phone it will be 100%</div>
  <div class="matify:ripple matify:col-6 matify:col-12@sm">50%, but on a phone it will be 100%</div>
</div>
```

### Grid Classes

| Class       | Width |
| ----------- | ----------- |
| `.matify:col-1`      | ~8%       |
| `matify:col-2 `   | ~16%        |
| `matify:col-3 `   | 25%        |
| `matify:col-4 `   | ~33%        |
| `matify:col-5 `   | ~42%        |
| `matify:col-6 `   | 50%        |
| `matify:col-7 `   | ~58%        |
| `matify:col-8 `   | ~67%        |
| `matify:col-9 `   | 75%        |
| `matify:col-10`   | ~83%        |
| `matify:col-11`   | ~91%        |
| `matify:col-12`   | 100%        |
