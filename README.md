# Literature Tracker｜跨学科文献追踪

一个用于 Codex 的文献追踪技能。可以做一次近期文献简报，也可以逐题配置一份持续更新的论文周刊。

## 快速开始

1. 下载或克隆本仓库。
2. 将整个 `literature-tracker/` 目录复制到用户技能目录 `~/.agents/skills/`，或目标项目的 `.agents/skills/`。
3. 在 Codex 中开启新对话，输入「用 `$literature-tracker` 帮我创建一个周刊」。

首次建刊会逐题确认学科、方向、监测来源、周期、格式和 Zotero。支持多选表单时，可在同一张卡勾选多个方向或来源并补充「其他」。也可以直接请求单次简报，例如「用 `$literature-tracker` 追踪最近一个月的电化学储能研究」。

## 筛选与归档

技能结合主题检索和固定来源监测，核对发表状态、版本和近期进展，按 DOI 等标识去重。根据证据、方法、局限及相关度决定荐读，允许零篇入选。星级表示阅读优先级，A/B/C 表示实际核验深度。

可选 Zotero 桌面端或官方云端 API，默认按 `周刊名 → 月.日` 归档正式荐读。定时运行和 Zotero 写入需要宿主提供相应工具与权限。云端密钥在运行环境中配置。

详见 [技能入口](literature-tracker/SKILL.md)、[建刊引导](literature-tracker/references/onboarding.md) 和 [集成说明](literature-tracker/references/integrations.md)。
