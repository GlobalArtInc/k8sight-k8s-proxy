# K8sight K8s Proxy

<!-- markdownlint-disable MD013 -->

[![GitHub](https://img.shields.io/github/v/release/GlobalArtInc/k8sight-k8s-proxy?display_name=tag&sort=semver)](https://github.com/GlobalArtInc/k8sight-k8s-proxy)
[![Test](https://github.com/GlobalArtInc/k8sight-k8s-proxy/actions/workflows/test.yaml/badge.svg)](https://github.com/GlobalArtInc/k8sight-k8s-proxy/actions/workflows/test.yaml)

<!-- markdownlint-enable MD013 -->

More secure alternative to `kubectl proxy`.

## How to build

On Mac and Linux install tools using [mise](https://mise.jdx.dev/):

```sh
mise install
make download
make build
```

On Windows:

```powershell
winget install GoLang.Go
winget install goreleaser.goreleaser
./Makefile.ps1 download
./Makefile.ps1 build
```
