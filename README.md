# CandourNormalize

This is an extremely minimal normalization library that helps you inject
some basic CSS normalization through [Radium](https://formidable.com/open-source/radium/).

## Install

To install [candour-normalize](https://github.com/candourpro/normalize):
```
yarn add candour-normalize
# or
npm install candour-normalize --save
```

## Usage

```jsx
import React from 'react'
import { render } from 'react-dom'
import CandourNormalize from 'candour-normalize'

render(
  <div>
    <CandourNormalize />

    Your app CSS is now normalized
  </div>,
  document.getElementById('root')
)
```

## What's in it

[candour-normalize](https://github.com/candourpro/normalize) is really simple.
The gist is that it uses `Radium` to inject some styles over the `*` CSS. Check
out the injected styles
[here](https://github.com/candourpro/normalize/blob/master/lib/rules.js).

## Dependencies

- [React](https://reactjs.org)
- [Radium](https://formidable.com/open-source/radium/)

## Candour

For usage with Candour, check [here](https://candour.pro/docs/getting-started/normalize).
