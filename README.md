# Drama Skills · short-drama-storyboard

> **[short-drama-storyboard](https://github.com/simlpandordinary/short-drama-storyboard)** —— 飞书《WorkBuddy 视频系列 · 全技能与提示词总目录》里推荐的开源技能，已拆分为独立仓库分发（一个技能一个仓库）。

| 项 | 内容 |
| - | - |
| 上游仓库 | <https://github.com/zenstory-ai/drama-skills> |
| 上游路径 | `skills/short-drama-storyboard` |
| 上游协议 | MIT |
| 上游 Star | 3.7k+ |
| 拆分方式 | 仅抽取该技能自身文件，独立可用 |

## 技能说明

把中文短剧剧本和视觉设定写成有戏剧职责、连续性边界与冻结关键帧提示词的分镜 Markdown。用户提出“拆分镜/设计镜头/做镜头表”“场次视觉计划/调度故事板”“比较导演方案”“写首帧/关键帧提示词”或检查轴线、站位、视线、持物连续性时使用；不生成媒体。

## 目录结构

```
├── LICENSE
├── README.upstream.md
├── SKILL.md
├── references/
│   ├── blocking-playbooks.md
│   ├── comic-keyframe-lexicon.md
│   ├── coverage-audition.md
│   ├── fight-craft.md
│   ├── keyframe-craft.md
│   ├── lighting-craft.md
│   ├── production-shot-grammar.md
│   ├── review-and-fixtures.md
│   ├── scene-visual-plan.md
│   ├── screenplay-to-keyframe-example.md
│   ├── shot-craft.md
│   ├── shot-revision-identity.md
│   └── stage-contract.md
└── agents/
    └── openai.yaml
```

- `SKILL.md` 是技能入口（触发条件 / 工作流 / 约束），安装时必须位于技能根目录。
- `references/`、`scripts/`、`assets/` 为该技能自带的参考文档、脚本与素材。
- `README.upstream.md` 为上游仓库原始说明，保留出处与版权信息。
- `LICENSE` 为上游许可证原件。

## 安装

WorkBuddy 技能目录为 `~/.workbuddy/skills/short-drama-storyboard/`：

```bash
git clone https://github.com/simlpandordinary/short-drama-storyboard.git ~/.workbuddy/skills/short-drama-storyboard
```

也可以直接对 AI 说：「把 <https://github.com/simlpandordinary/short-drama-storyboard> 装成 Skill」。

安装后用自然语言触发，例如「Drama Skills · short-drama-storyboard」「用 short-drama-storyboard 帮我处理这个任务」。

## 版权

原始作者与版权归上游仓库 `zenstory-ai/drama-skills` 所有。本仓库仅做独立分发与结构整理，未修改技能内容；商用请遵循上游许可证。
