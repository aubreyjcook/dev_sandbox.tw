# Tailwind Templates

## Purpose

A collection of templates created using Tailwind CSS.

## Table of Contents

## CSS Templates

## Tailwind Config Templates

**Minimal Config**

```js
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

**Responsive Breakpoints Config**

```js
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [],
  theme: {
  screens: {
      sm: '480px',
      md: '768px',
      lg: '976px',
      xl: '1440px',
    },
    extend: {},
  },
  plugins: [],
  variants: {
    extend: {
    },
  },
}
```