---
name: chinese-writing-skills
description: |
  中文小说写作技法知识库。涵盖人物、情节、语言、场景、对话、节奏、悬念、爽点等系统性写作技巧。
  支持按需查阅特定技法，也可作为创作辅助参考。模块化设计，持续迭代扩展。
  当用户讨论：写作技巧、小说技法、怎么写出好故事、人物怎么塑造、情节怎么设计、对话怎么写时使用。
---

# 中文小说写作技法大全

> 系统化整理的中文小说写作技巧知识库。模块化设计，可独立查阅，也可组合使用。

## 设计理念

本 Skill 不是一个创作流程工具，而是一个**写作技法知识库**。它按主题组织，每个主题包含：
- 核心理论
- 实战技法
- 正反对比示例
- 常见错误
- 进阶巧思

你可以：
- **按主题查阅**：需要什么技巧就查什么模块
- **作为创作参考**：写作时对照检查
- **持续扩展**：随时补充新的技法和巧思

## 整合工作流

本知识库可与 [chinese-novelist](https://github.com/PenglongHuang/chinese-novelist-skill) 搭配使用，通过 `novel-writing-workflow` 编排层实现：

```
chinese-writing-skills (技法) + chinese-novelist (引擎)
              ↓
   novel-writing-workflow (编排层)
              ↓
      端到端小说创作系统
```

编排层已包含在本仓库 → [novel-writing-workflow/](novel-writing-workflow/)

详见 [novel-writing-workflow/SKILL.md](novel-writing-workflow/SKILL.md)

---

## 模块索引

| 编号 | 模块 | 文件 | 内容概要 |
|:---:|------|------|----------|
| 01 | 人物塑造 | [character.md](references/techniques/character.md) | 人物弧光、矛盾构建、侧面揭示、出场设计、反派深度 |
| 02 | 情节设计 | [plot.md](references/techniques/plot.md) | 冲突类型、节奏曲线、高潮构建、转折技法、多线叙事 |
| 03 | 语言风格 | [language.md](references/techniques/language.md) | 句式变化、修辞选用、语感培养、文白平衡、金句打造 |
| 04 | 场景描写 | [scene.md](references/techniques/scene.md) | 五感调动、时空营造、环境映射情绪、留白技法 |
| 05 | 对话设计 | [dialogue.md](references/techniques/dialogue.md) | 潜台词、角色辨识度、信息密度、对话推动情节、停顿的艺术 |
| 06 | 节奏控制 | [pacing.md](references/techniques/pacing.md) | 张弛之道、快写与慢写、信息释放节奏、章节节奏设计 |
| 07 | 悬念构建 | [suspense.md](references/techniques/suspense.md) | 钩子类型、信息差利用、预期管理、多层悬念体系 |
| 08 | 爽点设计 | [pleasure-points.md](references/techniques/pleasure-points.md) | 网文爽点公式、打脸/逆袭/翻盘、期待感管理、爽点密度 |
| 09 | 开篇技法 | [opening.md](references/techniques/opening.md) | 黄金三章、十种开头法、第一句话的艺术、前20%决胜 |
| 10 | 结尾技法 | [ending.md](references/techniques/ending.md) | 结局类型、余韵设计、开放式结局、每一章结尾的钩子 |
| 11 | 世界观构建 | [worldbuilding.md](references/techniques/worldbuilding.md) | 架空世界、规则体系、信息释放时机、氛围统一性 |
| 12 | 情感描写 | [emotion.md](references/techniques/emotion.md) | 外化技法、身体语言、情绪层次、克制与爆发、不直说的魅力 |

---

## 使用方式

### 按需查阅
当你需要某种写作技巧时，直接说：
- "给我看看人物塑造的技巧"
- "怎么写好对话？"
- "悬疑小说的悬念怎么设计？"

我会打开对应的模块文件，提供系统化的指导。

### 写作对照
在创作时可以逐模块对照检查：
```
□ 人物是否有弧光？
□ 情节冲突是否足够？
□ 句子长短是否有变化？
□ 场景是否有五感细节？
□ 对话是否有辨识度？
□ 节奏是否有张有弛？
□ 悬念是否留到结尾？
□ 爽点密度是否足够？
```

### 持续迭代
本 Skill 支持持续扩展。要添加新技法，在 `references/techniques/` 下添加新模块文件，然后更新本文件的模块索引即可。

---

## 快速参考卡

写作时常遇到的问题 → 对应模块：

| 问题 | 查这个模块 |
|------|-----------|
| 角色太平淡，没有记忆点 | 01-人物塑造 |
| 故事像流水账，不够吸引人 | 02-情节设计 |
| 文字太干，没有文学味 | 03-语言风格 |
| 环境描写不知道怎么写 | 04-场景描写 |
| 对话像在念稿子 | 05-对话设计 |
| 读者说节奏太快/太慢 | 06-节奏控制 |
| 不知道下一章写什么 | 07-悬念构建 |
| 网文读者说不够爽 | 08-爽点设计 |
| 开头留不住读者 | 09-开篇技法 |
| 结尾收不住或太平淡 | 10-结尾技法 |
| 架空世界设定不起来 | 11-世界观构建 |
| 感情戏写得假 | 12-情感描写 |
