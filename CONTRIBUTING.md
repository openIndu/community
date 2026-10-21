# 贡献指南 | Contributing Guide

感谢你对 openIndu 社区的关注！无论是报告 Bug、提出需求还是贡献代码，都是对社区的重要支持。

## 参与方式

| 方式 | 说明 |
| ---- | ---- |
| 提交 Issue | 报告 Bug、提出功能建议、创建任务 |
| 提交 PR | 修复 Bug、开发新功能、完善文档 |
| **贡献数据** | 电气模组模板、品牌映射、IO 表、工艺参数、缺陷图谱——**不需要会写代码**，见下节 |
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

## 贡献数据（模板 / 参数 / 映射表）

openIndu 最需要的贡献不只是代码，还有**数据条目**：电气模组模板、品牌映射、
IO 表样例、工艺参数、缺陷图谱、PLC 程序片段。这类贡献不需要你是软件开发者——
在 GitHub 网页上改一个文件就能发起 PR。

这类贡献落在 **[openIndu-studio](https://github.com/openIndu/openIndu-studio)**。
该仓的贡献指南同时写明了**贡献数据的归属边界**（哪些永久免费、什么才可能成为付费内容、
混合贡献如何拆分）与**签署要求（DCO）**：

- [CONTRIBUTING.md](https://github.com/openIndu/openIndu-studio/blob/main/CONTRIBUTING.md) — English
- [CONTRIBUTING_ZH.md](https://github.com/openIndu/openIndu-studio/blob/main/CONTRIBUTING_ZH.md) — 中文

> 归属条款以上述仓内文件为准，**本文不复述**——同一套规则在两处各写一份必然漂移，
> 而这套规则的价值恰恰在于「贡献者当时看到的是什么」。

## 代码规范

各仓库在自己的 `README.md` 中说明技术栈与本地开发方式，贡献前请先阅读对应仓库文档。

## 行为准则

参与社区请遵守 [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)。
