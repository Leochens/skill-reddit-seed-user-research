# Reddit Seed User Research

[English README](README.md)

[![罐头实验室](https://world.guantou.site/badge.svg?theme=dark&accent=red&lang=zh&size=sm)](https://world.guantou.site/)

这是一个用于在 Reddit 上寻找项目种子用户机会的 Codex skill。它关注真实需求发现和有价值的低打扰回复，不做自动发帖。

## 它适合做什么

- 从项目目录生成本地 `brand.md` 品牌/定位资料。
- 搜索 Reddit 上真实用户需求、重复痛点和相关社区。
- 按匹配度、用户意图、风险和链接策略排序机会。
- 生成先提供价值、必要时披露关系的英文回复草稿。
- 基于 `references/report-template.md` 输出中英双语报告。

## 安装

```bash
git clone https://github.com/Leochens/skill-reddit-seed-user-research.git ~/.codex/skills/reddit-seed-user-research
```

然后可以这样告诉 Codex：

```text
Use $reddit-seed-user-research to find Reddit seed-user opportunities for this project.
```

## 使用说明

这个 skill 不会自动发帖。用户需要在发布前手动检查目标帖子、subreddit 规则、账号状态和回复草稿。

`brand.md` 会被视为本地研究资料。在 Git 仓库里，它应该通过 `.git/info/exclude` 忽略，而不是提交到共享仓库。

## 仓库结构

```text
SKILL.md                              Skill 指令
agents/openai.yaml                    Codex UI 元数据
references/brand-template.md          本地品牌资料模板
references/report-template.md         中英双语 Reddit 报告模板
```

## 了解更多罐头实验室项目

这个 skill 是 GuanTou Lab 个人 agent 工作流工具箱的一部分。可以访问 [罐头的世界](https://world.guantou.site/) 查看更多项目和产品。

## 开源协议

MIT License。见 [LICENSE](LICENSE)。
