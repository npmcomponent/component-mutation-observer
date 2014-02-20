*This repository is a mirror of the [component](http://component.io) module [component/mutation-observer](http://github.com/component/mutation-observer). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-mutation-observer`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# mutation-observer

  Exposes the `MutationObserver` constructor without testing for prefixes.

## Installation

```
$ component install component/matches-selector
```

## API

```js
require('mutation-observer')
```

will return one of the following:

```
MutationObserver
WebKitMutationObserver
MozMutationObserver
```

## License

  MIT
