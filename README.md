# Ultima release channel

This public repository hosts distributable Ultima launcher updates and Windows installer releases.

- `channels/staging/release.json` is the current signed staging pointer.
- `releases/<release-id>/` contains immutable, hash-addressed ClassicUO runtime files.
- `release-<release-id>` tags pin the exact bytes referenced by each manifest.
- GitHub Releases contains the one-click Windows installer.

The update manifest is signed. Do not edit a published manifest or release payload in place; publish a new release ID instead.

Electronic Arts/Broadsword Ultima Online game data is not included. Players select an existing legal Ultima Online installation when first launching the game.
