# RayDaw releases

Builds of [RayDaw](https://github.com/ray-language/ray-daw), a DAW written in raylang, for macOS
on Apple silicon: signed with a Developer ID and notarized.

Install the latest one:

```sh
curl -fsSL https://github.com/ray-language/ray-daw-releases/releases/latest/download/install.sh | sh
```

From then on RayDaw updates itself (RayDaw > Check for Updates…). Each release carries the app's
zip, `update.json` (the manifest RayDaw updates from), its Ed25519 signature `update.json.sig`,
and `install.sh`.
