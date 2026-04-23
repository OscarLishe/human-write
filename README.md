# human-write

中文优先、可交付导向的写作 skill，用于把中文文档写得更自然、更具体、更少 AI 腔，并且更容易直接交付或转为 Word/PPT。

A delivery-oriented writing skill for Chinese formal documents. It helps produce natural, specific, less AI-sounding output that is easier to deliver directly or convert to Word/PPT.

## 适用场景 / When to Use

- 报告、方案、政策咨询、会议纪要、研究计划、申报材料
- 需要“去 AI 味”、结构清晰、可核查来源、可直接交付的正式文本
- Formal Chinese materials that require clear structure, traceability, and human-like tone

## 核心能力 / What It Enforces

- 先判断文档类型，再套通用规则和类型专项规则
- 约束空话、套话、模板腔，优先具体事实与可执行表达
- 交付前执行结构、语言、排版一致性检查

## 快速使用 / Quick Start

```text
$human-write
请把下面这份研究方案改写成正式中文版本，要求：
1) 去掉明显 AI 腔
2) 保留关键事实和证据链
3) 输出可直接转 Word 的结构
```

## 目录结构 / Structure

- `SKILL.md`: 触发与执行流程定义 / Triggering and workflow
- `references/writing-standard-zh.md`: 中文写作与排版细则 / Full Chinese standards
- `agents/openai.yaml`: 展示元数据 / UI metadata

## 说明 / Notes

- 本 skill 主要面向中文写作，因此规则重点在中文表达与正式文档风格。
- This skill is optimized for Chinese formal writing tasks.
