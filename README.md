# scala-steward

Scala steward configuration to keep our scala apps up to date.

This runs a github-action on a schedule and will raise PRs against repositories that the [Wellcome Collection Scala Steward](https://github.com/organizations/wellcomecollection/settings/apps/wellcome-collection-scala-steward) GitHub app has permissions to read from.

If you want to run this action against a non-default branch you can specify them in [REPOSITORIES.md](./REPOSITORIES.md).

_With appreciation for https://github.com/guardian/scala-steward-public-repos, from which this is copied._