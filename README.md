# Herva Suwayomi Extensions

Custom extension repository for Singgih's Suwayomi deployment.

## Add to Suwayomi

Use this repo URL:

```text
https://raw.githubusercontent.com/singgihanggana/suwayomi-comix-extension-repo/repo/index.min.json
```

## Extensions

- Comix (`eu.kanade.tachiyomi.extension.en.comix`) sidecar-patched for Suwayomi server.

The patched Comix extension delegates browser-only payload capture to `comix-browser-sidecar` at `http://comix-browser-sidecar:8193/capture` and image fetching to `/image`.
