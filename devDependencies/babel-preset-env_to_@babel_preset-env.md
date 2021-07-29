# [`babel-preset-env`](https://www.npmjs.com/package/babel-preset-env) -> [`@babel/preset-env`](https://www.npmjs.com/package/@babel/preset-env)

The following figure compares the over time centrality ranking of [`babel-preset-env`](https://www.npmjs.com/package/babel-preset-env) and [`@babel/preset-env`](https://www.npmjs.com/package/@babel/preset-env).

![the centrality of babel-preset-env and @babel/preset-env](../figs/babel-preset-env_@babel_preset-env.png)

## A pull request example

The following is an example of a pull request that perform a dependency migration from [`babel-preset-env`](https://www.npmjs.com/package/babel-preset-env) to [`@babel/preset-env`](https://www.npmjs.com/package/@babel/preset-env):

- [jkcfg/jk#211](https://github.com/jkcfg/jk/pull/211)

## What is package centrality?

By definition, centrality is a measure of the prominence or importance of a node in a social network.
In our context, the centrality allows us to rank the packages based on the popularity/importance of packages that depend on them.
Specifically, we use the PageRank algorithm to evaluate the shift in their centrality over time.
For more details read our research paper: [Towards Using Package Centrality Trend to Identify Packages in Decline](https://arxiv.org/abs/2107.10168).
