# groupby-polyfill <img src="https://user-images.githubusercontent.com/1148376/183421896-8fea5bef-6d32-4f49-ab6c-f2fe7e6ac4ab.svg" width="20px" height="20px" title="This package contains built-in JSDoc declarations (...works as equally well as d.ts)" alt="JSDoc icon, indicating that this package has built-in type declarations">

A small polyfill with zero-dependency that do just do one thing.

`npm install groupby-polyfill`

This is a hybrid package. It dose not import or export anything so both `require`
and `import` works.

This will conditionally polyfill global Object/Map with the missing groupBy
method using `??=` but I would recommend that you conditionally import it if it's
needed. See comp. table at MDN if you need this:

[Object.groupBy](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/groupBy)
[Map.groupBy](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map/groupBy)

Documentation and code example is in this links too.

## Usage

Just need to import it.

```js
import 'groupby-polyfill/lib/polyfill.js'
```
