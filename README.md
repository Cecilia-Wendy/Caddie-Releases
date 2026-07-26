# Caddie Releases

Caddie 求职管家的公开发行仓库。

本仓库仅用于分发经过签名验证的 macOS 安装包和自动更新清单，不包含应用源码、用户数据、API Key 或发布私钥。

## 安装

1. 从 Releases 下载最新的 macOS Apple Silicon 安装包。
2. 解压后阅读压缩包中的“首次打开-Caddie.txt”。
3. 首次安装需要手动完成 macOS 信任操作；后续版本可在 Caddie 的“设置 → 应用更新”中安装。

## 安全

Caddie 会使用内置 Ed25519 公钥验证更新清单，并使用 SHA-256 校验安装包完整性。校验失败的更新不会被安装。
