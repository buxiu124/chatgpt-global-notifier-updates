# ChatGPT 全局完成提醒 — 自动更新分发端

本仓库**只**用于分发 Firefox 扩展的自动更新元数据与已签名安装包，**不包含任何源代码**。

- `updates.json` — Firefox 原生自动更新（self-managed update）使用的 update manifest
- Releases 中的 `*.xpi` — 由 Mozilla AMO 签名的发行包（unlisted / self-distribution）

扩展 ID：`@chatgpt-global-notifier-buxiu`

这些文件由发布工具链自动写入；签名 XPI 的 SHA-256 与 `updates.json` 中的 `update_hash` 一致。
