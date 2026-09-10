# rke

[中文版本](./README.cn.md)

> ⚠️ This project is archived.

Rancher Kubernetes Engine (RKE), an extremely simple, lightning fast Kubernetes distribution that runs entirely within containers.

![rke](https://repo.x-cmd.io/rke.svg)

## Install

```sh
x install rke
```

## Code insight

Total: **22,457** lines of code across **125** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 22,000 | 1,500 | 2,400 | 110 |
| Bash | 414 | 35 | 79 | 11 |
| Sh | 31 | 7 | 14 | 2 |
| Makefile | 11 | 0 | 4 | 1 |
| Json | 1 | 0 | 0 | 1 |

## OpenSSF Scorecard

Overall score: **3.3 / 10**

Lowest-scoring checks:

- **Code-Review** (0/10) — Found 0/30 approved changesets -- score normalized to 0
- **Maintained** (0/10) — project is archived
- **Packaging** (-1/10) — packaging workflow not detected

## Source

- **Upstream**: <https://github.com/rancher/rke>
- **License**: Apache-2.0

## Release

- **Latest**: `v1.8.14` (2026-06-03)
- **Last commit**: 2026-06-01
- **Assets in release**: 9

## Popularity

- **Stars**: 3,292 · **Forks**: 590 · **Open issues**: 1,527 · **Contributors**: 97

## Totals (cumulative)

- **Releases**: 749 · **Merged PRs**: 0 · **Open PRs**: 0 · **Closed issues**: 1496 · **Open issues**: 31 · **Commits**: 2406

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 0 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-07-12 | 0 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-06-12 | 0 | 0 | 0 | 0 | 0 | 0 |
| last180d | 2026-03-14 | 6 | 0 | 0 | 0 | 0 | 0 |
| 360d | 2025-09-15 | 17 | 0 | 0 | 0 | 0 | 0 |
| last720d | 2024-09-20 | 100 | 0 | 0 | 0 | 0 | 0 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [rke-extended-life-images.txt](https://github.com/rancher/rke/releases/download/v1.8.14/rke-extended-life-images.txt) | 1.6 KiB | `other` |
| [rke-k8sversions.txt](https://github.com/rancher/rke/releases/download/v1.8.14/rke-k8sversions.txt) | 108 B | `other` |
| [rke_darwin-amd64](https://github.com/rancher/rke/releases/download/v1.8.14/rke_darwin-amd64) | 67.1 MiB | `native/darwin/x64` |
| [rke_linux-amd64](https://github.com/rancher/rke/releases/download/v1.8.14/rke_linux-amd64) | 66.4 MiB | `native/linux/x64` |
| [rke_linux-arm](https://github.com/rancher/rke/releases/download/v1.8.14/rke_linux-arm) | 61.8 MiB | `native/linux/arm` |
| [rke_linux-arm64](https://github.com/rancher/rke/releases/download/v1.8.14/rke_linux-arm64) | 65.0 MiB | `native/linux/arm64` |
| [rke_windows-386.exe](https://github.com/rancher/rke/releases/download/v1.8.14/rke_windows-386.exe) | 63.6 MiB | `native/win/x64` |
| [rke_windows-amd64.exe](https://github.com/rancher/rke/releases/download/v1.8.14/rke_windows-amd64.exe) | 67.3 MiB | `native/win/x64` |
| [sha256sum.txt](https://github.com/rancher/rke/releases/download/v1.8.14/sha256sum.txt) | 674 B | `other` |

## Distribution status

Reported by **16** distros on [repology.org](https://repology.org/project/rke). **4** are ✅ on the latest upstream release, **11** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Homebrew | `1.8.14` | ✅ latest |
| Nix unstable | `1.8.14` | ✅ latest |
| Alpine edge | `1.4.3` | ⚠️ outdated |
| openSUSE Tumbleweed | `1.8.14` | ✅ latest |

## Improve this data

Install metadata for rke lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `rke` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/rke.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260910.yml` · 2026-09-10T20:08:37Z._
