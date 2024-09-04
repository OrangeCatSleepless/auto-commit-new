# 自动提交

🌳 让你的 Github 统计变绿，由 [Github Actions](https://github.com/features/actions) 驱动

[![自动提交](https://github.com/mazipan/auto-commit/workflows/Auto%20commit/badge.svg)](https://github.com/mazipan/auto-commit/actions?query=workflow%3A%22Auto+commit%22)

![Mazipan 的 Github 统计](https://ghchart.rshah.org/mazipan)

## 创建你自己的版本

- 点击 "**使用此模板**" 按钮创建你自己的仓库（⚠️ fork 的仓库无法正常工作）

- ✅ 你需要配置你的仓库。前往：**设置** -> **操作** -> **常规** -> **工作流程权限**，并选择 **"读取和写入权限"**
- ✅ 在 [autocommit.yml](.github/workflows/autocommit.yml#L53) 更改 `email` 和 `name` 信息
- ✅ 在 [autocommit.yml](.github/workflows/autocommit.yml#L9) 更改调度时间。如果你不熟悉 cron 调度字符串，可以使用 [crontab.guru](https://crontab.guru/)。首次尝试时，你可以使用 `1 * * * *` 字符串每小时运行一次。

## 致谢

- [Github Actions](https://github.com/features/actions)
- [ad-m/github-push-action](https://github.com/ad-m/github-push-action)
- [mazipan/auto-commit: 🌳 Making green your Github stats, powered by Github 操作](https://github.com/mazipan/auto-commit)