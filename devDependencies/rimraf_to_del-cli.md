# [`rimraf`](https://www.npmjs.com/package/rimraf) -> [`del-cli`](https://www.npmjs.com/package/del-cli)

The following figure compares the over time centrality ranking of [`rimraf`](https://www.npmjs.com/package/rimraf) and [`del-cli`](https://www.npmjs.com/package/del-cli).

![the centrality of rimraf and del-cli](../figs/rimraf_del-cli.png)

## A pull request example

The following is an example of a pull request that perform a dependency migration from [`rimraf`](https://www.npmjs.com/package/rimraf) to [`del-cli`](https://www.npmjs.com/package/del-cli):

- [wireapp/wire-web-packages#3271](https://github.com/wireapp/wire-web-packages/pull/3271)

## What is package centrality?

By definition, centrality is a measure of the prominence or importance of a node in a social network.
In our context, the centrality allows us to rank the packages based on the popularity/importance of packages that depend on them.
Specifically, we use the PageRank algorithm to evaluate the shift in their centrality over time.
For more details read our research paper: [Towards Using Package Centrality Trend to Identify Packages in Decline](https://arxiv.org/abs/2107.10168).
