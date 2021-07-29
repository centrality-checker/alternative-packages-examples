# [`babel-core`](https://www.npmjs.com/package/babel-core) -> [`@babel/core`](https://www.npmjs.com/package/@babel/core)

The following figure compares the over time centrality ranking of [`babel-core`](https://www.npmjs.com/package/babel-core) and [`@babel/core`](https://www.npmjs.com/package/@babel/core).

![the centrality of babel-core and @babel/core](../figs/babel-core_@babel_core.png)

## Pull request examples

The following are examples of pull requests that perform a dependency migration from [`babel-core`](https://www.npmjs.com/package/babel-core) to [`@babel/core`](https://www.npmjs.com/package/@babel/core):

- [babel/minify#804](https://github.com/babel/minify/pull/804)
- [facebook/fbjs#303](https://github.com/facebook/fbjs/pull/303)
- [tuateam/tua-mp#65](https://github.com/tuateam/tua-mp/pull/65)
- [SUI-Components/sui#507](https://github.com/SUI-Components/sui/pull/507)
- [reactway/webpack-builder#3](https://github.com/reactway/webpack-builder/pull/3)

## What is package centrality?

By definition, centrality is a measure of the prominence or importance of a node in a social network.
In our context, the centrality allows us to rank the packages based on the popularity/importance of packages that depend on them.
Specifically, we use the PageRank algorithm to evaluate the shift in their centrality over time.
For more details read our research paper: [Towards Using Package Centrality Trend to Identify Packages in Decline](https://arxiv.org/abs/2107.10168).
