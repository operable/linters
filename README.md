# linters
Styleguide repository for Operable projects

This repository stores configuration files for any linters and static
code analysis tools used on Operable projects. Specifically it allows
us to centralize such configuration for use with the
[Ebert](https://ebertapp.io/) analysis service.

All Cog-related Ebert analyses can be found at
[https://ebertapp.io/github/operable/](https://ebertapp.io/github/operable/)

## Usage

In a repository's `.ebert.yml` configuration file, ensure that the
following is in place:

```yaml
styleguide: operable/linters
```

See the [Ebert configuration
documentation](https://ebertapp.io/docs/config) for more details.
