# Herva Suwayomi Extensions

Custom extension repository for Singgih's Suwayomi deployment.

## Add to Suwayomi

Use this Suwayomi extension repo URL:

```text
https://github.com/singgihanggana/suwayomi-comix-extension-repo/tree/repo2
```

Raw index URL, if needed:

```text
https://raw.githubusercontent.com/singgihanggana/suwayomi-comix-extension-repo/repo2/index.min.json
```

## Extensions

- Comix (`eu.kanade.tachiyomi.extension.en.comix`) sidecar-patched for Suwayomi server.

The patched Comix extension delegates browser-only payload capture to `comix-browser-sidecar` at `http://comix-browser-sidecar:8193/capture` and image fetching to `/image`.

## Versioning

Current Comix package:

```text
pkg: eu.kanade.tachiyomi.extension.en.comix
versionCode: 32
versionName: 1.4.32
apk: tachiyomi-en.comix-v1.4.32.apk
```

Suwayomi's extension parser expects numeric-style versions; avoid suffixes such as `-herva.1` in `index.min.json`.
