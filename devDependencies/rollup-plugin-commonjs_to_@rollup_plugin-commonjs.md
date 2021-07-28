# [`isomorphic-fetch`](https://www.npmjs.com/package/rollup-plugin-commonjs) -> [`@rollup/plugin-commonjs`](https://www.npmjs.com/package/@rollup/plugin-commonjs)

The following figure compares the over time centrality ranking of [`rollup-plugin-commonjs`](https://www.npmjs.com/package/rollup-plugin-commonjs) and [`@rollup/plugin-commonjs`](https://www.npmjs.com/package/@rollup/plugin-commonjs).

![the centrality of rollup-plugin-commonjs and @rollup/plugin-commonjs](../figs/rollup-plugin-commonjs_@rollup_plugin-commonjs.png)

## Pull request examples

The following are examples of pull requests that perform a dependency migration from [`rollup-plugin-commonjs`](https://www.npmjs.com/package/rollup-plugin-commonjs) to [`@rollup/plugin-commonjs`](https://www.npmjs.com/package/@rollup/plugin-commonjs):

- [Azure/azure-sdk-for-js#6876](https://github.com/Azure/azure-sdk-for-js/pull/6876)
- [rollup/plugins#160](https://github.com/rollup/plugins/pull/160)
- [firebase/firebase-js-sdk#3930](https://github.com/firebase/firebase-js-sdk/pull/3930)

## What is package centrality?

By definition, centrality is a measure of the prominence or importance of a node in a social network.
In our context, the centrality allows us to rank the packages based on the popularity/importance of packages that depend on them.
Specifically, we use the PageRank algorithm to evaluate the shift in their centrality over time.
For more details read our research paper: [Towards Using Package Centrality Trend to Identify Packages in Decline](https://arxiv.org/abs/2107.10168).
