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

Please make sure all dependencies are installed ```$ npm install```

### Build

```
$ npm run build
```

### Bump Version

Available importance options
* patch     # makes v0.1.0 → v0.1.1
* feature   # makes v0.1.1 → v0.2.0
* release   # makes v0.2.1 → v1.0.0

```
$ npm run bump-<importance> 
```
