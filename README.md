# SURFACE-Updates

Public update feed for **SURFACE** (ACAS Tools), the visibility tracker for indie brands.

- `latest.json` is the signed update manifest the app reads (Ed25519, key id `acas-surface-v1`).
- Releases hold the installers the manifest points at (`SURFACE_Windows_<v>_Setup.exe`, `SURFACE_Mac_<v>.dmg`) plus `.sha256` files.

Both are published by the SURFACE build pipeline. Nothing here is edited by hand.
Source code lives in the private `SURFACE` repository.

Copyright 2026 ACAS Tools. Installers are for SURFACE testers and customers; not for redistribution.
