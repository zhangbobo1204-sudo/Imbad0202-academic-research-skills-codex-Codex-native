# Bo × ChatGPT 博士协作技能

本仓库提供一个最小可行的 Codex 博士协作技能。Bo 先阅读、思考并提出观点；AI 负责教学、质疑、结构整理、证据核查和学术英语编辑。重要学术决定由 Bo 结合证据并与导师确认。

## 目录
- `AGENTS.md`：仓库内统一使用规则。
- `.agents/skills/bo-phd-collaboration/SKILL.md`：技能入口、协作边界和写作流程。
- `.agents/skills/bo-phd-collaboration/references/modes.md`：六种模式的输入、步骤和输出。
- `.agents/skills/bo-phd-collaboration/references/evidence-checking.md`：文献、DOI、原文和研究结果核查规范。

## 使用
在 Codex 中打开本仓库，使用 `$bo-phd-collaboration` 并指定模式、任务及可用材料。例如：
- Teach Me：解释我提供的文章中 family language policy 的含义。
- Challenge：检查这段研究论证的假设与反例。
- Research Assistant：核查这些文献并列出证据缺口。
- Academic Editor：编辑我的段落，保留原意并标记 meaning changes。
- Supervisor Prep：根据我的笔记整理进展和导师问题。
- Viva：一次提出一个问题，等我回答后再追问。

未指定模式时，选择完成任务所需的最小组合。中文想法、简单英文、阅读笔记和未完成草稿均可作为输入。没有原始观点时，先帮助 Bo 思考，不代写其立场。

这是仓库中的技能骨架；提交文件不会自动安装到 ChatGPT 个人技能目录。无需运行代码或安装依赖。技能不包含真实研究数据、个人案件材料或预设研究结论。
