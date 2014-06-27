nojs
====

Notify when javascript is disabled in your browser

### Disable javascript to test demonstration

```html
<!-- You can activate and deactivate your noJS (ON & OFF) -->
<noscript nojs="on">Hey I am <span>Friend</span> active javascript!<br>Please refresh the page.</noscript>
```

```css
[nojs="on"] {
  position: fixed;
  display: block;
  text-align: center;
  background-color: #2E3237;
  font-family: "Arial", sans-serif;
  font-weight: bold;
  font-size: 3em;
  color: #fff;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  padding: 2.80em 0 0 0;
  min-height: 100%;
  min-width: 100%;
  z-index: 100000;
}
[nojs="on"] span {
  color: #55acee;
}
[nojs="off"] {
  display: none; /* used to disable off */
}
```
