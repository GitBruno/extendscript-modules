# json.cycle

> Extension

Adds `decycle()` and `retrocycle()` to JSON, which make it possible to encode cyclical structures and dags in JSON, and to then recover them.

Source: [JSON-js](https://github.com/douglascrockford/JSON-js/blob/master/cycle.js)

## Test

You can test the code against a range of [targets](https://github.com/nbqx/fakestk/blob/master/resources/versions.json):

    npm run test target-1 target-2

We keep [a log of test results](./test/results_log.md)