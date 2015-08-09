# AngularJS-TDD-example
Development with AngularJS by Test Driven Development

### Initial
This is a description of https://github.com/wataruoguchi/AngularJS-TDD-example

your-directory
  + index.html


### Build environment

Install packages, selenium server, and web driver

```shell
sudo npm install --save-dev gulp gulp-protractor gulp-webserver run-sequence
sudo node node_modules/gulp-protractor/node_modules/protractor/bin/webdriver-manager update
```

your-directory
  + index.html
  + node_modules

Make your `gulpfile.js`

Note: If you refer my repo, I made `gulpfile.coffee` and it requires `gulpfile.js`.

your-directory
  + index.html
  + node_modules
  + gulpfile.js

Make your test directories

```shell
mkdir test
mkdir test/e2e
mkdir test/e2e/spec
```

Make `config.js` at `e2e`

Make `main.js` at `spec`

your-directory
  + index.html
  + node_modules
  + gulpfile.js
  + test
    + e2e
      + config.js
      + spec
        + main.js

### Test

```shell
gulp test:e2e
```


### Reference(Japanese)

http://qiita.com/yuyaohshimo/items/ce155b92878275056401
