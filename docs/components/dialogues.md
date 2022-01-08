# Modals
To initialize a modal, call the `new MatifyComponents()` class, and then call the `Components.Modal.init` class

<iframe height="300" style="width: 100%;" scrolling="no" title="Matify Modals" src="https://codepen.io/ManuTheCoder/embed/preview/JjraXYM?default-tab=result&editable=true&theme-id=light" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/ManuTheCoder/pen/JjraXYM">
  Matify Modals</a> by ManuTheCoder (<a href="https://codepen.io/ManuTheCoder">@ManuTheCoder</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>

## Non closable
<iframe height="300" style="width: 100%;" scrolling="no" title="Untitled" src="https://codepen.io/ManuTheCoder/embed/preview/WNZgxJM?default-tab=result&editable=true&theme-id=light" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/ManuTheCoder/pen/WNZgxJM">
  Untitled</a> by ManuTheCoder (<a href="https://codepen.io/ManuTheCoder">@ManuTheCoder</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>


<!-- tabs:start -->

#### **HTML**

```html	

<button class="matify:button matify:ripple matify:ripple@light" onclick="Components.Modal.open('#nonDismiss')">
  Open modal (Non-dismissible)
</button>

<div class="matify:modal" id="nonDismiss">
  <div class="matify:modal-content">
    <b>Delete account?</b>
    <p>This action is irreversible</p>
  </div>
  <div class="matify:modal-footer">
    <button class="matify:button matify:button@pill red lighten-5 matify:button@flat matify:ripple black-text" onclick="Components.Modal.close('#nonDismiss')">
      Cancel
    </button>
    <button class="matify:button matify:button@pill red darken-3 matify:ripple matify:button@flat matify:ripple@light" onclick="Components.Modal.close('#nonDismiss')">
      Delete
    </button>
  </div>
</div>
```

#### **JavaScript**


```js	
var Components = new MatifyComponents();
Components.Modal.init("#nonDismiss", {
  dismissible: false,
  callbacks: {
    openend() {
      console.log("Finished opening");
    },
    openstart() {
      console.log("Started opening");
    },
    closestart() {
      console.log("Started closing");
    },
    closeend() {
      console.log("Ended closing");
    }
  }
});

```

<!-- tabs:end -->

## Fullscreen
<iframe height="300" style="width: 100%;" scrolling="no" title="Untitled" src="https://codepen.io/ManuTheCoder/embed/preview/yLzxayw?default-tab=result&editable=true&theme-id=light" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/ManuTheCoder/pen/yLzxayw">
  Untitled</a> by ManuTheCoder (<a href="https://codepen.io/ManuTheCoder">@ManuTheCoder</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>


<!-- tabs:start -->

#### **HTML**

```html	

<button class="matify:button matify:ripple matify:ripple@light" onclick="Components.Modal.open('#nonDismiss')">
  Open modal (Non-dismissible)
</button>

<div class="matify:modal matify:modal@fullscreen" id="nonDismiss">
  <div class="matify:modal-content">
    <b>Delete account?</b>
    <p>This action is irreversible</p>
  </div>
  <div class="matify:modal-footer">
    <button class="matify:button matify:button@pill red lighten-5 matify:button@flat matify:ripple black-text" onclick="Components.Modal.close('#nonDismiss')">
      Cancel
    </button>
    <button class="matify:button matify:button@pill red darken-3 matify:ripple matify:button@flat matify:ripple@light" onclick="Components.Modal.close('#nonDismiss')">
      Delete
    </button>
  </div>
</div>
```

#### **JavaScript**


```js	
var Components = new MatifyComponents();
Components.Modal.init("#nonDismiss", {
  dismissible: false,
  callbacks: {
    openend() {
      console.log("Finished opening");
    },
    openstart() {
      console.log("Started opening");
    },
    closestart() {
      console.log("Started closing");
    },
    closeend() {
      console.log("Ended closing");
    }
  }
});

```
<!-- tabs:end -->
