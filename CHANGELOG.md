# Change log

### vNEXT

### v1.19.0-alpha.1

### v1.18.1

- **action**: show more details after file load failed [PR #223](https://github.com/kamilkisiela/graphql-inspector/pull/223)
- **github**: show more details after file load failed [PR #223](https://github.com/kamilkisiela/graphql-inspector/pull/223)

### v1.18.0

- **github**: load `.yaml` file too [PR #216](https://github.com/kamilkisiela/graphql-inspector/pull/216)

### v1.17.0

- **action**: Update Check Run instead of creating an extra one [PR #177](https://github.com/kamilkisiela/graphql-inspector/pull/177) - thanks to [@BeeeQueue](http://github.com/BeeeQueue)

- **core**: New optional argument or an optional input field is now treated as a dangerous change [PR #147](https://github.com/kamilkisiela/graphql-inspector/pull/147)

### v1.16.0

- **core**: Required field becoming nullable should be a non-breaking change [PR #139](https://github.com/kamilkisiela/graphql-inspector/pull/139) - thanks to [@filipncs](http://github.com/filipncs)

### v1.15.0

- **action**: No double check [PR #111](https://github.com/kamilkisiela/graphql-inspector/pull/111)
- **action**: Way more independent of the github package - uses `actions-toolkit` instead of `probot` [PR #111](https://github.com/kamilkisiela/graphql-inspector/pull/111)
- **github**: Fix location of a targeted entity [PR #104](https://github.com/kamilkisiela/graphql-inspector/pull/104)
- **github**: Support .github/graphql-inspector.yml config [PR #105](https://github.com/kamilkisiela/graphql-inspector/pull/105) [PR #109](https://github.com/kamilkisiela/graphql-inspector/pull/109)

### v1.14.0

- **core**: Fix how GraphQL Schema is fetched [PR #101](https://github.com/kamilkisiela/graphql-inspector/pull/101)
- **core**: Added diff support for arrays and objects (arguments) [PR #95](https://github.com/kamilkisiela/graphql-inspector/pull/95) - thanks to [@mkaradeniz](http://github.com/mkaradeniz)

### v0.13.3

- **load**: `graphql-toolkit` expects options to be a non-null value [PR #92](https://github.com/kamilkisiela/graphql-inspector/pull/92) [Issue #91](https://github.com/kamilkisiela/graphql-inspector/issues/91)

### v0.13.2

- **github**: annotation's `message` was empty [PR #87](https://github.com/kamilkisiela/graphql-inspector/pull/87)

### v0.13.1

- **cli**: bump `apollo-server@2.4.0` [PR #86](https://github.com/kamilkisiela/graphql-inspector/pull/86)

### v0.13.0

- **load**: use The Guild's `graphql-toolkit` [PR #77](https://github.com/kamilkisiela/graphql-inspector/pull/77)
- **cli**: pass `--token` to introspection [PR #77](https://github.com/kamilkisiela/graphql-inspector/pull/77)
- **cli**: pass `--token` to introspection command [PR #77](https://github.com/kamilkisiela/graphql-inspector/pull/77)

### v0.12.0

- Move `graphql` to peer dependencies [PR #70](https://github.com/kamilkisiela/graphql-inspector/pull/70)

### v0.11.0

- **cli**: Make `--require` accept multiple values `--require a --require b` [PR #67](https://github.com/kamilkisiela/graphql-inspector/pull/67)
- **cli**: Fix `--require` not loading modules [PR #67](https://github.com/kamilkisiela/graphql-inspector/pull/67)
- **github**: Use message as a title and reason as a message [PR #67](https://github.com/kamilkisiela/graphql-inspector/pull/67)

### v0.10.0

- **github**: Uses path as a title and includes a reason [PR #65](https://github.com/kamilkisiela/graphql-inspector/pull/65)

### v0.9.0

Initial release. We didn't track changes before this version.
