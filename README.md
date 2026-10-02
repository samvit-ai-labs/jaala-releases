# jaala — releases

Binary release artifacts for [jaala](https://jaala.ai) — the desktop app's
update bundles, installers, and headless builds. **Artifacts only; no source.**

- Each release tag carries signed bundles for macOS (Apple Silicon + Intel),
  Windows, and Linux, plus headless `jaala-server`/CLI tarballs.
- The app's built-in updater fetches its manifest from `updates.jaala.ai` and
  downloads the referenced assets from here. Bundles are verified against the
  updater's public key before install — assets on this repo are not the trust
  root.
- Releases are append-only. A pulled release (the rare exception) is always
  superseded by a higher version.

Download the latest version from <https://jaala.ai>. Issues and feedback: see
the links on the website — this repo intentionally has no issue tracker.
