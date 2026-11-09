# codex-skills — Sean 的 Skill 收藏仓

收藏自抖音【老麦不废话】《5个神级Skill，装完Codex直接开挂！》（2026-10-25 发布），
2026-11-09 由柚子逐个在 GitHub 核实后存入本体。星数为存入当日数据。

| # | Skill | 用途 | 来源仓库 | 星数 | 许可 |
|---|-------|------|----------|------|------|
| 1 | Caveman | 让 Agent 少说废话、省 Token（/caveman、/ultracave、/megacave 三档） | https://github.com/JuliusBrussee/caveman | 118.5k | Apache-2.0 |
| 2 | Taste Skill | 给编码 Agent 设计品味：艺术方向、真实图片、浏览器自检，摆脱"AI味"页面 | https://github.com/Leonxlnx/taste-skill | 112.3k | MIT |
| 3 | Playwright | 微软浏览器自动化；本仓存的是其面向编码 Agent 的官方 skills（playwright-cli 等） | https://github.com/microsoft/playwright | 99.7k | Apache-2.0 |
| 4 | GSAP Skills | GreenSock 官方 AI 技能包：教 Agent 正确使用 GSAP 动效（core/timeline/ScrollTrigger 等 8 个） | https://github.com/greensock/gsap-skills | 18.1k | 见 gsap-skills/LICENSE |
| 5 | Hypit | 拆解爆款视频并重建工作流：换脸/换文案/换 B-roll，批量生成变体 | https://github.com/hypit-ai/hypit | 28.7k | Apache-2.0 |

## 目录说明

- `caveman/` — 上游 `skills/` 全量（17 个子技能）+ LICENSE
- `taste-skill/` — 上游 `skills/taste-skill/` 全量文本文件（SKILL.md + assets 代码库）+ LICENSE。
  **未含**：151 个二进制图片（jpg/png/webp，为示例装饰照片，无法经文本通道存入）；需要时到上游仓库取。
- `gsap-skills/` — 上游仓库全量
- `hypit/` — 上游 `skills/hypit/` 全量（SKILL.md + references playbooks）+ LICENSE
- `playwright/` — 上游 `packages/playwright-core/src/tools/skills/` 全量（playwright-cli、
  playwright-component-testing、playwright-trace）+ LICENSE。Playwright 框架本体请按官方方式安装
  （`npm i -g @playwright/cli@latest` 或 `npx @playwright/mcp@latest`），不在本仓范围内。

## 原始安装命令（上游）

- Taste Skill：`npx skills add Leonxlnx/taste-skill`
- Playwright CLI：`npm i -g @playwright/cli@latest`；Playwright MCP：`npx @playwright/mcp@latest`
- 其余见各目录内 README / SKILL.md。

> 本仓为个人学习收藏，版权与许可归各上游作者所有，使用请遵守各目录内 LICENSE。
