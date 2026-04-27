# workshop-takeouts

Public hosting for workshop participant takeout ZIPs.

- Each takeout is published as `docs/<slug>-<date>/<file>.zip`
- Public URL: `https://nichtagentur.github.io/workshop-takeouts/<slug>-<date>/<file>.zip`
- All ZIPs auto-expire **after 7 days** via the daily cleanup workflow
  ([`.github/workflows/cleanup.yml`](.github/workflows/cleanup.yml)).
- ZIPs contain only participant work + recreation guides — **no API keys**
  (every takeout passes a regex secret-leak gate before publish).

This repo is managed by the workshop infra. Don't push directly.
