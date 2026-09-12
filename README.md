# 星期五启动器（FKCL）自动更新仓库

本仓库用于托管星期五启动器的更新清单与发布包。

## 更新源配置

在启动器「设置 → 关于与更新」中填写：

- **update_url**：`https://raw.githubusercontent.com/mirror101-git/fkcl-mc-launcher/main/update.json`
- **update_repo**：`mirror101-git/fkcl-mc-launcher`

## 发布新版本流程

1. 修改 `update.json` 中的版本号与更新说明
2. 将更新包压缩为 `fkcl-update.zip`（包含 exe 与 resources 的完整目录）
3. 创建 GitHub Release（tag 如 `v1.0.2`）并上传 `fkcl-update.zip`

启动器启动后会自动检查并提示更新。
