# jaala — releases

Binary release artifacts for [jaala](https://jaala.ai) — the desktop app's
update bundles and installers. **Artifacts only; no source.**

- Each release tag carries desktop bundles for macOS (Apple Silicon), Windows
  (x86_64) and Linux (x86_64). The bundles the updater installs
  (`.app.tar.gz`, `.msi`, `.exe`, `.AppImage`) carry a detached `.sig` beside
  them; the `.dmg`, `.deb` and `.rpm` are plain downloads.
- The app's built-in updater fetches its manifest from `updates.jaala.ai` and
  downloads the referenced assets from here. Bundles are verified against the
  updater's public key before install — assets on this repo are not the trust
  root.
- Published artifacts are retained, so a download URL stays live for anyone
  still on an older version. Removing a release or a tag is a deliberate act
  by the owner, not something the release process does.

Download the latest version from <https://jaala.ai>. Issues and feedback: see
the links on the website — this repo intentionally has no issue tracker.
