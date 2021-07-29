# [`elasticsearch`](https://www.npmjs.com/package/elasticsearch) -> [`@elastic/elasticsearch`](https://www.npmjs.com/package/@elastic/elasticsearch)

The following figure compares the over time centrality ranking of [`elasticsearch`](https://www.npmjs.com/package/elasticsearch) and [`@elastic/elasticsearch`](https://www.npmjs.com/package/@elastic/elasticsearch).

![the centrality of elasticsearch and @elastic/elasticsearch](../figs/elasticsearch_@elastic_elasticsearch.png)

## A pull request example

The following is an example of a pull request that perform a dependency migration from [`elasticsearch`](https://www.npmjs.com/package/elasticsearch) to [`@elastic/elasticsearch`](https://www.npmjs.com/package/@elastic/elasticsearch):

- [rstiller/inspector-metrics#16](https://github.com/rstiller/inspector-metrics/pull/16)

## What is package centrality?

By definition, centrality is a measure of the prominence or importance of a node in a social network.
In our context, the centrality allows us to rank the packages based on the popularity/importance of packages that depend on them.
Specifically, we use the PageRank algorithm to evaluate the shift in their centrality over time.
For more details read our research paper: [Towards Using Package Centrality Trend to Identify Packages in Decline](https://arxiv.org/abs/2107.10168).
