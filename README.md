# Dosling releases

Public downloads for [Dosling](https://dosling.com), a friendly DOS game
emulator for the browser, Mac, iPhone and iPad. This repository holds release
files only; Dosling's source code is not published here.

## Available now

| Release | What it is |
|---|---|
| [Dosling Web 0.1.0](https://github.com/pbalogh77/dosling-releases/releases/tag/web-v0.1.0) | Preview of the WebAssembly player. Play it at https://dosling.com/play/ or self-host the static folder. |

The Mac and iOS apps are in development and are not publicly released yet.

## What's included

- MS-DOS 4.0, built from Microsoft's open-source, MIT-licensed release.
- No games. Import games you have the right to use. Freeware and shareware
  labels don't automatically allow redistribution.

## Third-party licences

Each release includes `THIRD_PARTY_NOTICES.txt` and the full licence texts.
Nuked OPL3 is LGPL-2.1-or-later. Every web release ships a relink kit with the
Dosling object files, a link script and the complete library source, so you can
relink a modified copy.

## Verifying downloads

Each release lists SHA-256 checksums in `SHA256SUMS.txt`:

```
shasum -a 256 -c SHA256SUMS.txt
```
