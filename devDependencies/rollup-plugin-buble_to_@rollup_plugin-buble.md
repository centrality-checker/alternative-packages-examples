# [`rollup-plugin-buble`](https://www.npmjs.com/package/rollup-plugin-buble) -> [`@rollup/plugin-buble`](https://www.npmjs.com/package/@rollup/plugin-buble)

The following figure compares the over time centrality ranking of [`rollup-plugin-buble`](https://www.npmjs.com/package/rollup-plugin-buble) and [`@rollup/plugin-buble`](https://www.npmjs.com/package/@rollup/plugin-buble).

![the centrality of rollup-plugin-buble and @rollup/plugin-buble](../figs/rollup-plugin-buble_@rollup_plugin-buble.png)

## A pull request example

The following is an example of a pull request that perform a dependency migration from [`rollup-plugin-buble`](https://www.npmjs.com/package/rollup-plugin-buble) to [`@rollup/plugin-buble`](https://www.npmjs.com/package/@rollup/plugin-buble):

- [rollup/plugins#160](https://github.com/rollup/plugins/pull/160)

## What is package centrality?

By definition, centrality is a measure of the prominence or importance of a node in a social network.
In our context, the centrality allows us to rank the packages based on the popularity/importance of packages that depend on them.
Specifically, we use the PageRank algorithm to evaluate the shift in their centrality over time.
For more details read our research paper: [Towards Using Package Centrality Trend to Identify Packages in Decline](https://arxiv.org/abs/2107.10168).
