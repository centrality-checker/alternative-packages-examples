# [`isomorphic-fetch`](https://www.npmjs.com/package/mocha-typescript) -> [`@testdeck/mocha`](https://www.npmjs.com/package/@testdeck/mocha)

The following figure compares the over time centrality ranking of [`mocha-typescript`](https://www.npmjs.com/package/mocha-typescript) and [`@testdeck/mocha`](https://www.npmjs.com/package/@testdeck/mocha).

![the centrality of mocha-typescript and @testdeck/mocha](../figs/mocha-typescript_@testdeck_mocha.png)

## A pull request example

The following is an example of a pull request that perform a dependency migration from [`mocha-typescript`](https://www.npmjs.com/package/mocha-typescript) to [`@testdeck/mocha`](https://www.npmjs.com/package/@testdeck/mocha):

- [allure-framework/allure-js#138](https://github.com/allure-framework/allure-js/pull/138)

## What is package centrality?

By definition, centrality is a measure of the prominence or importance of a node in a social network.
In our context, the centrality allows us to rank the packages based on the popularity/importance of packages that depend on them.
Specifically, we use the PageRank algorithm to evaluate the shift in their centrality over time.
For more details read our research paper: [Towards Using Package Centrality Trend to Identify Packages in Decline](https://arxiv.org/abs/2107.10168).
