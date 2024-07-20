# cloud-init configs

Collection of cloud-init user configs.

You should combine `base.yml` with the more-specific configs (e.g., droplets
should get `base.yml` and `digitalocean.yml`).

## Linting

```bash
pre-commit run --all-files
```
