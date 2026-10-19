# Child Safety app update feed

Public, token-free update feed for the Child Safety apps (source repos are private).

- `version.json` - latest version, notes and APK download URL per app (`parent`, `client`).
- APKs are attached to this repo's public releases (`parent-v*`, `client-v*`).

Update flow when shipping a Child Safety release: build in the private repo as usual, then attach the APK to a release here and bump `version.json`.
