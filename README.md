# liblzma-dev

liblzma 5.8.4 headers and static library (the xz compression library) for building programs with gcc

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install liblzma-dev
```

| | |
|---|---|
| Version | 5.8.4 |
| Licence | 0BSD |
| Upstream | https://tukaani.org/xz/ |
| Needs | [`gcc`](https://github.com/Artfical/tpkg-gcc), [`xz`](https://github.com/Artfical/tpkg-xz) |
| Needs tOS build | 615 or newer |
| Size | 175883 bytes (593654 unpacked) |
| SHA-256 of the `.tpkg` | `6be865f029eba6557efd03b048e06a96cd370540f88425041b28a5d5ff8ec621` |

## Commands it adds

| Command | Runs |
|---|---|
| - | - |

## Download

The package file (`liblzma-dev-5.8.4.tpkg`) and the sources it was built from are the assets of the
[v5.8.4 release](https://github.com/Artfical/tpkg-liblzma-dev/releases/tag/v5.8.4).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `xz-5.8.4.tar.xz`

Check a download: `sha256sum liblzma-dev-5.8.4.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: 0BSD. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
