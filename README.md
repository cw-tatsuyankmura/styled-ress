# styled-ress

ress CSS library for [styled-components](https://styled-components.com/).

The original `ress.css` is pulled from [filipelinhares/ress.css](https://github.com/filipelinhares/ress/blob/master/ress.css), and parsed into styled ready format.

## Innstall

```sh
npm install --save styled-ress
```

### Usage

> This is just usage example

```js
import React from 'react';
import { Ress } from 'styled-ress';

const App = () => (
  <>
    <Ress />
    <Component />
  </>
);
```

Also you can use `injectGlobal` API:

```js
import ress from 'styled-ress';
import { injectGlobal } from 'styled-components';

injectGlobal`
  ${ress}

  // You can continue writing global styles
  body {
    margin: 0;
  }
`;
```

## License

The [MIT License](LICENSE)
