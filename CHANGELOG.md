# 1.0.0-beta.4

## New Features

- Adding ability to specify your own instance of an `apiCheck` which allows you to use your own checkers.

## Bug Fixes

- Fixing the prefix for the `scopeTypes` instance of an `apiCheck` to be `angular-scope-types` rather than `api-check-angular`

# 1.0.0-beta.3

## Bug Fixes

- Fixing issue where a new instance of the controller was created and the properties were not bound to that instance.

# 1.0.0-beta.2

## Other

- Adding `.npmignore`

# 1.0.0-beta.1

## Breaking changes

- `scopeTypes` must be a function that accepts the api-check instance and returns the api (perf improvement)
- Changing what is exported to be the `scopeTypesFactory` function.

## New Features

- Adding `disabled` option.
- Improved the API, adding more tests, adding example.

# 1.0.0-beta.0

- Initial release
