# The Pink Pony Project — releases

Downloadable builds of **The Pink Pony Project**, a VFX production tracking and
reporting application by [VFX Tools Ltd](https://vfxtools.co.uk).

This repository carries **only** the built applications and the update feed the
app reads. The source is private.

## Downloads

Get the latest build from the [Releases](../../releases) page:

| File | For |
|---|---|
| `PinkPony_<version>_mac_arm64.zip` | macOS, Apple silicon |
| `PinkPony_<version>_win_x64.zip`   | Windows, 64-bit |

Each release also has a `SHA256SUMS` file. To check a download before opening it:

```
shasum -a 256 -c SHA256SUMS      # macOS
```
```
Get-FileHash .\PinkPony_*.zip -Algorithm SHA256   # Windows, compare by eye
```

**macOS:** the builds are not code-signed, so the first launch may report the app
as damaged. Clear the quarantine flag once and it will open normally:

```
xattr -cr "/Applications/The Pink Pony Project.app"
```

## Updating

The app does not check for updates on its own. Use **Settings → Check for
Updates…** when you want to; it reads `feed.json` from this repository, and can
download and install a newer build for you after confirming.

## feed.json

The update feed. One entry per channel, regenerated automatically when a release
is published:

```json
{
  "stable": {
    "tag": "v1.2.3",
    "version": "1.2.3",
    "released": "2026-01-01",
    "notes_url": "https://github.com/.../releases/tag/v1.2.3",
    "assets": {
      "mac_arm64": { "url": "...", "sha256": "...", "size": 0 },
      "win_x64":   { "url": "...", "sha256": "...", "size": 0 }
    }
  }
}
```

An empty object means no release has been published yet, which the app reads as
"nothing newer available".

## Support

Issues and questions: <https://vfxtools.co.uk>

© VFX Tools Ltd. The application is provided as-is, without warranty of any kind.
See the About tab inside the app for the full notice.
