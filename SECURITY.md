# Security Policy

## Reporting a vulnerability

If you believe you've found a security problem in The Pink Pony Project — for
example something that could expose ShotGrid credentials or production data —
please report it privately rather than opening a public issue.

**Contact:** via [vfxtools.co.uk](https://vfxtools.co.uk).

Please include:

- what you found and where,
- the version you were running (shown on the app's **About** tab), and
- steps to reproduce it, if you have them.

We'll acknowledge your report and keep you updated as we look into it.

## What's in a build

The published builds are compiled applications only. They contain **no
credentials and no production data** — your ShotGrid login and local cache live
in `~/.shotgrid_sync_tool/` on your own machine and are never bundled or
transmitted anywhere except to your own ShotGrid site.

## Verifying a download

Every release ships a `SHA256SUMS` file so you can confirm a download is intact
before running it. See *Verifying your download* in the
[README](README.md#verifying-your-download).

## Supported versions

Only the **latest** published release is supported. If you're on an older build,
update via **Settings → Check for Updates…** before reporting an issue.
