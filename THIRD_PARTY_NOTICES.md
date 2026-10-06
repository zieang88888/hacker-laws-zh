# 第三方声明与署名（THIRD_PARTY_NOTICES）

本仓库 **hacker-laws-zh** 是对以下开源项目的**中文导读与全量索引**，特此如实署名。

## 源项目

- **项目名**：hacker-laws
- **仓库地址**：<https://github.com/dwmkerr/hacker-laws>
- **默认分支**：`main`
- **原作者 / 维护者**：Dave Kerr（GitHub：[`@dwmkerr`](https://github.com/dwmkerr)）
- **贡献者**：源 README 的 `Contributors` 章节列出的全体贡献者（含文档贡献与各语言翻译贡献者）。

## 许可声明（重要）

- 源仓库 `dwmkerr/hacker-laws` 的许可经 **2026-10-06 GitHub API 实测**：
  - `license.spdx_id` = **`CC-BY-SA-4.0`**（**知识共享 署名-相同方式共享 4.0 国际许可协议**）。
  - **注意：源许可并非 MIT**。任何关于本项目许可的转述，均以本次在线实测为准。
- 依据"相同方式共享（ShareAlike）"要求，本仓库在源作品之上整理，亦采用 **[CC BY-SA 4.0](./LICENSE)** 发布。

## 实测数据与统计口径（核实日期：2026-10-06）

| 项目 | 数值 | 来源 / 方法 |
| --- | --- | --- |
| 源仓 Star 数 | **27,306** | GitHub API `repos/dwmkerr/hacker-laws` 字段 `stargazers_count` 实测 |
| `## ` 章节数 | **7** | 对源 README 正文逐段统计 `## ` 二级标题：Introduction、Laws、Principles、Reading List、Online Resources、Podcast、Contributors（排除顶部 TOC 列表） |
| 定律条目总数 | **69** | 对源 README 正文统计 `### ` 三级标题：Laws 节 **48** 条 + Principles 节 **21** 条 |
| 其中：Laws 节 | **48** 条 | 以正文 `### ` 标题为准（含页面 TOC 漏列的 `The Second-System Effect`） |
| 其中：Principles 节 | **21** 条 | 以正文 `### ` 标题为准（含作为伞形条目的 `SOLID`） |

**统计方法说明**：
1. 通过 `https://raw.githubusercontent.com/dwmkerr/hacker-laws/main/README.md` 拉取源 README 全文（约 29,088 字符），逐段读完。
2. 分节数以 Markdown `## ` 二级标题计数，**不使用**页面顶部自动生成的目录（TOC），因为 TOC 与正文存在偏差。
3. 条目数以正文实际出现的 `### ` 三级标题逐条计数；TOC 漏列的条目（如 The Second-System Effect）以正文为准补入。
4. 5 个辅助章节（Introduction / Reading List / Online Resources / Podcast / Contributors）不含 `### ` 定律条目，条目数为 0，不计入 69 条。

## 本仓库的边界

- 本仓库**仅做中文导读与索引**：提供每条定律的中文译名、一句话核心、以及指向源 README 对应小节的锚点链接。
- 本仓库**不收录源文正文**（不复制源 README 的详细解释、示例与引文）。
- 所有详细解释、案例、延伸阅读，请通过索引中的锚点链接访问源仓库原文。

## 署名要求

转载或再分发本仓库内容时，请：
1. 保留对原作者 **Dave Kerr（`@dwmkerr`）** 及源项目 [`dwmkerr/hacker-laws`](https://github.com/dwmkerr/hacker-laws) 的署名；
2. 保留本许可声明；
3. 以相同方式（CC BY-SA 4.0）共享衍生作品。
