# Enable cors proxy

Proxy for enable cors written in Golang (for development, don't use in production)

Add this headers to response: Access-Control-Allow-Origin: *, Access-Control-Allow-Methods: *, Access-Control-Allow-Headers: *

https://enable-cors.awesomeapi.com.br/api?u=YOUR-URL

```sh
$ curl https://enable-cors.awesomeapi.com.br/api?u=https://economia.awesomeapi.com.br/all/usd
```
