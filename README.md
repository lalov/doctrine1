# Doctrine 1 fork

This is a unmaintained Doctrine 1 fork.

The current goal is to make it work with a Symfony 1.4 project, with php 7.1


## Usage

Use the `dev-dev` version string for the latest doctrine1,
and `dev-master` for the backwards-compatible one:

```json
{
  "require": {
    "drak/doctrine1": "dev-dev"
  }
}
```

## List of backwards-incompatible changes on `dev`

* `whereIn` with an empty array now restricts query to returning nothing instead of returning
everything ([issue #15](https://github.com/drak/doctrine1/pull/15))
