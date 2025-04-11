# dependabot does not update pnpm-workspace.yaml's catalog

dependabot does not update pnpm-workspace.yaml's catalog

```yaml
catalog:
  lodash: 4.0.0
```

https://github.com/azu/pnpm-catalog-with-dependabot/pull/1 does not update the catalog, but it update pnpm-lock.yaml

This behavior cause another issue 

- https://github.com/pnpm/pnpm/issues/9369