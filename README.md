# react-native-ssb-shims

Node.js-related shims necessary for the SSB ecosystem to run on React Native apps.

## usage

First install it as a dependency in your project

```
npm install --save react-native-ssb-shims
```

Then "link" some dependencies (important!):

```
react-native link react-native-os
```

And import it in your project's index.js:

```js
require('react-native-ssb-shims');
```

### Note

Mac users: in order to get the post-install scripts to run, you will first need to install `coreutils` through homebrew

```brew install coreutils```

