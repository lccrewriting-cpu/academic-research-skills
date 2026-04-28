# Wentor Skills 工具转载说明

> 原始入口：<https://wentor.ai/skills>

本文件用于在本仓库中**转载与归档** Wentor Skills 的入口信息，方便中文用户快速访问并安装相关技能。

## 快速访问

- Wentor Skills 首页：<https://wentor.ai/skills>
- Wentor 官方 GitHub（技能仓库）：<https://github.com/wentorai/research-plugins>

## 一键安装（按需）

```bash
# 安装整套 skills（建议先在独立环境试用）
npx skills add wentorai/research-plugins
```

## 单技能安装示例

```bash
# Semantic Scholar API skill
curl -o ~/.claude/skills/semantic-scholar-api/SKILL.md --create-dirs \
  "https://raw.githubusercontent.com/wentorai/research-plugins/main/skills/literature/search/semantic-scholar-api/SKILL.md"
```

## 说明

- 本页为转载导航，不修改 Wentor 原始内容与许可。
- 实际技能内容、更新节奏、兼容性以原仓库发布为准。
- 建议在引入第三方 skill 前做安全检查，并在隔离环境验证后再用于正式研究流程。
