# 开源航天技术共享生态与深空仿真平台研究

> 借鉴计算机发展史构建开源航天技术共享生态与深空仿真平台的路径研究

本仓库承载该论文的写作过程与成果。论文计划投稿 arXiv。

## 项目结构

```
OpenSourceAerospaceEcosystem/
├── README.md                          # 项目说明（本文件）
├── docs/
│   ├── 01_abstract_keywords.md        # 摘要 + 关键词（已定稿）
│   ├── 02_outline.md                  # 论文大纲（已定稿）
│   ├── 03_concept_mapping_table.md    # 概念映射表（计算机原型 → 开源航天新形态）
│   └── chapters/
│       ├── 01_introduction.md         # 第 1 章 引言
│       ├── 02_literature_review.md    # 第 2 章 文献综述与理论基础
│       ├── 03_computer_history_lessons.md # 第 3 章 计算机发展史经验提炼
│       ├── 04_ecosystem_architecture.md   # 第 4 章 开源航天生态总体架构
│       ├── 05_simulation_platform.md      # 第 5 章 深空仿真平台构建路径
│       ├── 06_security_governance.md      # 第 6 章 安全、信任与治理机制
│       ├── 07_business_model.md           # 第 7 章 商业模式与可持续发展
│       ├── 08_cases_feasibility.md        # 第 8 章 案例分析与可行性论证
│       └── 09_conclusion_references.md    # 第 9 章 结论与展望 + 参考文献
└── paper/
    ├── full_paper.md                  # 完整论文合成稿（Markdown，中文）
    ├── main_zh.tex                    # 中文版 LaTeX（xelatex + ctex 编译）
    ├── main_en.tex                    # 英文版 LaTeX（arXiv 投稿版，pdflatex 编译）
    ├── main_zh.pdf                    # 中文版 PDF（18 页）
    └── main_en.pdf                    # 英文版 PDF（21 页）
```

## 作者

- **Y. X. Tan**（陈 勇 勋），E-mail：yxtan5022@gmail.com
- 单位：待补充

## 核心观点

以计算机产业数十年的演进史（开源协作、技术标准化、模块化与中间件、仿真虚拟化、商业开源闭环）为参照系，提出构建开源航天技术共享生态与深空仿真平台的整体方案，主要包括：

- **微服务化航天器架构** 与航天器通用操作系统（Space OS）
- **DevSpaceOps**：云端数字孪生驱动的高可靠研发交付流程
- **航天组件与算法包注册表（Space Package Registry）**，类比 npm / PyPI
- **零信任与拜占庭容错** 保障开源贡献下的航天核心安全基线（Safe Mode）
- **双重许可与商业开源** 模式解决开源航天资金来源

## 学术层次

本科/硕士课程论文，方法以历史比较 + 案例分析 + 概念映射 + 统计数据分析为主。

## 进度

- [x] 摘要 + 关键词
- [x] 论文大纲
- [x] 概念映射表
- [x] 第 1 章 引言
- [x] 第 2 章 文献综述与理论基础
- [x] 第 3 章 计算机发展史经验提炼（含 3.6 量化证据与数据表）
- [x] 第 4 章 开源航天生态总体架构
- [x] 第 5 章 深空仿真平台构建路径
- [x] 第 6 章 安全、信任与治理机制
- [x] 第 7 章 商业模式与可持续发展
- [x] 第 8 章 案例分析与可行性论证（并入 NASA/CubeSat/SIA 数据）
- [x] 第 9 章 结论与展望 + 参考文献
- [x] 完整论文合成稿（paper/full_paper.md）
- [x] 参考文献补全（28 条，全部真实；[23] 软件定义卫星中文文献，[24]-[28] GitHub/npm/Linux/CubeSat/SIA 数据来源）
- [x] 量化数据章节（GitHub Octoverse 2024、Sonatype 2024、LWN 2023、Kulu IAC 2024、SIA SSIR 2024）
- [x] 排版重构（几何页面版式、标题字体样式、题头摘要区、横排表格）
- [x] 英文版翻译（paper/main_en.tex，arXiv 版）
- [x] 中文版 PDF 重编译（main_zh.pdf，18 页）
- [x] 英文版 PDF 重编译（main_en.pdf，21 页）
- [ ] 确认单位信息（tex 中为"单位：待补充"占位）
- [ ] arXiv 投稿（提交 main_en.tex 及引文文件）
