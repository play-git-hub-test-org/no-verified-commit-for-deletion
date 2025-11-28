Surprisingly, it looks like deletions (unlike additions) are not signed when performed using the GitHub REST API:

https://github.com/orgs/community/discussions/180621

Alternative approaches:

* Crafting individual Git trees/blobs/commits: https://github.com/orgs/community/discussions/50055
* GraphQL: https://github.blog/changelog/2021-09-13-a-simpler-api-for-authoring-commits/
  * https://docs.github.com/en/graphql/reference/input-objects#filechanges
