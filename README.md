# Fishstix Finance UIkit

[![Version](https://img.shields.io/npm/v/fishstix-uikit)](https://www.npmjs.com/package/fishstix-uikit) [![Size](https://img.shields.io/bundlephobia/min/fishstix-uikit)](https://www.npmjs.com/package/fishstix-uikit)

Fishstix Finance UIkit is a set of React components and hooks used to build pages on Fishstix's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add fishstix-uikit`

## Setup

### Theme

Before using Fishstix Finance UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from 'fishstix-uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from 'fishstix-uikit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.

## How to use the UIkit

If you want to use components from the UIkit, check the [Storybook documentation](https://fishstix.github.io/fishstix-uikit/)
