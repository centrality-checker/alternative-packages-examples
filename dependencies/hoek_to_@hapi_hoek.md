# [`hoek`](https://www.npmjs.com/package/hoek) -> [`@hapi/hoek`](https://www.npmjs.com/package/@hapi/hoek)

The following figure compares the over time centrality ranking of [`hoek`](https://www.npmjs.com/package/hoek) and [`@hapi/hoek`](https://www.npmjs.com/package/@hapi/hoek).

![the centrality of hoek and @hapi/hoek](../figs/hoek_@hapi_hoek.png)

## A pull request example

The following is an example of a pull request that perform a dependency migration from [`hoek`](https://www.npmjs.com/package/hoek) to [`@hapi/hoek`](https://www.npmjs.com/package/@hapi/hoek):

- [Icehunter/litterbox#9](https://github.com/Icehunter/litterbox/pull/9)

## What is package centrality?

By definition, centrality is a measure of the prominence or importance of a node in a social network.
In our context, the centrality allows us to rank the packages based on the popularity/importance of packages that depend on them.
Specifically, we use the PageRank algorithm to evaluate the shift in their centrality over time.
For more details read our research paper: [Towards Using Package Centrality Trend to Identify Packages in Decline](https://arxiv.org/abs/2107.10168).
