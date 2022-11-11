# Renovate integration

Repositories under the [`slavcodev/`](https://github.com/slavcodev/) scope receive regular dependency
upgrades through [renovate](https://github.com/renovatebot/renovate/).

The configuration is defined in [`renovate-config.json`](./renovate-config.json), and imported in all applicable
repositories.

Dependency ranges are kept restrictively recent as per my [Versioning policy and support](./versioning.md).

To use this configuration, create a [`renovate.json`](./renovate.json) file in the repository where it should be active:

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": [
    "local>slavcodev/.github:renovate-config"
  ]
}
```

Please note that this file will change according to **MY OWN** needs: no BC guaranteed.
