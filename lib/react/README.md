# GitHub Octicons React Component

[![npm version](https://img.shields.io/npm/v/%40primer%2Freact-octicons.svg)](https://www.npmjs.org/package/%40primer%2Freact-octicons)
[![Build Status](https://travis-ci.org/primer/octicons.svg?branch=master)](https://travis-ci.org/primer/octicons)

> A react component for installing octicons

## Install

```
$ npm install @primer/react-octicons --save
```

## Usage

The entire library will be available when importing `@primer/react-octicons`. Specifying the [icon you want to use][octicons], by supplying the `name=""` to the component.

```js
// Example usage
import Octicon from "@primer/react-octicons"

const AlertIcon = <Octicon name="alert" />
```

##### ariaLabel

You have the option to add accessibility information to the icon using `aria-label`.

```js
// Example usage
import Octicon from "@primer/react-octicons"

const PlusIcon = <Octicon name="plus" ariaLabel="Add new item" />
```


##### width & height

You can change the dimensions of the icon by setting `width` and/or `height`. We recommended you supply **only the `height`**, because this will then calculate the appropriate width based on the viewBox size.

```js
// Example usage
import Octicon from "@primer/react-octicons"

const BiggestLogo = <Octicon name="logo-github" height="500" />
```

## License

(c) GitHub, Inc.

When using the GitHub logos, be sure to follow the [GitHub logo guidelines](https://github.com/logos).

[MIT](./LICENSE)  

[octicons]: https://octicons.github.com/
[primer]: https://github.com/primer/primer
[docs]: http://primercss.io/
[npm]: https://www.npmjs.com/
[install-npm]: https://docs.npmjs.com/getting-started/installing-node