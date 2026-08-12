# Muse Releases

Public distribution channel for [Muse](https://maxtrigify.github.io/muse-releases/) — a native
macOS spatial canvas for local AI agents.

- **Download:** grab the latest `Muse-<version>.dmg` from
  [Releases](https://github.com/maxtrigify/muse-releases/releases), or use the
  [download page](https://maxtrigify.github.io/muse-releases/).
- **Requirements:** macOS 15 or newer.
- `v1/updates/manifest` is the signed update manifest the app polls; every release entry
  carries the artifact's exact SHA-256 and byte count, signed with the Muse release key.
- `updates.json` / `changelog.json` feed the download page.
- The public site offers the drag-to-Applications DMG; the signed in-app update manifest
  continues to reference the immutable ZIP.

The app source is developed in a private repository; this repo only hosts release artifacts,
release metadata, and the download site.
