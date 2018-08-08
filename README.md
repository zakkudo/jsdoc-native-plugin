# jsdoc-native-plugin

Adds tags to help document native functionality of javscript/html without having to copy-paste text around.

Install with:

```sh
yarn add --dev @zakkudo/jsdoc-native-plugin
```

Add to your jsdoc config with:

```js
    "plugins": [
        "@zakkudo/jsdoc-native-plugin"
    ],
```

Includes typedefs for

- `Native` namespace
- `Native.DocumentFragment`
- `Native.CustomEvent`
- `Native.Promise`
- ...this will likely grow in the future.  Pull requests welcome!
