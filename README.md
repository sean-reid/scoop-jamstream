# scoop-jamstream

Scoop bucket for [JamStream](https://sean-reid.github.io/jamstream).

```console
$ scoop bucket add jamstream https://github.com/sean-reid/scoop-jamstream
$ scoop install jamstream
```

`jamstream` is the terminal client. `jamstream-app` is the desktop app
and the `jamstreamd` session server, with a Start Menu shortcut.

The manifests are rendered from each release's `SHA256SUMS` by
`scripts/render-packaging.sh` in the
[main repository](https://github.com/sean-reid/jamstream) and copied
here verbatim; changes belong there.
