# AngBull

[![npm](https://img.shields.io/npm/v/angbull.svg)]()
[![npm](https://img.shields.io/npm/dt/angbull.svg)]()
[![npm](https://img.shields.io/npm/l/angbull.svg)]()

AngBull is a lightweight library of responsive UI components for [Angular](https://angular.io/) based on [Bulma](http://bulma.io/) css framework.

## Features

* very lightweight with none internal dependencies aside from Bulma
* very small size About 60KB min+gzip (with Bulma included)
* Semantic code output
* Follows flexbox design 
* Focus on usability and performance without *over-animations*

## Documentation
documentation will be released soon...

## Quick start

You need to create a project using [angular-cli](https://cli.angular.io/).

![angular-cli](https://cli.angular.io/images/cli-logo.svg)

this will install latest version of angular and install all dependencies.

### 1- Installation 

now install angbull via npm or yarn 
####via npm

```bash
npm install angbull --save
```
####via yarn
 
```bash
yarn add angbull
```

### 2 Import and use AngBull

```javascript
import Vue from 'vue';
import Buefy from 'buefy';
import 'buefy/lib/buefy.css';

Vue.use(Buefy);

// OR

Vue.component(Buefy.Checkbox.name, Buefy.Checkbox);
Vue.component(Buefy.Table.name, Buefy.Table);
Vue.component(Buefy.Switch.name, Buefy.Switch);
```

### 3 Include Material Design Icons

```html
<link rel="stylesheet" href="//cdn.materialdesignicons.com/2.0.46/css/materialdesignicons.min.css">
```

If you want to customize the icons or the theme, refer to the [customization section on the documentation](https://buefy.github.io/#/documentation/customization).

### Alternatively, you can use a CDN or even download

```html
<!-- Buefy CSS -->
<link rel="stylesheet" href="https://unpkg.com/buefy/lib/buefy.min.css">

<!-- Buefy JavaScript -->
<script src="https://unpkg.com/buefy"></script>
```

```javascript
// Global variable
Vue.use(Buefy.default)
```

## Browser support

Recent versions of Firefox, Chrome, Edge, Opera and Safari. IE10+ is only partially supported.

## Versioning

While it's still in beta, version will follow **v0.Y.Z**, where:

* **Y**: Major (breaking changes)
* **Z**: Minor or patch

## Stay in touch

* [Twitter](https://twitter.com/rafaelpimpa)

## Collaborators

* Walter Tommasi — [@jtommy](https://github.com/jtommy)

## License

Code released under [MIT]((https://github.com/rafaelpimpa/buefy/blob/master/LICENSE)) license.

Copyright (c) 2017, Rafael Beraldo.
