# ATF test catalog

Available PZ mod tests published by developers using ATF Workbench.

The catalog is `catalog/v1/index.json`. Packages live in GitHub Releases, separate from this small repository. Each publisher/project/channel points to one exact release revision.

Testers use ATF Test Connect with a compatible Storm build, or import a release in Workbench. After preparing the same revision, host or join through PZ's Steam co-op.

## Publishing

Use Workbench's **Publish exported test** with this repository as the destination. It creates a release and a catalog pull request. Maintainers check publisher ownership and merge approved entries. Never upload credentials, worlds, databases or personal configuration.

This catalog lists test builds. It is not a live server list or a network relay.
