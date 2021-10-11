---
title: "Upgrading to 1.0.0"

---

### Resources

- [Discourse]()
- [Release notes](https://github.com/dbt-labs/dbt/releases/tag/v1.0.0)
- [Full changelog](https://github.com/dbt-labs/dbt/blob/1.0.0/CHANGELOG.md)

## Breaking changes
- Do I need to mention enacted deprecations?


## New and changed documentation

### Tasks


## Selection


### Elsewhere in Core
- [model-paths](model-paths) have replaced `source-paths` in `dbt-project.yml.
- [seed-paths](seed-paths) have replaced `data-paths` in `dbt-project.yml with a default value of `seeds`.
- The default value of [test-paths](test-paths) has been updated to be the plural `tests`.
- The default value of [analysis-paths](analysis-paths) has been updated to be the plural `analyses`.
- The [packages-install-path](packages-install-path) was updated from `modules-path` with a default value of `dbt-packages` instead of `dbt-modules`.

### Plugins
