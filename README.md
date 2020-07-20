#  Typescript + Karma + Webpack + Coverage :sparkles:

[![CircleCI](https://circleci.com/gh/mcliment/typescript-karma-webpack-coverage-sample.svg?style=svg)](https://circleci.com/gh/mcliment/typescript-karma-webpack-coverage-sample)
![Node.js CI](https://github.com/mcliment/typescript-karma-webpack-coverage-sample/workflows/Node.js%20CI/badge.svg)
[![codecov](https://codecov.io/gh/mcliment/typescript-karma-webpack-coverage-sample/branch/master/graph/badge.svg)](https://codecov.io/gh/mcliment/typescript-karma-webpack-coverage-sample) [![Known Vulnerabilities](https://snyk.io/test/github/mcliment/typescript-karma-webpack-coverage-sample/badge.svg?targetFile=package.json)](https://snyk.io/test/github/mcliment/typescript-karma-webpack-coverage-sample?targetFile=package.json)

The most basic example I can think of a Typescript project with Webpack + Karma + full coverage

## Motivation :muscle:

I tried many routes to make this work properly. Some people have enough with a coverage report from 
the js file generated by webpack but I wanted a better user experience and invested some time finding
a good solution.

In the proposed solution, karma-typescript can be also used instead of going through the webpack route but
in more complex scenarios reusing the main webpack configuration may be very convenient.

## Notable packages :gift:

- [istanbul-instrumenter-loader](https://github.com/webpack-contrib/istanbul-instrumenter-loader) to generate istanbul instrumentation data for coverage
- [karma-coverage-istanbul-reporter](https://github.com/mattlewis92/karma-coverage-istanbul-reporter) to report coverage from istanbul
- [karma-webpack](https://github.com/webpack-contrib/karma-webpack) to preprocess files through Webpack


