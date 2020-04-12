# urlqueryobject

A 180 byte (gzip) utility to get the current url query params as object.

## Example

Url: `https://example.com?foo=baz&something=more`

```
import urlqueryobject from 'urlqueryobject';

const params = urlqueryobject();

console.log(params);

{
  foo: 'baz',
  something: 'more',
}

```

# License

[MIT](https://oss.ninja/mit/mjanssen/)
