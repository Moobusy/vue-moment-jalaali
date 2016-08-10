# vue-moment-jalaali

Jalaali [Moment.js](http://www.momentjs.com) filters for your [Vue.js](http://vuejs.org/) project. This project is based on [vue-moment] (https://github.com/brockpetrie/vue-moment) and [moment-jalaali] (https://github.com/jalaali/moment-jalaali)

## Installation

Either install via NPM and require plugin like so  

```js
Vue.use(require('vue-moment-jalaali'));
```

or load `vue-moment-jalaali.min.js` along with `moment-jalaali.js` the old fashioned way.

## Usage

Simply set `moment` as the filtering function and you're good to go. At least one argument is expected, which the filter assumes to be a `format` string if the argument doesn't match any of the other filtering methods.

```html
<span>{{ someDate | moment "jYYYY/jM/jD HH:mm" }}</span>
<!-- or create a new date from 'now' -->
<span>{{ new Date() | moment "jYYYY/jM/jD HH:mm" }}</span>
```
