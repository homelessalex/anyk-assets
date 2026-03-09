# anyk-assets

Published Anyk style and camera-profile assets.

## Layout

- `manifest.json` — export manifest with normalized metadata and hashes
- `styles/*.json` — cloud-safe styles, no thumbnails
- `profiles/*.json` — split camera profiles
- `profiles/profile_defaults.json` — camera-to-default-profile mapping

## Notes

- Thumbnails are intentionally excluded from this repo. They remain local-only in PureRaw.
- The repo is meant to be written by PureRaw publish tooling and read by Anyk Raw sync tooling.
- The format is file-based on purpose so it can be migrated later to a database-backed service without changing asset JSON payloads.
