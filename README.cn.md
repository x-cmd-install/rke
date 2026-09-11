# rke

[English version](./README.md)

> ⚠️ 此项目已归档（archived）。

Rancher Kubernetes Engine (RKE), an extremely simple, lightning fast Kubernetes distribution that runs entirely within containers.

![rke](https://repo.x-cmd.io/rke.svg?lang=zh)

## 安装

```sh
x install rke
```

## 代码洞察

合计: **22,457** 行代码（覆盖前 5 种语言、共 **125** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 22,000 | 1,500 | 2,400 | 110 |
| Bash | 414 | 35 | 79 | 11 |
| Sh | 31 | 7 | 14 | 2 |
| Makefile | 11 | 0 | 4 | 1 |
| Json | 1 | 0 | 0 | 1 |

## OpenSSF Scorecard 评分

总评分: **3.3 / 10**

评分最低的几项:

- **Code-Review** (0/10) — Found 0/30 approved changesets -- score normalized to 0
- **Maintained** (0/10) — project is archived
- **Packaging** (-1/10) — packaging workflow not detected

## 源代码

- **上游仓库**: <https://github.com/rancher/rke>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v1.8.14` (2026-06-03)
- **最近提交**: 2026-06-01
- **Release 含资产**: 9 个

## 流行度

- **Star**: 3,292 · **Fork**: 590 · **开放 issue**: 1,527 · **贡献者**: 97

## 累计统计

- **发布数**: 749 · **已合并 PR**: 0 · **开放 PR**: 0 · **已关闭 issue**: 1496 · **开放 issue**: 31 · **提交数**: 2406

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-12 | 0 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-07-13 | 0 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-06-13 | 0 | 0 | 0 | 0 | 0 | 0 |
| last180d | 2026-03-15 | 6 | 0 | 0 | 0 | 0 | 0 |
| 360d | 2025-09-16 | 17 | 0 | 0 | 0 | 0 | 0 |
| last720d | 2024-09-21 | 100 | 0 | 0 | 0 | 0 | 0 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [rke-extended-life-images.txt](https://github.com/rancher/rke/releases/download/v1.8.14/rke-extended-life-images.txt) | 1.6 KiB | `other` |
| [rke-k8sversions.txt](https://github.com/rancher/rke/releases/download/v1.8.14/rke-k8sversions.txt) | 108 B | `other` |
| [rke_darwin-amd64](https://github.com/rancher/rke/releases/download/v1.8.14/rke_darwin-amd64) | 67.1 MiB | `native/darwin/x64` |
| [rke_linux-amd64](https://github.com/rancher/rke/releases/download/v1.8.14/rke_linux-amd64) | 66.4 MiB | `native/linux/x64` |
| [rke_linux-arm](https://github.com/rancher/rke/releases/download/v1.8.14/rke_linux-arm) | 61.8 MiB | `native/linux/arm` |
| [rke_linux-arm64](https://github.com/rancher/rke/releases/download/v1.8.14/rke_linux-arm64) | 65.0 MiB | `native/linux/arm64` |
| [rke_windows-386.exe](https://github.com/rancher/rke/releases/download/v1.8.14/rke_windows-386.exe) | 63.6 MiB | `native/win/x64` |
| [rke_windows-amd64.exe](https://github.com/rancher/rke/releases/download/v1.8.14/rke_windows-amd64.exe) | 67.3 MiB | `native/win/x64` |
| [sha256sum.txt](https://github.com/rancher/rke/releases/download/v1.8.14/sha256sum.txt) | 674 B | `other` |

## 发行版状态

在 [repology.org](https://repology.org/project/rke) 上共有 **16** 个发行版报告此项目。**4** 个 ✅ 已是最新上游版本，**11** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Homebrew | `1.8.14` | ✅ latest |
| Nix unstable | `1.8.14` | ✅ latest |
| Alpine edge | `1.4.3` | ⚠️ outdated |
| openSUSE Tumbleweed | `1.8.14` | ✅ latest |

## 改进这些数据

rke 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `rke` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/rke.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260911.yml` · 2026-09-11T04:46:23Z._
