# [`isomorphic-fetch`](https://www.npmjs.com/package/underscore) -> [`lodash`](https://www.npmjs.com/package/lodash)

The following figure compares the over time centrality ranking of [`underscore`](https://www.npmjs.com/package/underscore) and [`lodash`](https://www.npmjs.com/package/lodash).

![the centrality of underscore and lodash](../figs/underscore_lodash.png)

## A pull request example

The following is an example of a pull request that perform a dependency migration from [`underscore`](https://www.npmjs.com/package/underscore) to [`lodash`](https://www.npmjs.com/package/lodash):

- [jpmorganchase/perspective#427](https://github.com/jpmorganchase/perspective/pull/427)

## What is package centrality?

By definition, centrality is a measure of the prominence or importance of a node in a social network.
In our context, the centrality allows us to rank the packages based on the popularity/importance of packages that depend on them.
Specifically, we use the PageRank algorithm to evaluate the shift in their centrality over time.
For more details read our research paper: [Towards Using Package Centrality Trend to Identify Packages in Decline](https://arxiv.org/abs/2107.10168).
