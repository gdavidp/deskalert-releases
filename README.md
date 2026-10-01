# Desk Alert releases

Signed Windows builds of Desk Alert 2.0, the EGW2 911 notification client. This repository holds binaries only — no source.

Each release carries `DeskAlert-<version>.exe`, its `.sha256`, and `manifest.json` with an Ed25519 signature (`manifest.json.sig`). Desk Alert checks the latest release, verifies the signature against the key built into the client, and offers the update from its tray menu ("Check for updates").

Builds are unsigned for Authenticode during the pilot; Windows SmartScreen will warn on first run (More info → Run anyway).
