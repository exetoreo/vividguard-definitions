# VividGuard definitions

Signed malware definition updates for **VividGuard** by Vivid Software.

- `latest.json` describes the current package (version, file, size, SHA-256).
- `latest.json.sig` is an ECDSA P-256 signature of `latest.json`. VividGuard only installs packages whose feed verifies against the public key built into the app, then checks the package's SHA-256 and every file listed in its `manifest.json`.
- `vividguard-defs-*.zip` contains known-malware SHA-256 hashes (MalwareBazaar, abuse.ch) and YARA rules (VividGuard's own and ReversingLabs, MIT licensed). See `manifest.json` inside each package for sources and licenses.

This repository contains no executable code.
