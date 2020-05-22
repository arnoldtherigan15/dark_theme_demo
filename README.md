# dark_theme_demo
Super Easy Way to apply dark theme on any website

Dark mode has become incredibly popular in the last year and all popular apps nowadays offer a toggle to turn it on.

<a href="https://darkmodejs.learn.uno/" target="_blank">Darkmode.js</a> is very easy to use, just copy paste the following code or use the npm package.

<h3>🚀 Easy way (using the JSDelivr CDN)</h3>

```html
<script src="https://cdn.jsdelivr.net/npm/darkmode-js@1.5.5/lib/darkmode-js.min.js"></script>
<script>
  new Darkmode().showWidget();
</script>

```

<h3>or 📦 Using NPM</h3>

`npm install darkmode-js`

<p>Then add the following javascript code:</p>

```javascript
import Darkmode from 'darkmode-js';

new Darkmode().showWidget();

```

<h3>Here are the options availables</h3>

```javascript
var options = {
  bottom: '64px', // default: '32px'
  right: 'unset', // default: '32px'
  left: '32px', // default: 'unset'
  time: '0.5s', // default: '0.3s'
  mixColor: '#fff', // default: '#fff'
  backgroundColor: '#fff',  // default: '#fff'
  buttonColorDark: '#100f2c',  // default: '#100f2c'
  buttonColorLight: '#fff', // default: '#fff'
  saveInCookies: false, // default: true,
  label: '🌓', // default: ''
  autoMatchOsTheme: true // default: true
}

const darkmode = new Darkmode(options);
darkmode.showWidget();
```

<p>Boom, the dark mode button will be added on the bottom of your web page</p>

<p>you can see the demo on my website <a href="https://arnoldtherigan15.github.io/dark_theme_demo/" target="_blank">here</a></p>

<p>Custom button or styling you can see on Darkmode.js <a href="https://darkmodejs.learn.uno/" target="_blank">documentation</a><p>