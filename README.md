# Angular Marquee

Scrolls html element contents with custom speed. Slows down on hover. 
Demo https://vepasto.github.io/angular-marquee/

## Usage 

1. Include script
  ```html
  <script src="angular-marquee.js">
  ```

2. Inject angularMarquee module as a dependency into your app
  ```js
  var app = angular.module('myApp', ['angularMarquee']);
  ```

3. Use the directive with any element
  * default
  ```html
  <div angular-marquee>Hello World!</div>
  ```
  * custom speed
  ```html
  <div angular-marquee speed="marqueSpeed" speed-hover="marqueSpeedHover">Hello World!</div>
  ```

4. Get a cup of coffee and enjoy!

## Contributing

### Build

```
$ npm install
$ npm run build
```
