# Scoop bucket for DesktopTools

Scoop bucket for [DesktopTools](https://github.com/vg2222/DesktopTools), a local-first Windows 11 app for screenshots, screen recording, annotation and presentation tools. It installs the portable ZIP from the project's GitHub releases.

```powershell
scoop bucket add desktoptools https://github.com/vg2222/scoop-desktoptools
scoop install desktoptools
```

The app is not code-signed, so Windows SmartScreen may ask for confirmation on first start. The manifest hash comes from the release's `SHA256SUMS.txt`. The manifest source of truth lives in the DesktopTools repository under `packaging/scoop/`; this bucket is a copy of it.
