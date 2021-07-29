# [`extract-text-webpack-plugin`](https://www.npmjs.com/package/extract-text-webpack-plugin) -> [`mini-css-extract-plugin`](https://www.npmjs.com/package/mini-css-extract-plugin)

The following figure compares the over time centrality ranking of [`extract-text-webpack-plugin`](https://www.npmjs.com/package/extract-text-webpack-plugin) and [`mini-css-extract-plugin`](https://www.npmjs.com/package/mini-css-extract-plugin).

![the centrality of extract-text-webpack-plugin and mini-css-extract-plugin](../figs/extract-text-webpack-plugin_mini-css-extract-plugin.png)

## A pull request example

The following is an example of a pull request that perform a dependency migration from [`extract-text-webpack-plugin`](https://www.npmjs.com/package/extract-text-webpack-plugin) to [`mini-css-extract-plugin`](https://www.npmjs.com/package/mini-css-extract-plugin):

- [ag-grid/ag-grid#2624](https://github.com/ag-grid/ag-grid/pull/2624)

## What is package centrality?

By definition, centrality is a measure of the prominence or importance of a node in a social network.
In our context, the centrality allows us to rank the packages based on the popularity/importance of packages that depend on them.
Specifically, we use the PageRank algorithm to evaluate the shift in their centrality over time.
For more details read our research paper: [Towards Using Package Centrality Trend to Identify Packages in Decline](https://arxiv.org/abs/2107.10168).
