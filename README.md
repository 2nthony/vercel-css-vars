# vercel-css-vars

## Usage

Install:

```console
npm i vercel-css-vars
```

In code:

```js
import 'vercel-css-vars/index.css'
```

## CSS Vars

It might be out-of-date, so check the `index.css` for latest vars.

```css
:root {
  --geist-white: #fff;
  --geist-black: #000;
  --geist-background: var(--geist-white);
  --geist-foreground: var(--geist-black);
  --accents-1: #fafafa;
  --accents-2: #eaeaea;
  --accents-3: #999;
  --accents-4: #888;
  --accents-5: #666;
  --accents-6: #444;
  --accents-7: #333;
  --accents-8: #111;
  --geist-secondary-lighter: var(--accents-2);
  --geist-secondary-light: var(--accents-3);
  --geist-secondary: var(--accents-5);
  --geist-secondary-dark: var(--accents-7);
  --geist-success-lighter: #d3e5ff;
  --geist-success-light: #3291ff;
  --geist-success: #0070f3;
  --geist-success-dark: #0761d1;
  --geist-error-lighter: #f7d4d6;
  --geist-error-light: #ff1a1a;
  --geist-error: #e00;
  --geist-error-dark: #c50000;
  --geist-warning-lighter: #ffefcf;
  --geist-warning-light: #f7b955;
  --geist-warning: #f5a623;
  --geist-warning-dark: #ab570a;
  --geist-violet-lighter: #e3d7fc;
  --geist-violet-light: #8a63d2;
  --geist-violet: #7928ca;
  --geist-violet-dark: #4c2889;
  --geist-cyan-lighter: #aaffec;
  --geist-cyan-light: #79ffe1;
  --geist-cyan: #50e3c2;
  --geist-cyan-dark: #29bc9b;
  --geist-highlight-purple: #f81ce5;
  --geist-highlight-magenta: #eb367f;
  --geist-highlight-pink: #ff0080;
  --geist-highlight-yellow: #fff500;
  --geist-link-color: var(--geist-success);
  --geist-selection: var(--geist-cyan-light);
  --shadow: rgba(0, 0, 0, 0.12);
}

.dark-theme {
  --geist-foreground: var(--geist-white);
  --geist-background: var(--geist-black);
  --geist-selection: var(--geist-highlight-purple);
  --accents-8: #fafafa;
  --accents-7: #eaeaea;
  --accents-6: #999;
  --accents-5: #888;
  --accents-4: #666;
  --accents-3: #444;
  --accents-2: #333;
  --accents-1: #111;
  --geist-secondary-lighter: var(--accents-2);
  --geist-secondary-light: var(--accents-3);
  --geist-secondary: var(--accents-5);
  --geist-secondary-dark: var(--accents-7);
  --geist-error-light: #f33;
  --geist-error: red;
  --geist-error-dark: #e60000;
  --geist-link-color: var(--geist-success-light);
  --geist-selection: var(--geist-highlight-purple);
}
```

## Credits

- [Vercel Design](https://vercel.com/design)

## Author

**Saika** © [evillt](https://github.com/evillt), Released under the [MIT](./LICENSE) License.

Authored and maintained by **EVILLT** with help from contributors ([list](https://github.com/evillt/saika/contributors)).

> [evila.me](https://evila.me) · GitHub [@evillt](https://github.com/evillt) · Twitter [@evillt](https://twitter.com/evillt)
