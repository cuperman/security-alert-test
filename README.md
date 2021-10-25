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

### Two

- runtime dependency:
  - `jquery@3.3.1`
- dev dependency:
  - `lodash@4.17.11`

### Three

- runtime dependency:
  - `immer@7.0.7`
- dev dependency:
  - `object-path@0.11.4`

### Four

- runtime dependency:
  - `highlight.js@9.18.1`
- dev dependency:
  - `netmask@1.0.6`

### Five

- runtime dependency:
  - `axios@0.19.2`
- dev dependency:
  - `elliptic@6.5.2`

### Six

- runtime dependency:
  - `serialize-javascript@1.9.1`
- dev dependency:
  - `moment@2.0.0`
