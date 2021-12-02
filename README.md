# react-typescript-rrule-generator

> This is ReactJS project based on Create React Library and using Bootstrap styling. It's built with the help of a great rrule.js library.
It also uses: 
-lodash 
-date-fns 
-@material-ui/pickers.

[![NPM](https://img.shields.io/npm/v/react-rrule-generator-ts.svg)](https://www.npmjs.com/package/react-rrule-generator-ts) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install --save react-typescript-rrule-generator
```

## Usage

```tsx
import React, { Component } from 'react'

import RRuleGeneratorTS, { translations } from 'react-typescript-rrule-generator'
import 'react-typescript-rrule-generator/dist/index.css'

class Example extends Component {
  render() {
    return 
    <RRuleGeneratorTS 
      onChange={(rrule) => console.log(rrule)}
      config={{
        hideStart: false,
      }}
      translations={translations.english}
    />
  }
}
```

## License

MIT © [jdbots](https://github.com/jagdishkumawat30)
