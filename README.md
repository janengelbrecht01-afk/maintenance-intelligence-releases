# Maintenance Intelligence — binary releases

Public Windows installer feed for `electron-updater`.

**This repository contains binaries and update metadata only.**

## Allowed

- `Maintenance Intelligence Setup <version>.exe`
- `.blockmap`
- `latest.yml` / `beta.yml`
- concise release notes

## Forbidden

- Application source code
- AppData / vaults / cookies / SQLite
- SSL.com material or GitHub tokens
- `.env` or credential files

Stable channel uses `latest.yml`. Beta is opt-in via `beta.yml` prereleases.
