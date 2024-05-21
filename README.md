# cache

A TypeScript utility for caching results of method executions.

```ts
class {
  @cache()
  async foo() {
    // ...
  }
}
```

## Install

### Node.js

Install using `npm` or other package managers:

```
npm install 1ib/cache
```

Import into your Node.js project:

```js
// CommonJS
const { cache } = require("1ib/cache")

// ESM
import { cache } from "1ib/cache"
```

### Deno

Install using [JSR](https://jsr.io):

```shell
deno add 1ib/cache

#or

jsr add 1ib/cache
```

Then import into your Deno project:

```js
import { cache } from "1ib/cache"
```

### Bun

Install using this command:

```
bun add 1ib/cache
```

Import into your Bun project:

```js
import { cache } from "1ib/cache"
```

### Browser

It's recommended to import the minified version to save bandwidth:

```js
import { cache } from "https://cdn.skypack.dev/1ib/cache?min"
```

However, you can also import the unminified version for debugging purposes:

```js
import { cache } from "https://cdn.skypack.dev/1ib/cache"
```

## License

This project is licensed under the MIT.

## Author

[kingcc](https://github.com/kingcc)
