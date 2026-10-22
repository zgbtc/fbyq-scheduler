# Free scheduler for the private FBYQ publishing service

This repository contains only the GitHub Actions scheduler. The publishing app remains private at `zgbtc/fbyq`.

Required Actions secrets (never store token values in files):
- `FBYQ_BASE_URL`: `https://fbyq.vercel.app`
- `FBYQ_TRIGGER_TOKEN`: Vercel `TRIGGER_TOKEN`

Scheduled triggers will be enabled after credentials are configured.
