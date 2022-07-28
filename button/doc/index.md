# Button

This is a button component.

```js script
import { html } from 'lit';
import '~/tokens/variables.css';
import '../src/button.css';
```

```js preview-story
export const base = () => html` <button class="btn">Click me!</button> `;
```

```js preview-story
export const outline = () =>
  html` <button class="btn" outline>Click me!</button> `;
```

```js preview-story
export const disabled = () =>
  html` <button class="btn" disabled>Click me!</button> `;
```
