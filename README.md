# TLS Peer Certificate Info

A simple library to get TLS peer certificate information.

Used by [@WooMaiBot](https://t.me/WooMaiBot)

## Usage

```js
const prober = require('@wmlabs/ssl-cert-info')
prober('1.1.1.1', 443, 'cloudflare.com').then(console.log)
```

## License

MIT
