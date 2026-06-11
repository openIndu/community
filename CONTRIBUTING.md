# 贡献指南 | Contributing Guide

感谢你对 openIndu 社区的关注！无论是报告 Bug、提出需求还是贡献代码，都是对社区的重要支持。

## 参与方式

| 方式 | 说明 |
| ---- | ---- |
| 提交 Issue | 报告 Bug、提出功能建议、创建任务 |
| 提交 PR | 修复 Bug、开发新功能、完善文档 |
| 参与讨论 | GitHub Discussions 分享经验与想法 |

## Issue 规范

提交 Issue 前请先搜索是否已有相同 Issue。提交时请选择正确的类型：

- **Task** — 需要完成的开发任务
- **Feature** — 新功能或改进建议
- **Bug** — 程序缺陷报告

## PR 流程

1. **Fork** 目标仓库到你的账号
2. 基于 `main` 创建分支，命名遵循：
   - `feat/xxx` — 新功能
   - `fix/xxx` — Bug 修复
   - `docs/xxx` — 文档更新
   - `refactor/xxx` — 重构
3. 本地开发完成后提交，commit message 遵循 [Conventional Commits](https://www.conventionalcommits.org/) 格式：
   ```
   feat: 添加设备批量导入功能
   fix: 修复设备状态不刷新问题
   docs: 更新部署文档
   ```
4. 推送到你的 Fork，发起 Pull Request 到目标仓库 `main` 分支
5. 填写 PR 模板，关联相关 Issue
6. 等待 Maintainer Review，根据反馈修改

## 代码规范

各仓库在自己的 `README.md` 中说明技术栈与本地开发方式，贡献前请先阅读对应仓库文档。

## 行为准则

参与社区请遵守 [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)。
