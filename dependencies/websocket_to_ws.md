# [`isomorphic-fetch`](https://www.npmjs.com/package/websocket) -> [`ws`](https://www.npmjs.com/package/ws)

The following figure compares the over time centrality ranking of [`websocket`](https://www.npmjs.com/package/websocket) and [`ws`](https://www.npmjs.com/package/ws).

![the centrality of websocket and ws](../figs/websocket_ws.png)

## A pull request example

The following is an example of a pull request that perform a dependency migration from [`websocket`](https://www.npmjs.com/package/websocket) to [`ws`](https://www.npmjs.com/package/ws):

- [gsi-upm/Maia#7](https://github.com/gsi-upm/Maia/pull/7)

## What is package centrality?

By definition, centrality is a measure of the prominence or importance of a node in a social network.
In our context, the centrality allows us to rank the packages based on the popularity/importance of packages that depend on them.
Specifically, we use the PageRank algorithm to evaluate the shift in their centrality over time.
For more details read our research paper: [Towards Using Package Centrality Trend to Identify Packages in Decline](https://arxiv.org/abs/2107.10168).
