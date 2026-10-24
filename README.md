# cloud_db_infra-ops-obsv_configs-sync

Data repo (repo as db) of the `configs-sync` engine (service `infra-obs_configs-sync` in cloud-u-containers).

- `containers-declared.json`: the C3 Containers page data (groups, categories, containers, metadata), derived from the `taxonomy` of every service `build.json`.
- `_cloud-data-consolidated.json`, `cloud-fleet-*.json`, `mesh-snapshot.json`, `watchdog.json`, `build/build-*.json`: the consolidated and per-app JSONs of cloud-t-infra `1_cloud-configs`.

Written only by the engine. Do not edit by hand. Served by c3-infra-api and cloud-infra-mcp.
