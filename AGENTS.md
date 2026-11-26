# AGENTS.md

本文件给在这个仓库里工作的 AI 编码助手和协作者看。

## 验证不依赖 GitHub CI

2026-11-25 起，本仓库不用 GitHub Actions 做验证，也不用它构建、发布或部署（发布 GitHub Pages 除外）。`.github/workflows/` 里只允许放发布 GitHub Pages 的工作流，别的工作流不要新建。

- 测试、检查、构建都在本机（或经 calltable `ct` 在验证机）上跑，推送前自己跑完。
- 提交和推送说明里写实际跑过的命令和环境，不写「CI 通过」，也不要等 CI 结果。
