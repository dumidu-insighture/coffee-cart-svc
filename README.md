# coffee-cart-svc
# making a change to test pipelines after ownership transfer.

A simple Coffee Service

Create a `config.json` file inside `src/configs` to start

```js
interface Config {
  port: number;
  mongodb: {
    uri: string,
  };
  redis: {
    host: string;
    port: number;
  };
}
```
