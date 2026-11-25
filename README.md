# NoScroll — Android APK (unofficial early build)

Early, pre-Play-Store build of NoScroll. No ads, no tracking, no account, no backend.

## Download

Go to **Releases** → latest release → download `NoScroll-v0.1.0-debug.apk`.

## Install (Android 13+)

1. Open the downloaded APK and install it.
2. Open NoScroll → **Status** → it will show the exact steps to enable the accessibility service.
3. On most phones you must first allow one-time restricted settings:
   **Settings → Apps → NoScroll → ⋮ (top right) → Allow restricted settings**
4. Then: **Settings → Accessibility → NoScroll → ON**.

If Play Protect warns about an unknown app: **Play Store → profile icon → Play Protect → Settings → temporarily turn off "Scan apps with Play Protect"**, install, then turn it back on. Android 13+ still requires step 3 regardless of install source.

## What it does

NoScroll hosts Instagram and YouTube (plus Snapchat, Facebook, Pinterest) inside its own WebView and hides the feeds that keep you scrolling. It reads only the foreground app's package name to show a shield when you open a real app; it cannot read app contents or act inside other apps.

## Verify the file

SHA-256 of `NoScroll-v0.1.0-debug.apk`:

```
03d708eb1f1def83c1ac2a24ac1db1c159833d3471235f7d764c0f7b8132bc80
```

## Privacy / License

See [PRIVACY.md](PRIVACY.md). Licensed under AGPL-3.0 — see [LICENSE](LICENSE).
