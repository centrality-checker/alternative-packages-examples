# [`isomorphic-fetch`](https://www.npmjs.com/package/request) -> [`node-fetch`](https://www.npmjs.com/package/node-fetch)

The following figure compares the over time centrality ranking of [`request`](https://www.npmjs.com/package/request) and [`node-fetch`](https://www.npmjs.com/package/node-fetch).

![the centrality of request and node-fetch](../figs/request_node-fetch.png)

## A pull request example

The following is an example of a pull request that perform a dependency migration from [`request`](https://www.npmjs.com/package/request) to [`node-fetch`](https://www.npmjs.com/package/node-fetch):

- [okta/okta-oidc-js#678](https://github.com/okta/okta-oidc-js/pull/678)

## What is package centrality?

By definition, centrality is a measure of the prominence or importance of a node in a social network.
In our context, the centrality allows us to rank the packages based on the popularity/importance of packages that depend on them.
Specifically, we use the PageRank algorithm to evaluate the shift in their centrality over time.
For more details read our research paper: [Towards Using Package Centrality Trend to Identify Packages in Decline](https://arxiv.org/abs/2107.10168).
