# writing-order（写作秩序）

面向通用 AI 文生文写作与改稿的秩序规程（Agent Skill）。单文件即装即用，不绑定任何学科专业或特定行业文体，兼容 **Antigravity**、**Claude Code**、**OpenAI Codex**、**Cursor** 及各类网页端对话大模型。

---

## 解决什么问题

大模型在生成或精简文本时，常陷入两类失序状态：

- **生成时虚浮混乱**：堆砌生造词、圈层歧义词、打比方、X字诀或排比口号；小标题写成意思悬空的词组并列或生硬拼凑；章节之间反复剧透与重述，缺少面向陌生读者的事理主线。
- **精简时残缺僵硬**：一旦要求控字数，便不舍得砍掉边缘内容点，转而抠掉主语、谓语、宾语和逻辑连接词来硬压篇幅，产出难以卒读的“电报式碎句”与无标点长句。

`writing-order` 将平实易懂的规则与直观的正反改写示例融于单一 `SKILL.md` 文件中，按**“入场底线 → 篇章脉络 → 标题拟定 → 语句表达 → 成稿裁剪 → 底稿修订”**六大模块，为 AI 的文本生成与改稿行为建立秩序。

---

## 六大模块概览

1. **入场底线**：按任务类型选定做法（短篇不硬拆标题）；只补逻辑和句法、不编造事实；理解沟通与批注意图，不在正文中留解释痕迹或反向声明。
2. **篇章脉络**：章内纯粹同类、章间内容独立不重述，交界处仅做极简过渡；单板块先交代动因，再顺着“源起动因 → 内在法则或演进方向 → 具体运行或演化机制 → 最终产生的结果或状态”推进。
3. **标题拟定**：直接亮出核心判断；拆开仅表面相关的生硬拼凑项，保留连贯因果链条；删去多余修饰但保留必要助词，不为凑字数对称挤压词义。
4. **语句表达**：用平实书面语“说人话”，去除生造词、自创简写、夸张修饰、打比方与口号对仗；立住扎实主语，消除跨分句主语暗换与共用中心词回溯；在连动动作、前置状语与后置“以……”处积极断句并保留连接词；只用肯定句正面陈述。
5. **成稿裁剪**：将“放开写顺初稿”与“独立过筛裁剪”拆为先后两步，按“砍边缘原则（章节内部文字只为本章节负责）”“非此即彼原则（写了正面不写反面）”“减字不减句法原则”做减法。
6. **底稿修订**：默认冻结；仅在修改已有底稿或带批注文档时自动启用，执行先对齐后动稿、只改点名处（用户已定稿文字零触碰）与延续原有版式对象格式。

---

## 安装方式

### 1. Google Antigravity

克隆至全局技能目录（对本机所有工作区生效）：

```bash
git clone https://github.com/<rc8s2242sr-cmd>/writing-order.git ~/.gemini/config/skills/writing-order
```

或放入单个项目的 `.agents/skills/writing-order/` 目录中。

### 2. Claude Code

```bash
git clone https://github.com/<rc8s2242sr-cmd>/writing-order.git ~/.claude/skills/writing-order
```

### 3. OpenAI Codex

```bash
git clone https://github.com/<rc8s2242sr-cmd>/writing-order.git ~/.codex/skills/writing-order
```

### 4. Agent Skills 通用 CLI（`skills.sh`）

```bash
npx skills add <rc8s2242sr-cmd>/writing-order
```

### 5. 网页端对话模型（Gemini / ChatGPT / Claude 等）

直接上传本仓库根目录下的 `SKILL.md`，或将其粘贴至系统指令（System Prompt / Custom Instructions / Gem / Project Instructions）即可生效。

---

## 许可证

[MIT License](./LICENSE)
