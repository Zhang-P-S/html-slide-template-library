# html-slide-template-library

Pick the right slide style before you generate the deck.

`html-slide-template-library` is a Codex skill for people who already know the real problem with slide generation:

the hard part is often not writing the HTML, but choosing **what kind of deck it should become**.

This skill gives Codex a stable template-routing layer, so it can stop guessing with vague labels like “modern”, “professional”, or “clean”, and instead recommend a presentation direction that actually fits the task.

**Language / 语言**

[English](#english) | [简体中文](#zh-cn)

---

<a id="english"></a>

## English

Switch language: [简体中文](#zh-cn)

## What This Skill Does

Use this skill when you want Codex to choose the **right presentation family** before generating slides.

Instead of jumping straight into a random deck style, Codex will:

- understand what kind of presentation you are making
- shortlist 3 to 6 fitting template directions
- explain the tradeoffs between them
- identify the safest default
- hand the chosen direction to your slide-generation workflow

In practice, this means you get a better answer to:

- “What kind of deck should this be?”
- “Which style actually fits this topic?”
- “What should the final presentation feel like on screen?”

## Why It Exists

Most slide workflows fail too early.

They either:

- start generating before the visual direction is clear
- overfit to a generic business template
- confuse mood words with usable design decisions
- ignore the difference between a policy deck, a theory talk, and a technical roadshow

This skill exists to solve that layer first.

## What You Get

This skill routes tasks into six stable presentation families:

1. Academic Defense
2. Policy and Governance
3. Engineering and Technology
4. Theory and Coursework
5. Innovation Roadshow
6. Community Portfolio

Each family contains multiple sub-directions, so Codex can recommend not just one “theme”, but a meaningful set of options with clear use cases.

## What Using It Feels Like

You ask for a deck.

Codex does not immediately start writing HTML.

It first responds like a strong design partner:

1. It identifies the kind of presentation you are making.
2. It recommends several template directions from this library.
3. It explains each one in plain language:
   - what it is
   - why it fits
   - what the final deck will look like
   - what the tradeoff is
4. You choose one, mix two, or let Codex pick the safest option.
5. Only then does the actual slide generation begin.

## Example Prompts

You can invoke it explicitly or let Codex trigger it naturally.

Examples:

- `Use $html-slide-template-library to recommend the best direction for a reinforcement learning lecture deck.`
- `I need a slide style for a scholarship defense. Show me a few options first.`
- `Don’t generate yet. First help me choose the right template family for this topic.`
- `Use my template library, not a generic startup deck.`
- `This is a policy interpretation talk. What should the deck look like?`

## The Six Families

### 1. Academic Defense

Best when the deck needs evidence, order, scores, certificates, screenshots, charts, or a formal academic tone.

### 2. Policy and Governance

Best when the deck needs institutional structure, public-briefing clarity, political or policy framing, or a stronger official tone.

### 3. Engineering and Technology

Best when the deck needs systems, architecture, experiments, process logic, technical explanation, or high-density engineering content.

### 4. Theory and Coursework

Best when the deck is concept-heavy, argumentative, text-led, or built around discussion, interpretation, and logic.

### 5. Innovation Roadshow

Best when the deck needs momentum, project framing, launch energy, highlights, outcomes, and a stronger pitch rhythm.

### 6. Community Portfolio

Best when the deck is catalog-like, character-driven, fandom-oriented, collection-based, or meant to feel browseable and social.

## Preview Boards

These six boards represent the top-level families inside the skill.

### Academic Defense

![Academic defense preview](assets/previews/01-academic-defense-preview.png)

### Policy and Governance

![Policy and governance preview](assets/previews/02-policy-and-governance-preview.png)

### Engineering and Technology

![Engineering and technology preview](assets/previews/03-engineering-and-technology-preview.png)

### Theory and Coursework

![Theory and coursework preview](assets/previews/04-theory-and-coursework-preview.png)

### Innovation Roadshow

![Innovation roadshow preview](assets/previews/05-innovation-roadshow-preview.png)

### Community Portfolio

![Community portfolio preview](assets/previews/06-community-portfolio-preview.png)

## What Makes This Different

This is not a template dump.

It is not a folder of random HTML examples.

It is a reusable selection layer that teaches Codex how to make better slide decisions before generation begins.

That makes it especially useful if you:

- generate many decks across different scenarios
- care about consistency
- want Codex to recommend styles instead of hallucinating them
- want a personal slide system instead of generic defaults

## Repository Structure

The repository is intentionally small:

- `SKILL.md`: trigger rules and workflow
- `references/`: the actual routing logic and family definitions
- `assets/previews/`: visual preview boards for the six families
- `agents/openai.yaml`: UI metadata

If you want to use it, place the repository in your Codex skills folder and invoke `$html-slide-template-library`.

## Best Paired With

This skill is strongest when paired with an actual generator.

Typical pairing:

- use this skill to choose the direction
- use a generation workflow such as `frontend-slides` to build the deck

In other words:

- this skill decides **what the deck should be**
- your generator decides **how to render it**

## License

MIT License. See [LICENSE](LICENSE).

Back to top: [English](#english) | [简体中文](#zh-cn)

---

<a id="zh-cn"></a>

## 简体中文

切换语言：[English](#english)

## 这个 skill 是干什么的

`html-slide-template-library` 是一个专门给 Codex 用的 **模板选择 skill**。

它不是直接帮你生成一套 HTML，而是先解决一个更关键的问题：

**这份内容，应该做成什么样的 deck？**

很多 slide 生成效果差，不是因为不会写 HTML，而是因为一开始就选错了方向。

这个 skill 的作用，就是在真正开始生成之前，先帮你把模板路线选对。

## 它能帮你得到什么

用这个 skill 之后，Codex 不会一上来就随便开做。

它会先：

- 判断你的内容属于哪一类汇报
- 从这套模板体系里推荐 3 到 6 个方向
- 说明每个方向为什么合适
- 告诉你最终画面会长成什么样
- 标出一个最稳妥的默认项
- 等你确认之后，再把这个方向交给后续生成流程

它解决的是“先选模板，再生成”的问题。

## 为什么值得用

因为大多数 slide 工作流都太早开始“出图”了。

常见问题是：

- 还没想清楚是什么类型的 deck，就已经开始生成
- 动不动就掉进泛商业模板
- 只会说“现代”“专业”“简洁”，但说不清具体长什么样
- 分不清技术讲解、政策汇报、理论课程、作品集本来就该是完全不同的视觉逻辑

这个 skill 就是专门把这一层先补上。

## 六大模板类

这套 skill 会把任务统一路由到六大类：

1. 学术答辩类
2. 党政政策类
3. 工程技术类
4. 理论课程类
5. 创新路演类
6. 社群作品集类

每一类下面还有更细的子方向，所以它给你的不是一句空泛的“风格建议”，而是一组真正可选的模板路线。

## 实际使用时会发生什么

你给出一个主题。

Codex 不会马上写 HTML。

它会先像一个靠谱的设计搭档一样工作：

1. 先判断这是什么类型的汇报。
2. 再从这套模板库里推荐几个方向。
3. 用普通人能看懂的话解释每个方向：
   - 它是什么
   - 为什么适合
   - 最终页面会是什么样
   - 代价或风险是什么
4. 你可以选一个，或者主副两个混合，也可以直接让 Codex 选最稳妥的。
5. 选定之后，再进入真正的 slide 生成。

## 适合怎么问

下面这些问法都很适合触发这个 skill：

- `用 $html-slide-template-library 先帮我选一套适合强化学习课程报告的方向。`
- `先别生成，先帮我挑模板。`
- `我要做奖学金答辩，先给我几个合适的 deck 路线。`
- `这次不要泛商业风，用我这套模板系统来选。`
- `这是政策解读汇报，应该长成什么样？`

## 六类分别适合什么

### 1. 学术答辩类

适合证据、成绩、证书、图表、截图很多的内容，也适合正式、稳妥、答辩感强的汇报。

### 2. 党政政策类

适合政策解读、规划部署、制度表达、现代治理、公共汇报这类内容。

### 3. 工程技术类

适合系统架构、实验结果、原理讲解、技术综述、项目方案、工程报告。

### 4. 理论课程类

适合课程展示、概念论证、课堂讨论、哲学社科议题、文本分析这类内容。

### 5. 创新路演类

适合科创比赛、项目发布、成果展示、产品叙事、亮点梳理、路演节奏更强的 deck。

### 6. 社群作品集类

适合图鉴、收藏、角色展示、社群活动、目录化内容、作品集和 fandom 场景。

## 预览总览

下面这 6 张预览板代表了这个 skill 的六大顶层方向。

### 学术答辩类

![学术答辩类预览](assets/previews/01-academic-defense-preview.png)

### 党政政策类

![党政政策类预览](assets/previews/02-policy-and-governance-preview.png)

### 工程技术类

![工程技术类预览](assets/previews/03-engineering-and-technology-preview.png)

### 理论课程类

![理论课程类预览](assets/previews/04-theory-and-coursework-preview.png)

### 创新路演类

![创新路演类预览](assets/previews/05-innovation-roadshow-preview.png)

### 社群作品集类

![社群作品集类预览](assets/previews/06-community-portfolio-preview.png)

## 它和“模板仓库”有什么不同

它不是一个模板堆。

它也不是几个示例页面的集合。

它更像是一个让 Codex 先学会“怎么选模板”的路由层。

所以如果你：

- 经常做不同场景的 deck
- 不想每次都从零判断风格
- 希望 Codex 能先推荐而不是乱猜
- 想把自己的 slide 系统沉淀成一套稳定方法

那这个 skill 就是有价值的。

## 仓库里有什么

仓库结构本身很克制：

- `SKILL.md`：定义这个 skill 何时触发、如何工作
- `references/`：六大类与具体路由规则
- `assets/previews/`：六类总览预览板
- `agents/openai.yaml`：界面元数据

如果你要用它，把仓库放进 Codex 的 skills 目录后，直接用 `$html-slide-template-library` 调用即可。

## 最适合和谁搭配

这个 skill 最适合和真正负责生成的工作流搭配使用。

最自然的组合方式是：

- 先用这个 skill 选方向
- 再用 `frontend-slides` 之类的生成流程做成最终 deck

也就是说：

- 这个 skill 负责决定 **做成什么样**
- 生成器负责决定 **怎么把它做出来**

## 许可证

采用 MIT License，详见 [LICENSE](LICENSE)。

返回顶部：[English](#english) | [简体中文](#zh-cn)
