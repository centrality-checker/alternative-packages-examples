# [`isomorphic-fetch`](https://www.npmjs.com/package/opn) -> [`open`](https://www.npmjs.com/package/open)

The following figure compares the over time centrality ranking of [`opn`](https://www.npmjs.com/package/opn) and [`open`](https://www.npmjs.com/package/open).

![the centrality of opn and open](../figs/opn_open.png)

## Pull request examples

The following are examples of pull requests that perform a dependency migration from [`opn`](https://www.npmjs.com/package/opn) to [`open`](https://www.npmjs.com/package/open):

- [appcelerator/amplify-tooling#59](https://github.com/appcelerator/amplify-tooling/pull/59)
- [angular/angular-cli#14042](https://github.com/angular/angular-cli/pull/14042)
- [facebook/create-react-app#7058](https://github.com/facebook/create-react-app/pull/7058)
- [ionic-team/capacitor#1411](https://github.com/ionic-team/capacitor/pull/1411)
- [IBM/kui#1140](https://github.com/IBM/kui/pull/1140)

## What is package centrality?

By definition, centrality is a measure of the prominence or importance of a node in a social network.
In our context, the centrality allows us to rank the packages based on the popularity/importance of packages that depend on them.
Specifically, we use the PageRank algorithm to evaluate the shift in their centrality over time.
For more details read our research paper: [Towards Using Package Centrality Trend to Identify Packages in Decline](https://arxiv.org/abs/2107.10168).
