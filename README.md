# 开源航天技术共享生态与深空仿真平台研究

> 借鉴计算机发展史构建开源航天技术共享生态与深空仿真平台的路径研究

本仓库承载该论文的写作过程与成果。论文计划投稿 arXiv。

---

# Pathways to Building an Open-Source Aerospace Technology Sharing Ecosystem and Deep-Space Simulation Platform Informed by the History of Computer Development

> This repository hosts the writing process and deliverables of the paper above. The paper is planned for arXiv submission.

## 项目结构 / Repository Structure

```
OpenSourceAerospaceEcosystem/
├── README.md                          # 项目说明（本文件）/ Project overview (this file)
├── docs/
│   ├── 01_abstract_keywords.md        # 摘要 + 关键词（已定稿）/ Abstract + keywords (finalized)
│   ├── 02_outline.md                  # 论文大纲（已定稿）/ Outline (finalized)
│   ├── 03_concept_mapping_table.md    # 概念映射表 / Concept mapping table
│   └── chapters/
│       ├── 01_introduction.md         # 第 1 章 引言 / Ch.1 Introduction
│       ├── 02_literature_review.md    # 第 2 章 文献综述 / Ch.2 Literature Review
│       ├── 03_computer_history_lessons.md # 第 3 章 计算机发展史 / Ch.3 Lessons from Computer History
│       ├── 04_ecosystem_architecture.md   # 第 4 章 生态架构 / Ch.4 Ecosystem Architecture
│       ├── 05_simulation_platform.md      # 第 5 章 仿真平台 / Ch.5 Simulation Platform
│       ├── 06_security_governance.md      # 第 6 章 安全治理 / Ch.6 Security & Governance
│       ├── 07_business_model.md           # 第 7 章 商业模式 / Ch.7 Business Model
│       ├── 08_cases_feasibility.md        # 第 8 章 案例分析 / Ch.8 Cases & Feasibility
│       └── 09_conclusion_references.md    # 第 9 章 结论 + 参考文献 / Ch.9 Conclusion + References
└── paper/
    ├── full_paper.md                  # 完整合成稿 / Full paper (Markdown, Chinese)
    ├── main_zh.tex                    # 中文 LaTeX（xelatex 编译）/ Chinese LaTeX (xelatex)
    ├── main_en.tex                    # 英文 LaTeX（pdflatex 编译）/ English LaTeX (pdflatex)
    ├── main_zh.pdf                    # 中文 PDF（19 页）/ Chinese PDF (19 pp.)
    ├── main_en.pdf                    # 英文 PDF（22 页）/ English PDF (22 pp.)
    ├── VERSIONS.md                    # 版本清单 / Version log
    └── versions/
        ├── v1_sidewaystable/          # v1: sidewaystable 旋转表格 / rotated tables
        ├── v2_pdflscape_blank/        # v2: pdflscape 空白页 bug / blank-page bug
        └── v3_pdflscape_small/        # v3: pdflscape + small / small-font tables
```

> **版本规则 / Versioning:** 最新版不带版本号放在 `paper/` 根目录；每次迭代把旧版归档到 `paper/versions/vN_名称/` 并登记到 `VERSIONS.md`。
>
> The latest version lives in `paper/` without a version suffix. Each iteration archives the previous version to `paper/versions/vN_name/` and updates `VERSIONS.md`.

## 作者 / Author

- **Y. X. Tan**（陈 勇 勋），E-mail: yxtan5022@gmail.com
- Affiliation: TBD

## 核心观点 / Core Thesis

以计算机产业数十年的演进史（开源协作、技术标准化、模块化与中间件、仿真虚拟化、商业开源闭环）为参照系，提出构建开源航天技术共享生态与深空仿真平台的整体方案，主要包括：

Taking the decades-long evolution of the computer industry (open-source collaboration, standardization, modular middleware, simulation virtualization, and commercial open-source feedback loops) as a reference frame, this paper proposes an overall scheme for building an open-source aerospace technology sharing ecosystem and a deep-space simulation platform, including:

- **微服务化航天器架构** 与航天器通用操作系统（Space OS）
  *Microservice-based spacecraft architecture* and a universal spacecraft operating system (Space OS)
- **DevSpaceOps**：云端数字孪生驱动的高可靠研发交付流程
  *DevSpaceOps*: cloud-digital-twin-driven high-reliability R&D delivery pipeline
- **航天组件与算法包注册表（Space Package Registry）**，类比 npm / PyPI
  *Space Package Registry* (analogous to npm / PyPI)
- **零信任与拜占庭容错** 保障开源贡献下的航天核心安全基线（Safe Mode）
  *Zero-trust architecture and Byzantine fault tolerance* to safeguard the aerospace safety baseline
- **双重许可与商业开源** 模式解决开源航天资金来源
  *Dual-licensing and commercial open-source* model to solve funding sustainability

## 学术层次 / Academic Level

不按学段定位，以学术严谨性为第一标准；方法为历史比较 + 案例分析 + 概念映射 + 统计数据分析。

Not positioned by educational level; academic rigor is the primary standard. Methods: historical comparison, case analysis, concept mapping, and statistical data analysis.

## 进度 / Progress

- [x] 摘要 + 关键词 / Abstract + keywords
- [x] 论文大纲 / Outline
- [x] 概念映射表 / Concept mapping table
- [x] 第 1 章 引言 / Ch.1 Introduction
- [x] 第 2 章 文献综述与理论基础 / Ch.2 Literature Review
- [x] 第 3 章 计算机发展史经验提炼（含量化证据与数据表）/ Ch.3 Lessons from Computer History (with quantitative evidence)
- [x] 第 4 章 开源航天生态总体架构 / Ch.4 Ecosystem Architecture
- [x] 第 5 章 深空仿真平台构建路径 / Ch.5 Simulation Platform
- [x] 第 6 章 安全、信任与治理机制 / Ch.6 Security & Governance
- [x] 第 7 章 商业模式与可持续发展 / Ch.7 Business Model
- [x] 第 8 章 案例分析与可行性论证 / Ch.8 Cases & Feasibility
- [x] 第 9 章 结论与展望 + 参考文献（28 条，全部真实）/ Ch.9 Conclusion + References (28 entries, all real)
- [x] 完整合成稿 / Full paper (paper/full_paper.md)
- [x] 量化数据（GitHub Octoverse 2024、Sonatype 2024、LWN 2023、Kulu IAC 2024、SIA SSIR 2024）
- [x] 排版重构 / LaTeX layout (geometry, titlesec, fancyhdr, landscape tables)
- [x] 英文版翻译与编译 / English translation & compilation (main_en.pdf, 22 pp.)
- [x] 中文版编译 / Chinese compilation (main_zh.pdf, 19 pp.)
- [x] 表格修复 v4：landscape 内 tabularx 宽度 textheight→textwidth / Table fix v4: tabularx width textheight→textwidth
- [x] 版本化归档 / Versioned archiving (VERSIONS.md + versions/)
- [ ] 确认单位信息（tex 中 Affiliation: TBD）/ Confirm affiliation (currently TBD)
- [ ] arXiv 投稿 / arXiv submission (main_en.tex + bibliography)
