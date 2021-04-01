#  PushSwap UIkit



PushSwap UIkit is a set of React components and hooks used to build pages on PushSwap's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @pushswap/libs`

## Setup

### Theme

Before using Pancake UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@pushswap/libs'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@pushswap/libs'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.
