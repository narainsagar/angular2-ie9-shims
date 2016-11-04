angular2-IE9-shims
==================

Shim(s) / Pollyfill(s) to make angular2 app work on older browsers (IE 9+)

^ It can be used as a temporary workaround for now, until the underlying libraries are fixed to include this polyfill(s).

**Note:** It has been pulled from:

## [`angular@2.1.2`](https://github.com/angular/angular/releases/tag/2.1.2):

raw url: `https://raw.githubusercontent.com/angular/angular/66df335998d097fa8fe46dec41f1183737332021/shims_for_IE.js`

i.e., we have named it as *shims_for_IE@2.1.2.js*

## [`angular@2.0.0-beta.17`](https://github.com/angular/angular/releases/tag/2.0.0-beta.17): 

cdn url: `https://unpkg.com/angular2@2.0.0-beta.17/es6/dev/src/testing/shims_for_IE.js`

i.e., we have named it as *shims_for_IE@2.0.0-beta.17.js*, *shims_for_IE.dev.js* & *shims_for_IE.prod.js*


# Installation

You can install this package with `npm`, `bower` or manually [download as zip](https://github.com/narainsagar/angular2-ie9-shims/archive/master.zip)


## Install via `npm`

```
$ npm install angular2-IE9-shims
```

## Install via `bower`

```
$ bower install angular2-IE9-shims
```


## Usage

Add a `<script>` into to your `.html` file:

**Note:** Always use the latest one.. (i.e., from below *top one* is the latest.)

```html
  <script src="/path/to/angular2-ie9-shims/shims_for_IE@2.1.2.js"></script>
```

```html
  <script src="/path/to/angular2-ie9-shims/shims_for_IE@2.0.0-beta.17.js"></script>
```

OR

```html
  <script src="/path/to/angular2-ie9-shims/shims_for_IE.dev.js"></script>
```

OR

```html
  <script src="/path/to/angular2-ie9-shims/shims_for_IE.prod.js"></script>
```

## License

MIT in [LICENSE](/LICENSE) file.
