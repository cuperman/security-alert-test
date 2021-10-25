# Securety Alert Test

Testing Github security alerts capabilities and configuration

## Open questions

- How many packages does Github support?
- If more packages exist than are supported, can we specify which to scan?
- Can we differentiate runtime dependencies from dev dependencies?

## Packages

Creating mono-repo with many packages, each runtime and dev dependencies that have security vulnerabilities.

### One

- runtime dependency:
  - `handlebars@2.0.0`
- dev dependency:
  - `tar@6.1.0`
