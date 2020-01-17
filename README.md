# testcafe-reporter-trx

This is the **trx** reporter plugin for [TestCafe](http://devexpress.github.io/testcafe).

This is a folk from keyrun's with attachment

The screenshots path is hardcoded as root/screenshots/In/${Fixture}_${TestName}/screenshot.png

I make this to use with Azure Pipeline's failed test's attachment

## Install

```
npm install testcafe-reporter-trx-attachment
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
