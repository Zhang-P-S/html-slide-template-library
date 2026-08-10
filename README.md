# html-slide-template-library

Standalone HTML slide templates for reusable presentation scenarios.

**Language / 语言**

[English](#english) | [简体中文](#zh-cn)

---

<a id="english"></a>

## English

Switch language: [简体中文](#zh-cn)

### Overview

`html-slide-template-library` is a clean, standalone repository of shareable HTML slide templates distilled from my own presentation work.

It focuses on six recurring scenarios:

- Academic defense
- Policy briefing
- Engineering and technical explanation
- Theory and classroom discussion
- Innovation roadshow
- Community and collectible showcase

All templates are plain HTML bundles with local assets. There is no build step, no framework dependency, and no bundled third-party skill code.

### What This Repository Is

This repository is intended to be:

- a personal HTML slide template library
- a reusable base for future slide-generation workflows
- a clean open-source artifact that can be shared independently

This repository is not:

- a dump of Codex system skills
- a mirror of third-party template packs
- a mixed workspace archive
- a collection of temporary export artifacts

### Included Templates

#### Core template scenarios

| Scenario | Directory | Notes |
| --- | --- | --- |
| Academic defense | `templates/academic-defense-qwen3/` | Evidence-first, blue-white, paper-presentation style |
| Policy briefing | `templates/policy-plan15/` | Red-gold institutional briefing style |
| Engineering / technical | `templates/engineering-quadcopter/` | Structured grid, modular technical explanation |
| Theory / classroom | `templates/theory-marx-ai/` | Editorial black-white-light discussion style |
| Innovation roadshow | `templates/innovation-aerospace/` | Capability-matrix storytelling and pitch framing |
| Community / catalog | `templates/community-cat-catalog/` | Card-based collectible and showcase direction |

#### Additional example

| Example | Directory | Notes |
| --- | --- | --- |
| Community adaptation example | `examples/community-eevee-pokedex/` | A Pokemon Pokedex adaptation based on the community showcase direction |

### Repository Structure

```text
html-slide-template-library/
|- templates/
|  |- academic-defense-qwen3/
|  |  |- index.html
|  |  `- assets/
|  |- policy-plan15/
|  |  |- index.html
|  |  `- assets/
|  |- engineering-quadcopter/
|  |  |- index.html
|  |  `- assets/
|  |- theory-marx-ai/
|  |  |- index.html
|  |  `- assets/
|  |- innovation-aerospace/
|  |  |- index.html
|  |  `- assets/
|  `- community-cat-catalog/
|     |- index.html
|     `- assets/
|- examples/
|  `- community-eevee-pokedex/
|     |- index.html
|     `- assets/
|- assets/
|  `- readme/
|     `- screenshots used in this README
|- README.md
`- LICENSE
```

### Routing Guide

Choose a starting template by content type:

| If the content is mainly... | Start here |
| --- | --- |
| research findings, evidence walls, method/result explanation | `academic-defense-qwen3` |
| policy interpretation, state planning, institutional public briefing | `policy-plan15` |
| system structure, mechanism explanation, engineering principle | `engineering-quadcopter` |
| concept-heavy, argumentative, classroom or discussion-led | `theory-marx-ai` |
| pitch-like storytelling, capability framing, innovation narrative | `innovation-aerospace` |
| catalog, collection, community showcase, fandom-style display | `community-cat-catalog` |

### Example Gallery

The following screenshots were renamed from raw workspace exports to stable, content-based filenames.

#### 1. Academic defense

`assets/readme/01-academic-defense-reranker-ablation.png`

![Academic defense example](assets/readme/01-academic-defense-reranker-ablation.png)

#### 2. Policy briefing

`assets/readme/02-policy-plan15-cover.png`

![Policy briefing example](assets/readme/02-policy-plan15-cover.png)

#### 3. Engineering / technical explanation

`assets/readme/03-engineering-quadcopter-advantage-grid.png`

![Engineering template example](assets/readme/03-engineering-quadcopter-advantage-grid.png)

#### 4. Theory / classroom discussion

`assets/readme/04-theory-marx-labor-process.png`

![Theory discussion example](assets/readme/04-theory-marx-labor-process.png)

#### 5. Innovation roadshow

`assets/readme/05-innovation-aerospace-capability-matrix.png`

![Innovation roadshow example](assets/readme/05-innovation-aerospace-capability-matrix.png)

#### 6. Community adaptation example

`assets/readme/06-community-eevee-eeveelutions.png`

![Community adaptation example](assets/readme/06-community-eevee-eeveelutions.png)

### How To Use

#### Open a template directly

Each template is self-contained. Open `index.html` in a browser:

- `templates/academic-defense-qwen3/index.html`
- `templates/policy-plan15/index.html`
- `templates/engineering-quadcopter/index.html`
- `templates/theory-marx-ai/index.html`
- `templates/innovation-aerospace/index.html`
- `templates/community-cat-catalog/index.html`

#### Reuse as a starting point

Recommended workflow:

1. Pick the closest scenario directory.
2. Duplicate the whole folder.
3. Replace text and local assets inside that duplicated folder.
4. Keep relative asset paths unchanged when possible.
5. Export screenshots or publish the folder directly.

### Design Principles

These templates follow a few stable constraints:

- self-contained HTML first
- local assets over remote dependencies
- scenario routing before visual styling
- structured layouts that survive real presentation density
- reusable visual language rather than one-off decoration

### Boundary Statement

This repository intentionally excludes:

- Codex system skill files
- external bundled skill definitions
- unrelated workspace artifacts
- temporary PPT export folders not required by the HTML templates
- generated files whose only purpose was local testing

### License

MIT License. See [LICENSE](LICENSE).

Back to top: [English](#english) | [简体中文](#zh-cn)

---

<a id="zh-cn"></a>

## 简体中文

切换语言：[English](#english)

### 仓库说明

`html-slide-template-library` 是一个独立的 HTML 幻灯片模板仓库，沉淀自我个人的演示文稿实践。

它聚焦六类高频场景：

- 学术答辩
- 党政政策解读
- 工程技术讲解
- 理论课程讨论
- 创新路演展示
- 社群与收藏型展示

所有模板都采用纯 HTML 加本地静态资源的方式组织，不依赖构建流程，不依赖前端框架，也不包含第三方 skill 代码。

### 这个仓库是什么

这个仓库的定位是：

- 个人可复用的 HTML 幻灯片模板库
- 后续生成式幻灯片工作流的基础资产
- 可以独立分享的干净开源仓库

这个仓库不包含：

- Codex 系统 skill 内容
- 第三方模板包镜像
- 混杂的工作区归档文件
- 临时导出产物堆积

### 模板内容

#### 六类核心模板

| 场景 | 目录 | 说明 |
| --- | --- | --- |
| 学术答辩类 | `templates/academic-defense-qwen3/` | 偏证据墙与论文汇报的蓝白风格 |
| 党政政策类 | `templates/policy-plan15/` | 红金色制度化政策汇报风格 |
| 工程技术类 | `templates/engineering-quadcopter/` | 结构化网格、适合系统与原理讲解 |
| 理论课程类 | `templates/theory-marx-ai/` | 黑白浅色编辑感，适合讨论与论述 |
| 创新路演类 | `templates/innovation-aerospace/` | 强叙事和能力矩阵表达的路演风格 |
| 社群作品集类 | `templates/community-cat-catalog/` | 卡片式收藏展示与兴趣社群表达 |

#### 附加示例

| 示例 | 目录 | 说明 |
| --- | --- | --- |
| 社群方向改编示例 | `examples/community-eevee-pokedex/` | 基于社群展示方向制作的伊布图鉴示例 |

### 仓库结构

```text
html-slide-template-library/
|- templates/
|  |- academic-defense-qwen3/
|  |  |- index.html
|  |  `- assets/
|  |- policy-plan15/
|  |  |- index.html
|  |  `- assets/
|  |- engineering-quadcopter/
|  |  |- index.html
|  |  `- assets/
|  |- theory-marx-ai/
|  |  |- index.html
|  |  `- assets/
|  |- innovation-aerospace/
|  |  |- index.html
|  |  `- assets/
|  `- community-cat-catalog/
|     |- index.html
|     `- assets/
|- examples/
|  `- community-eevee-pokedex/
|     |- index.html
|     `- assets/
|- assets/
|  `- readme/
|     `- 本 README 使用的示例截图
|- README.md
`- LICENSE
```

### 选型指引

如果你的内容更接近下面这些表达目标，可以直接从对应模板开始：

| 如果内容主要是... | 建议起点 |
| --- | --- |
| 研究结论、实验结果、方法与对比说明 | `academic-defense-qwen3` |
| 政策解读、规划部署、制度型公开汇报 | `policy-plan15` |
| 系统结构、机制原理、工程技术拆解 | `engineering-quadcopter` |
| 概念论述、课堂讨论、理论密度较高内容 | `theory-marx-ai` |
| 路演叙事、能力表达、创新项目包装 | `innovation-aerospace` |
| 图鉴、收藏、角色展示、社群兴趣内容 | `community-cat-catalog` |

### 示例画廊

下面这些截图来自工作区原始导出图，已经按内容重新命名，方便在 README 中稳定引用。

#### 1. 学术答辩类

`assets/readme/01-academic-defense-reranker-ablation.png`

![学术答辩示例](assets/readme/01-academic-defense-reranker-ablation.png)

#### 2. 党政政策类

`assets/readme/02-policy-plan15-cover.png`

![党政政策示例](assets/readme/02-policy-plan15-cover.png)

#### 3. 工程技术类

`assets/readme/03-engineering-quadcopter-advantage-grid.png`

![工程技术示例](assets/readme/03-engineering-quadcopter-advantage-grid.png)

#### 4. 理论课程类

`assets/readme/04-theory-marx-labor-process.png`

![理论课程示例](assets/readme/04-theory-marx-labor-process.png)

#### 5. 创新路演类

`assets/readme/05-innovation-aerospace-capability-matrix.png`

![创新路演示例](assets/readme/05-innovation-aerospace-capability-matrix.png)

#### 6. 社群改编示例

`assets/readme/06-community-eevee-eeveelutions.png`

![社群改编示例](assets/readme/06-community-eevee-eeveelutions.png)

### 使用方式

#### 直接打开模板

每套模板都可以独立使用，直接在浏览器中打开对应的 `index.html` 即可：

- `templates/academic-defense-qwen3/index.html`
- `templates/policy-plan15/index.html`
- `templates/engineering-quadcopter/index.html`
- `templates/theory-marx-ai/index.html`
- `templates/innovation-aerospace/index.html`
- `templates/community-cat-catalog/index.html`

#### 作为起点进行复用

推荐流程：

1. 先选最接近内容场景的模板目录。
2. 整个复制该目录。
3. 在复制后的目录中替换文本和本地图片资源。
4. 尽量保持相对路径结构不变。
5. 最后直接发布文件夹，或导出截图继续使用。

### 设计原则

这些模板遵循几条稳定原则：

- 以自包含 HTML 为优先
- 优先使用本地静态资源
- 先按场景分流，再做视觉风格选择
- 排版结构要能承受真实信息密度
- 追求可复用的视觉语言，而不是一次性装饰

### 边界说明

这个仓库明确排除了以下内容：

- Codex 系统 skill 文件
- 外部打包进来的 skill 定义
- 与本模板库无关的工作区文件
- HTML 模板不需要的临时 PPT 导出文件夹
- 仅用于本地测试的生成文件

### 许可证

采用 MIT License，详见 [LICENSE](LICENSE)。

返回顶部：[English](#english) | [简体中文](#zh-cn)
