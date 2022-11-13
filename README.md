## alertJS

<strong>alertJS</strong>, which currently has a very simple interface design and functionality, will evolve over time. The set target is to offer some features that are not currently available.

To integrate <strong>alertJS</strong> into your software, all you have to do is paste the <code><script src="https://cdn.jsdelivr.net/gh/dvlt39/alertJS/alert.js"></script></code> tag between your codes. After that, you need to run the <strong>alertJS</strong> function.

The function structure is as you see below.

<code>alertJS(message, type, duration)</code>

In the <code>Message</code> section you will write the text to be displayed on the screen, in the <code>type</code> section you will write the type of warning, in the <code>duration</code> section you will write it will how long it will appear on the screen.

For example:

```js
alertJS("Hello world", "success", 3000);
```

If you leave the <code>duration</code> field blank, 5 seconds will appear on the screen.