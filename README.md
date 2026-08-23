# syncmeta/homebrew-tap

[syncmeta](https://github.com/syncmeta) 自建的 Homebrew tap。

```sh
brew install --cask syncmeta/tap/pendingcrew
```

## 为什么是自建 tap，不是官方 homebrew-cask

官方仓库对项目有知名度门槛，按 [Homebrew 的 Package Acceptance Policy](https://docs.brew.sh/Package-Acceptance-Policy)：
普通提交需要 **≥30 forks / 30 watchers / 75 stars** 之一，**由仓库作者本人提交则需要
≥90 / 90 / 225**；此外「建库不满 30 天通常不合格」。这些项目达不到，所以走自建 tap ——
没有门槛，且升级节奏完全自己掌控。

## Casks

| Cask | 项目 |
|---|---|
| `pendingcrew` | [PendingCrew](https://github.com/syncmeta/PendingCrew) —— 在自己的 Mac 上把多个 coding agent 当成一个小组来带 |

Cask 里的 `version` / `sha256` 由各项目发版脚本自动更新
（PendingCrew 见 `scripts/release/update-homebrew-tap.sh`），不手工维护。
