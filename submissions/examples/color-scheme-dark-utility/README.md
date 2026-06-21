# Color Scheme Dark Utility

Introduces the browser-native dark configuration hint token (`.ease-color-scheme-dark`) under issue #15153.

## Functional Mechanics

- **The Problem:** Even when custom CSS classes enforce dark backgrounds (`background-color: #121212`), native browser elements—such as input forms, textareas, checkboxes, drop-down selection arrays, and window scrollbars—continue to render with light user-agent presets. This causes harsh visual contrast leaks.
- **The Solution:** Syncs native engine painting. The `.ease-color-scheme-dark` class signals the rendering engine that the container is optimized for a dark profile. This tells the browser to automatically paint form controls, interactive surfaces, and scroll tracks using dark system colors.

## Usage Layout Structure
```html
<div class="ease-color-scheme-dark">
  </div>
```

Closes #15153
