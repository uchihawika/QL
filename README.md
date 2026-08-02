# TAVO 设计专家 / TAVO Design Expert

**Language:** 中文 · [English](#english)

---

## 简介

为 **TAVO / TavoJS**（SillyTavern 强大分支）设计的 AI 助手技能包。用户用自然语言描述想要的角色、世界观、规则或交互效果，AI 生成可直接导入 TAVO 的 JSON 数据。

覆盖 **角色卡 / 世界书 / 正则 / 变量 / 预设 / 长记忆 / 插件** 全部模块，基于 TavoJS **v0.75 ~ v0.91** 完整 API 文档编写。

---

## 功能一览

| 模块 | 说明 |
|---|---|
| 角色卡 | CCv3 规范，含 EJS 条件开场白 |
| 世界书 | 关键词触发 / 常驻 / 概率注入 / sticky / cooldown / delay |
| 正则 | input→宏展开 / output 格式化 / 推理层替换 |
| 变量 | chat / global / message 三作用域 + EJS + lodash |
| 宏 | `{{setvar}}` / `{{getvar}}` / `{{roll}}` / 时间宏等 |
| 预设 | entries + injectionPosition/injectionDepth |
| 长记忆 | memories 数组 |
| 插件 | manifest v2 + entry + htmlFragments + Hooks |

---

## 安装

```bash
npx skills add uchihawika/QL
```

手动：将 `SKILL.md` 放入 `~/.qclaw/skills/tavo-design-expert/`。

---

## 使用

直接开口描述你的需求，例如：

> "帮我设计一个赛博朋克风格的地下城主持人角色，HP 100"

AI 引导确认关键参数，生成完整 JSON 并标注导入方式。

---

## 发布许可

MIT License

---

<a id="english"></a>

## English

AI skill for designing **TAVO / TavoJS** character cards, lorebooks, regex rules, and more. Generates ready-to-import JSON directly into TAVO.

---

> Built with [OpenClaw](https://github.com/openclaw/openclaw) · Published on [skills.sh](https://skills.sh)
