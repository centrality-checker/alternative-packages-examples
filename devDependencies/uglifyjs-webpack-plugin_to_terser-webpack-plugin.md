# [`isomorphic-fetch`](https://www.npmjs.com/package/uglifyjs-webpack-plugin) -> [`terser-webpack-plugin`](https://www.npmjs.com/package/terser-webpack-plugin)

The following figure compares the over time centrality ranking of [`uglifyjs-webpack-plugin`](https://www.npmjs.com/package/uglifyjs-webpack-plugin) and [`terser-webpack-plugin`](https://www.npmjs.com/package/terser-webpack-plugin).

![the centrality of uglifyjs-webpack-plugin and terser-webpack-plugin](../figs/uglifyjs-webpack-plugin_terser-webpack-plugin.png)

## Pull request examples

The following are examples of pull requests that perform a dependency migration from [`uglifyjs-webpack-plugin`](https://www.npmjs.com/package/uglifyjs-webpack-plugin) to [`terser-webpack-plugin`](https://www.npmjs.com/package/terser-webpack-plugin):

- [facebook/create-react-app#5026](https://github.com/facebook/create-react-app/pull/5026)
- [wireapp/wire-web-packages#1566](https://github.com/wireapp/wire-web-packages/pull/1566)
- [jupyterlab/jupyterlab#6193](https://github.com/jupyterlab/jupyterlab/pull/6193)
- [readmeio/api-explorer#430](https://github.com/readmeio/api-explorer/pull/430)
- [readmeio/api-explorer#435](https://github.com/readmeio/api-explorer/pull/435)

## What is package centrality?

By definition, centrality is a measure of the prominence or importance of a node in a social network.
In our context, the centrality allows us to rank the packages based on the popularity/importance of packages that depend on them.
Specifically, we use the PageRank algorithm to evaluate the shift in their centrality over time.
For more details read our research paper: [Towards Using Package Centrality Trend to Identify Packages in Decline](https://arxiv.org/abs/2107.10168).
