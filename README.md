# VibePOS Releases

This public repository contains official VibePOS installer artifacts and update metadata. Application source code is maintained separately.

Releases are published automatically by the private VibePOS build workflow after a version tag is pushed. Installed copies check the `latest.json` asset attached to the newest release and never require a GitHub credential.

Each Windows release includes:

- the VibePOS NSIS installer;
- `latest.json` for the in-app update checker;
- `SHA256SUMS.txt` and `build-manifest.json` for verification; and
- `python-packages.txt` for build traceability.

No customer databases, credentials, license caches, backups, or runtime data belong in this repository.
