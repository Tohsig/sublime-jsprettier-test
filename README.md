# Bug reproduction

To test:

1. `npm install`
2. Run `JsPrettier: Format Code` on `src/test.html`.

Expected output:

```html
<div class="grid grid-cols-2">Hello world</div>
```

Received output:

```html
[35m🌼 daisyUI components 2.19.0[0m [0m https://github.com/saadeghi/daisyui
  [32m✔︎ Including:[0m [0m base, components, themes[29], utilities
  
<div class="grid grid-cols-2">Hello world</div>
```

Versions:

- Sublime Text: `Build 4126`
- JsPrettier: `1.60.6`
- macOS: `12.3.1`