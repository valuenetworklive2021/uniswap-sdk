# Valueswap SDK
[![npm version](https://img.shields.io/npm/v/@valueswap/sdk/latest.svg)](https://www.npmjs.com/package/@valueswap/sdk/v/latest)
[![npm bundle size (scoped version)](https://img.shields.io/bundlephobia/minzip/@valueswap/sdk/latest.svg)](https://bundlephobia.com/result?p=@valueswap/sdk@latest)

In-depth documentation on this SDK is available at [valuenetworklive2021.github.io/valueswap-protocol](https://valuenetworklive2021.github.io/valueswap-protocol/docs/v2/SDK/getting-started/).


## Running tests
To run the tests, follow these steps. You must have at least node v10 and [yarn](https://yarnpkg.com/) installed.

First clone the repository:
```sh
git clone https://github.com/valuenetworklive2021/valueswap-sdk.git
```

Move into the valueswap-sdk working directory
```sh
cd valueswap-sdk/
```

Install dependencies
```sh
yarn install
```

Run tests
```sh
yarn test
```

You should see output like the following:
```sh
yarn run v1.22.4
$ tsdx test
 PASS  test/constants.test.ts
 PASS  test/pair.test.ts
 PASS  test/fraction.test.ts
 PASS  test/miscellaneous.test.ts
 PASS  test/entities.test.ts
 PASS  test/trade.test.ts

Test Suites: 1 skipped, 6 passed, 6 of 7 total
Tests:       3 skipped, 82 passed, 85 total
Snapshots:   0 total
Time:        5.091s
Ran all test suites.
✨  Done in 6.61s.
```
