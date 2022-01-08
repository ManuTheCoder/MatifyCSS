# Text inputs

<iframe height="300" style="width: 100%;" scrolling="no" title="MatifyCSS text inputs" src="https://codepen.io/ManuTheCoder/embed/preview/ExweNKv?default-tab=result&editable=true&theme-id=light" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/ManuTheCoder/pen/ExweNKv">
  MatifyCSS text inputs</a> by ManuTheCoder (<a href="https://codepen.io/ManuTheCoder">@ManuTheCoder</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>

<!-- tabs:start -->
### **HTML**
```html
<div class="matify:input">
  <input type="text">
  <label>Your email</label>
</div>

<div class="matify:input matify:input@outline">
  <input type="text">
  <label>Your email</label>
</div>

<div class="matify:input matify:input@line">
  <input type="text">
  <label>Your email</label>
</div>
```
### **JavaScript**
```js
var Components = new MatifyComponents();
Components.BindInputs();
```
<!-- tabs:end -->