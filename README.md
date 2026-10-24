# erp-teaching-team

**ERP 教学团** · v1.0.0 · `team`

> ERP teaching team that teaches core concepts at four learner levels, sets exercises with clear rubrics, diagnoses where a learner is stuck, and plans what to study next — covering selection, five-year TCO/ROI, seven business domains, AI integration, and organizational adoption.


Part of the [WorkBuddy Experts](https://github.com/Lucewalk/lucewalk-experts) collection — expert teams, agents and skills for the WorkBuddy AI assistant platform.


## What it does

- **erp-ai-integration** — ERP + AI 集成技术资产库。当需要设计 ERP Agent 集成架构、编写业务工具函数、搭建 RAG 知识库、选型与私有化部署大模型、或判断 API/只读库/RPA 三种接法边界时使用。包含架构模板、14 个工具函数设计规范、RAG 分片策略、踩坑清单。
- **erp-asset-routing** — ERP 专家包资产调度与路由表。当需要判断"该由哪个专家包处理"、避免重复造轮子、或需要跨包协作完成 ERP 任务时使用。包含 15 个候选专家包的能力边界、路由判据、协作铁律与转包话术（是否已安装需现场确认）。
- **erp-knowledge-base** — ERP 专业知识库（全景 → 诊断 → 选型 → 论证 → 业务域 → AI 集成 → 组织落地，含 21 天训练营、40 题自测集、时效核验机制与学习沉淀方法）。当需要 Agentic ERP 现状、成熟度判断、流程断点诊断、方案评估、五年 TCO/ROI、采购销售供应链财务人
- **erp-pain-diagnosis** — ERP 痛点诊断方法库。当需要诊断 ERP 系统实施后的问题、定位流程断点、区分"真痛"与"不习惯"、识别自动化机会、或判断数据问题根因时使用。包含分域断点检查表、问题分类判据、优先级评分公式。
- **erp-teaching-method** — ERP 教学方法论（六个教练共用）。当需要按四层结构讲解概念、批改学生答案、诊断学习卡点、把握教师禁语、评估学习闭环，或讲授时效性内容的核验纪律时使用。

## Agent roster

| Agent | Role |
|---|---|
| `ai-adoption-coach` | AI 与落地教练 |
| `concept-coach` | 概念教练 |
| `domain-coach` | 业务域教练 |
| `erp-teaching-team-team-lead` | ERP 教学团 - 主讲人（课程主教习） |
| `exercise-coach` | 练习与评卷教练 |
| `progress-coach` | 进度与路径教练 |
| `selection-coach` | 选型与论证教练 |

## Install

1. Download the package zip from [Releases](https://github.com/Lucewalk/erp-teaching-team/releases) or clone this repo;
2. Unzip keeping the internal manifest structure intact;
3. Import/register in WorkBuddy (custom connector → trust & enable).

## Version

Current release: **v1.0.0** — see [CHANGELOG.md](CHANGELOG.md) if present, or the package manifest.

## License

MIT — see [LICENSE](LICENSE).
