# setup-obsidian-claude

## R — Reading（原文）
> 「首先安装Obsidian作为大脑存储器，创建一个文件夹命名为第二大脑。第二步用Cloud作为顶层大脑，跟Obsidian刚建的第二大脑文件夹建立链接。」（视频 00:00:58-00:01:10）

## I — Interpretation（自述）
物理结构分两层：底层是本地存储 Obsidian（文件落盘、可检索、属于你）；顶层是 Claude（Projects 作为「顶层大脑」）。关键动作是把两者链接起来——在 Claude 的 Project 里关联那个「第二大脑」文件夹，之后丢进文件夹的任何文件，Claude 都能读取并归档到你已知的所有内容里。这一步是后面「灵魂采访」和「每日 ingestion」能成立的前提。

## A1 — Application Example（合成演练）
设计演练（非作者亲历）：在 Obsidian 建库 `SecondBrain`，内建文件夹 `第二大脑`；打开 Claude 新建 Project「我的第二大脑」，在 Project 的「知识」里添加该本地文件夹路径。随后把一份 PDF 讲座笔记拖进文件夹，问 Claude「帮我归档这份笔记，并和已有的时间管理主题关联」——它读取后生成带链接的摘要。

## A2 — Future Trigger（关键）
用户会在这些情境下遇到：
1. 实际要动手搭 Obsidian+Claude 的第二大脑；
2. 问「Claude Projects 怎么连本地文件夹」「第二大脑文件夹怎么建」；
3. 已有 Obsidian 但不知道怎么让 Claude 接管。
语言信号：「Obsidian 怎么连 Claude」「Claude Projects 知识库」「第二大脑怎么搭建」。
和「纯 Obsidian 笔记法」不同：本能力强调把 Claude 设为可读取本地库的顶层大脑，而非只用 Obsidian 自己管理。

## E — Execution（可执行步骤）
1. 安装 Obsidian，新建仓库（vault）→ 完成标准：本地出现可写入的 vault。
2. 在 vault 内建文件夹，命名「第二大脑」→ 完成标准：文件夹存在且用户认同其用途。
3. 打开 Claude，新建 Project，把该「第二大脑」文件夹作为知识源关联 → 完成标准：Claude 能列出文件夹内文件。
4. 进入「灵魂采访」阶段（见 soul-interview-claude-md）。
输入契约：需用户有 Obsidian 与 Claude（支持 Projects / 本地文件读取）账户；缺任一则先说明替代方案。

## B — Boundary（边界）
- 不适用于已搭好只想维护的情况（见 daily-ingestion）。
- 没有 Claude Projects / 本地文件读取能力时，降级为「纯 Obsidian + 手动粘贴」，并提示能力损失。
- 别把敏感隐私文件无差别丢进被 AI 读取的文件夹。
