# [`isomorphic-fetch`](https://www.npmjs.com/package/highlight.js) -> [`prismjs`](https://www.npmjs.com/package/prismjs)

The following figure compares the over time centrality ranking of [`highlight.js`](https://www.npmjs.com/package/highlight.js) and [`prismjs`](https://www.npmjs.com/package/prismjs).

![the centrality of highlight.js and prismjs](../figs/highlight.js_prismjs.png)

## A pull request example

The following is an example of a pull request that perform a dependency migration from [`highlight.js`](https://www.npmjs.com/package/highlight.js) to [`prismjs`](https://www.npmjs.com/package/prismjs):

- [raxjs/rax-scripts#289](https://github.com/raxjs/rax-scripts/pull/289)

## What is package centrality?

By definition, centrality is a measure of the prominence or importance of a node in a social network.
In our context, the centrality allows us to rank the packages based on the popularity/importance of packages that depend on them.
Specifically, we use the PageRank algorithm to evaluate the shift in their centrality over time.
For more details read our research paper: [Towards Using Package Centrality Trend to Identify Packages in Decline](https://arxiv.org/abs/2107.10168).
