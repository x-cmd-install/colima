# colima

[English version](./README.md)

Container runtimes on macOS (and Linux) with minimal setup

![colima](https://repo.x-cmd.io/colima.svg?lang=zh)

## 安装

```sh
x install colima
```

## 代码洞察

合计: **11,266** 行代码（覆盖前 5 种语言、共 **121** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 10,884 | 1,231 | 2,305 | 108 |
| Sh | 143 | 29 | 50 | 4 |
| Yaml | 74 | 218 | 39 | 4 |
| Nix | 68 | 3 | 11 | 4 |
| Makefile | 64 | 0 | 18 | 1 |

## OpenSSF Scorecard 评分

总评分: **5.6 / 10**

评分最低的几项:

- **Security-Policy** (4/10) — security policy file detected
- **Packaging** (-1/10) — packaging workflow not detected
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions

## 源代码

- **上游仓库**: <https://github.com/abiosoft/colima>
- **官网**: <https://colima.run>
- **许可证**: MIT

## 发布

- **最新版本**: `v0.10.3` (2026-06-04)
- **最近提交**: 2026-08-13
- **Release 含资产**: 8 个

## 流行度

- **Star**: 30,758 · **Fork**: 610 · **开放 issue**: 904 · **贡献者**: 109

## 累计统计

- **发布数**: 65 · **已合并 PR**: 466 · **开放 PR**: 19 · **已关闭 issue**: 530 · **开放 issue**: 374 · **提交数**: 715

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 0 | 0 | 6 | 0 | 5 | 0 |
| last60d | 2026-07-12 | 0 | 4 | 14 | 2 | 9 | 3 |
| 90d | 2026-06-12 | 0 | 14 | 15 | 2 | 11 | 15 |
| last180d | 2026-03-14 | 2 | 34 | 17 | 7 | 24 | 39 |
| 360d | 2025-09-15 | 6 | 104 | 18 | 36 | 45 | 120 |
| last720d | 2024-09-20 | 12 | 182 | 19 | 93 | 118 | 237 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [colima-Darwin-arm64](https://github.com/abiosoft/colima/releases/download/v0.10.3/colima-Darwin-arm64) | 14.9 MiB | `native/darwin/arm64` |
| [colima-Darwin-arm64.sha256sum](https://github.com/abiosoft/colima/releases/download/v0.10.3/colima-Darwin-arm64.sha256sum) | 86 B | `native/darwin/arm64` |
| [colima-Darwin-x86_64](https://github.com/abiosoft/colima/releases/download/v0.10.3/colima-Darwin-x86_64) | 16.2 MiB | `native/darwin/x64` |
| [colima-Darwin-x86_64.sha256sum](https://github.com/abiosoft/colima/releases/download/v0.10.3/colima-Darwin-x86_64.sha256sum) | 87 B | `native/darwin/x64` |
| [colima-Linux-aarch64](https://github.com/abiosoft/colima/releases/download/v0.10.3/colima-Linux-aarch64) | 14.4 MiB | `native/linux/arm64` |
| [colima-Linux-aarch64.sha256sum](https://github.com/abiosoft/colima/releases/download/v0.10.3/colima-Linux-aarch64.sha256sum) | 87 B | `native/linux/arm64` |
| [colima-Linux-x86_64](https://github.com/abiosoft/colima/releases/download/v0.10.3/colima-Linux-x86_64) | 15.4 MiB | `native/linux/x64` |
| [colima-Linux-x86_64.sha256sum](https://github.com/abiosoft/colima/releases/download/v0.10.3/colima-Linux-x86_64.sha256sum) | 86 B | `native/linux/x64` |

## 发行版状态

在 [repology.org](https://repology.org/project/colima) 上共有 **11** 个发行版报告此项目。**5** 个 ✅ 已是最新上游版本，**5** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Homebrew | `0.10.3` | ✅ latest |
| Nix unstable | `0.10.3` | ✅ latest |

## 改进这些数据

colima 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `colima` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/colima.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260910.yml` · 2026-09-10T22:14:57Z._
