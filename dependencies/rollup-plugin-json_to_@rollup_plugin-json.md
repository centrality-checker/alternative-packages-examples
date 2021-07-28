# [`isomorphic-fetch`](https://www.npmjs.com/package/rollup-plugin-json) -> [`@rollup/plugin-json`](https://www.npmjs.com/package/@rollup/plugin-json)

The following figure compares the over time centrality ranking of [`rollup-plugin-json`](https://www.npmjs.com/package/rollup-plugin-json) and [`@rollup/plugin-json`](https://www.npmjs.com/package/@rollup/plugin-json).

![the centrality of rollup-plugin-json and @rollup/plugin-json](../figs/rollup-plugin-json_@rollup_plugin-json.png)

## A pull request example

The following is an example of a pull request that perform a dependency migration from [`rollup-plugin-json`](https://www.npmjs.com/package/rollup-plugin-json) to [`@rollup/plugin-json`](https://www.npmjs.com/package/@rollup/plugin-json):

- [remaxjs/remax#376](https://github.com/remaxjs/remax/pull/376)

## What is package centrality?

By definition, centrality is a measure of the prominence or importance of a node in a social network.
In our context, the centrality allows us to rank the packages based on the popularity/importance of packages that depend on them.
Specifically, we use the PageRank algorithm to evaluate the shift in their centrality over time.
For more details read our research paper: [Towards Using Package Centrality Trend to Identify Packages in Decline](https://arxiv.org/abs/2107.10168).
