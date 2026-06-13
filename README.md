# 🏛️ Legal-Exam-Skills-AI

<div align="center">
  <img src="https://img.shields.io/badge/License-MIT-E8F5E9?style=flat-square&logo=opensourceinitiative&logoColor=black" alt="License">
  <img src="https://img.shields.io/badge/Domain-Chinese_Law-E8F5E9?style=flat-square" alt="Domain">
  <img src="https://img.shields.io/badge/Status-Active-E8F5E9?style=flat-square" alt="Status">
</div>

> **非 AI 替代，而是 AI 辅助。** 
> 本项目是一个专为中国大陆法考（客观题/主观题）及法学考研设计的结构化 AI 提示词（Prompt）与 Agent 编排技能库。

## 🎯 设计哲学

不同于简单的“替人写文书”指令，本技能库将法律推理的认知过程划分为三层架构：
- **输入 (Input)**：复杂长文本与案情的事实剥离、因果映射。
- **处理 (Process)**：基于成文法的逻辑推演、陷阱生成与管辖权决策。
- **输出 (Output)**：法理学宏观叙事搭建、合宪性审查图谱与法言法语纠偏。

## 🗂️ 技能导航 (Skills Directory)

| 模块 | 部门法 | 技能名称 | 适用场景 |
| :--- | :--- | :--- | :--- |
| **01 提取** | 刑法 | [犯罪构成事实拆解与映射引擎](./01-Knowledge-Extraction/crime-constitution-deconstructor.md) | 多人多次交织犯罪定罪逻辑剥离 |
| **01 提取** | 行政法 | [受案范围边界拆解](./01-Knowledge-Extraction/act-and-scope-deconstructor.md) | 具体/抽象行政行为定性 |
| **01 提取** | 民商法 | [请求权基础与连环嵌套解析器](./01-Knowledge-Extraction/claim-basis-relationship-mapper.md) | 复杂合同、担保、物权交叉案情图谱化 |
| **02 测验** | 知识产权法 | [侵权比对与权利限制测验机](./02-Exam-Simulation/ip-infringement-trap-generator.md) | 合理使用、先用权等免责条款陷阱测验 |
| **02 测验** | 刑事诉讼法 | [证据链与期限陷阱题生成器](./02-Exam-Simulation/evidence-and-timeline-generator.md) | 羁押期限重算、非法证据排除盲点 |
| **02 测验** | 国际私法 | [涉外管辖权与准据法指引决策树](./02-Exam-Simulation/transnational-jurisdiction-solver.md) | 冲突规范与最密切联系原则推演 |
| **03 批改** | 民事诉讼法 | [普通程序精准校验器](./03-Evaluation-and-Feedback/ordinary-program-validator.md) | 概念对齐与程序违规纠偏 |
| **03 批改** | 法理学 | [深度论述架构师](./03-Evaluation-and-Feedback/essay-architect.md) | 主观大题模板注入与法言法语包装 |
| **03 批改** | 宪法 | [合宪性审查推演图谱](./03-Evaluation-and-Feedback/constitutional-review-analyzer.md) | 机构职权越权审查与比例原则应用 |

## 🚀 如何使用

1. 点击上方表格中的技能链接，进入对应的 `.md` 文件。
2. 复制 `# Role` 至文末的所有文本。
3. 粘贴到你常用的 AI 交互界面（如 Gemini 1.5 Pro, Claude 3.5, NotebookLM）。
4. 替换文本中 `[{{填写...}}]` 的变量即可开始运行。
