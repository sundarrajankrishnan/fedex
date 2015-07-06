#fedex

## Install

`npm install fedex`

## Usage

```js
  var fedexAPI = require('fedex');

  var fedex = new fedexAPI({
    environment: 'sandbox', // or live
    debug: true,
    key: 'KEY',
    password: 'DEVPASSWORD',
    account_number: 'ACCOUNT#',
    meter_number: 'METER#',
    imperial: true // set to false for metric
  });
```

See `example/index.js` for working samples.