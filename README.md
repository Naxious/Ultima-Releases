# Ultima release channel

This public repository hosts distributable Ultima launcher updates and Windows installer releases.

- `channels/staging/release.json` is the current signed staging pointer.
- `releases/<release-id>/` contains immutable, hash-addressed ClassicUO runtime files.
- `release-<release-id>` tags pin the exact bytes referenced by each manifest.
- GitHub Releases contains the one-click Windows installer.

The update manifest is signed. Do not edit a published manifest or release payload in place; publish a new release ID instead.

The UONax installer includes authorized Ultima Online Classic game data, and the signed UO-data catalog allows the launcher to verify and repair that managed installation automatically. The Enhanced Client is not included.
