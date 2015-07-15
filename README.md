A polyfill for the `input` event in IE 8 and 9. It is based on Ben Alperts "near-perfect oninput shim for IE 8 and 9", but without the jQuery, and it will actual `input` events, not custom equivalents.

As IE 8 and 9 don't allow attaching event handlers to unrecognised event names, this polyfill will requires an Event polyfill. One is available on the [polyfill service](https://cdn.polyfill.io/v1/docs/).
