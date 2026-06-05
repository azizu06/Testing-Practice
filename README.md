# Testing Practice

A small project built to practice **unit testing with Jest**. It pairs a set of plain
JavaScript functions (`functions.js`) with a matching test suite
(`functions.test.js`), bundled with Webpack.

## What it covers

- Writing pure, testable functions and asserting their behavior with Jest.
- Common testing patterns: `expect`, matchers, and edge-case coverage.
- A Babel + Webpack setup so modern JS can be both bundled and tested.

## Tech stack

JavaScript · **Jest** · Babel · **Webpack**

## Getting started

```bash
npm install
npm test             # run the Jest suite
npm run watch        # jest --watch
npm start            # webpack dev server (for the demo page)
npm run build        # production bundle
```

## What I practiced

Test-driven habits: writing **pure functions** that are easy to test, expressing
expected behavior as Jest assertions, and configuring Babel so Jest can run modern
syntax.

> No UI screenshot — this project is about the test suite, not a rendered page.

## License

Odin Project coursework — original implementation by Aziz Umarov.
