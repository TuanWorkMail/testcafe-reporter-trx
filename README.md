# testcafe-reporter-trx
[![Build Status](https://travis-ci.org/TuanWorkMail/testcafe-reporter-trx.svg)](https://travis-ci.org/TuanWorkMail/testcafe-reporter-trx)

This is the **trx** reporter plugin for [TestCafe](http://devexpress.github.io/testcafe).

## Install

```
npm install testcafe-reporter-trx
```

## Usage

When you run tests from the command line, specify the reporter name by using the `--reporter` option:

```
testcafe chrome 'path/to/test/file.js' --reporter trx
```


When you use API, pass the reporter name to the `reporter()` method:

```js
testCafe
    .createRunner()
    .src('path/to/test/file.js')
    .browsers('chrome')
    .reporter('trx') // <-
    .run();
```
