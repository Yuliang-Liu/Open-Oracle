# 预印本与待定出版状态追踪表

维护流程见 [MAINTENANCE.md](../MAINTENANCE.md)。按 arXiv ID 或 DOI 去重；同一论文在多个分类或 README 中的出现位置需要一起更新。

## 初始化说明

- 建表日期：2026-09-11。来源：仓库提交 `f4518392e92e467157f06cd137fe363f9ca4d1e9` 的 PAPERS.md。
- 本表仅提取 venue 列为 `arXiv YYYY` 的条目，未联网核验，核验日期为空；“原索引标注”不代表当前真实发表状态。
- 共 20 篇唯一论文；首次执行仍须扫描 README 独有条目、其他预印本平台以及已有 venue 但缺少官方证据的条目，并加入需要跟踪的候选。
- 2026-10-13 复核后：18 篇活跃（16 篇 arXiv、1 篇漏跟踪的 SSRN、1 篇已提前上线待最终版本的论文），12 篇归档。UniCalli 与 Beyond aggregate metrics 已更新为正式发表；FROD 仍仅有作者录用声明。初始 20 篇的历史身份全部保留。
- PD-OBS 的两行分别指数据集和方法；以同一个 arXiv ID 跟踪。Chronicles-OCR 也跨分类出现；重复次数只统计 PAPERS.md。
- 本表按 ID 排序方便检查旧论文；实际每周检查全部活跃条目。证据列可链接至本周记录中的详细核验依据。

## 活跃条目

| 稳定 ID | 论文 / 项目（当前索引名称） | 原索引标注 | PAPERS 行数 | 最新核验日期 / 版本 | 当前结论 | 证据 / 下次动作 |
| --- | --- | --- | --- | --- | --- | --- |
| [2401.12467](https://arxiv.org/abs/2401.12467) | An Open Dataset for the Evolution of Oracle Bone Characters: EVOBC | arXiv 2024 | 1 | 2026-10-13 / v2 (2024-02-13) | 本轮未发现可核对的新录用或正式出版证据 | arXiv 元数据、Crossref/OpenAlex 标题检索及 OpenReview 检索已查；未绑定不匹配结果；[本周证据](weekly/2026-10-13.md#2-旧论文状态核验)；下周继续 |
| [2409.15893](https://arxiv.org/abs/2409.15893) | Unsupervised Attention Regularization Based Domain Adaptation for Oracle Character Recognition | arXiv 2024 | 1 | 2026-10-13 / v1 (2024-09-24) | 本轮未发现可核对的新录用或正式出版证据 | arXiv 元数据、Crossref/OpenAlex 标题检索及 OpenReview 检索已查；未绑定不匹配结果；[本周证据](weekly/2026-10-13.md#2-旧论文状态核验)；下周继续 |
| [2411.17837](https://arxiv.org/abs/2411.17837) | OracleSage: Towards Unified Visual-Linguistic Understanding of Oracle Bone Scripts through Cross-Modal Knowledge Fusion | arXiv 2024 | 1 | 2026-10-13 / v1 (2024-11-26) | 本轮未发现可核对的新录用或正式出版证据 | arXiv 元数据、Crossref/OpenAlex 标题检索及 OpenReview 检索已查；未绑定不匹配结果；[本周证据](weekly/2026-10-13.md#2-旧论文状态核验)；下周继续 |
| [2505.03836](https://arxiv.org/abs/2505.03836) | Explainable Coarse-to-Fine Ancient Manuscript Duplicates Discovery, OBD-Finder | arXiv 2025 | 1 | 2026-10-13 / v2 (2025-07-05) | 本轮未发现可核对的新录用或正式出版证据 | 补充标题别名 OBD-Finder: Explainable Coarse-to-Fine Text-Centric Oracle Bone Duplicates Discovery；OpenReview 仅 CoRR 镜像；[本周证据](weekly/2026-10-13.md#2-旧论文状态核验)；下周继续 |
| [2506.03798](https://arxiv.org/abs/2506.03798) | CoLa: Chinese Character Decomposition with Compositional Latent Components | arXiv 2025 | 1 | 2026-10-13 / v1 (2025-06-04) | 本轮未发现可核对的新录用或正式出版证据 | ICLR 2026 的对应 OpenReview 记录为 Rejected_Submission；不推断其他投稿结果；[本周证据](weekly/2026-10-13.md#2-旧论文状态核验)；下周继续 |
| [2506.19208](https://arxiv.org/abs/2506.19208) | Ancient Script Image Recognition and Processing: A Review | arXiv 2025 | 1 | 2026-10-13 / v1 (2025-06-24) | 本轮未发现可核对的新录用或正式出版证据 | arXiv 元数据、Crossref/OpenAlex 标题检索及 OpenReview 检索已查；未绑定不匹配结果；[本周证据](weekly/2026-10-13.md#2-旧论文状态核验)；下周继续 |
| [2508.10113](https://arxiv.org/abs/2508.10113) | Pictographic Decipherment OBS Dataset (PD-OBS) | arXiv 2025 | 2 | 2026-10-13 / v2 (2025-08-17) | 本轮未发现可核对的新录用或正式出版证据 | ICLR 2026 对应记录为 Rejected_Submission；官方仓库训练/推理代码仍待发布，已修正链接标签；[本周证据](weekly/2026-10-13.md#2-旧论文状态核验)；下周继续 |
| [2510.26114](https://arxiv.org/abs/2510.26114) | OracleAgent: A Multimodal Reasoning Agent for Oracle Bone Script Research | arXiv 2025 | 1 | 2026-10-13 / v1 (2025-10-30) | 本轮未发现可核对的新录用或正式出版证据 | ICLR 2026 对应记录为 Withdrawn_Submission；这不等于 arXiv 论文撤回；[本周证据](weekly/2026-10-13.md#2-旧论文状态核验)；下周继续 |
| [2511.00076](https://arxiv.org/abs/2511.00076) | Bridging Vision, Language, and Mathematics: Pictographic Character Reconstruction with Bézier Curves | arXiv 2025 | 1 | 2026-10-13 / v1 (2025-10-29) | 本轮未发现可核对的新录用或正式出版证据 | arXiv 元数据、Crossref/OpenAlex 标题检索及 OpenReview 检索已查；未绑定不匹配结果；[本周证据](weekly/2026-10-13.md#2-旧论文状态核验)；下周继续 |
| [2601.06753](https://arxiv.org/abs/2601.06753) | Towards Computational Chinese Paleography | arXiv 2026 | 1 | 2026-10-13 / v2 (2026-01-29) | 本轮未发现可核对的新录用或正式出版证据 | arXiv Comments 仍为 position paper in progress；[本周证据](weekly/2026-10-13.md#2-旧论文状态核验)；下周继续 |
| [2604.09668](https://arxiv.org/abs/2604.09668) | Decoding Ancient Oracle Bone Script via Generative Dictionary Retrieval | arXiv 2026 | 1 | 2026-10-13 / v1 (2026-04-01) | 本轮未发现可核对的新录用或正式出版证据 | arXiv 仍称 under review at Nature Machine Intelligence；该刊搜索页遇挑战，未确认录用；[本周证据](weekly/2026-10-13.md#2-旧论文状态核验)；下周继续 |
| [2604.12865](https://arxiv.org/abs/2604.12865) | From Edges to Meaning: Semantic Line Sketches as a Cognitive Scaffold for Ancient Pictograph Invention | arXiv 2026 | 1 | 2026-10-13 / v2 (2026-04-15) | 本轮未发现可核对的新录用或正式出版证据 | arXiv 元数据、Crossref/OpenAlex 标题检索及 OpenReview 检索已查；未绑定不匹配结果；[本周证据](weekly/2026-10-13.md#2-旧论文状态核验)；下周继续 |
| [2605.11960](https://arxiv.org/abs/2605.11960) | Chronicles-OCR: A Cross-Temporal Perception Benchmark for the Evolutionary Trajectory of Chinese Characters | arXiv 2026 | 2 | 2026-10-13 / v2 (2026-09-28) | 本轮未发现可核对的新录用或正式出版证据 | 新 v2（2026-09-28）；ICLR 2027 同题记录仅为 Submission，不能升级 venue；[本周证据](weekly/2026-10-13.md#2-旧论文状态核验)；下周继续 |
| [2606.25906](https://arxiv.org/abs/2606.25906) | OracleAnalyser: Analysing Implicit Semantics of Oracle Bone Scripts through MLLMs with Post-training | arXiv 2026 | 1 | 2026-10-13 / v1 (2026-06-24) | 本轮未发现可核对的新录用或正式出版证据 | arXiv 元数据、Crossref/OpenAlex 标题检索及 OpenReview 检索已查；未绑定不匹配结果；[本周证据](weekly/2026-10-13.md#2-旧论文状态核验)；下周继续 |
| [2606.31169](https://arxiv.org/abs/2606.31169) | Beyond Single Character: Evaluating MLLMs for Sentence-Level Oracle Bone Inscription Understanding | arXiv 2026 | 1 | 2026-10-13 / v1 (2026-06-30) | 本轮未发现可核对的新录用或正式出版证据 | arXiv 元数据、Crossref/OpenAlex 标题检索及 OpenReview 检索已查；未绑定不匹配结果；[本周证据](weekly/2026-10-13.md#2-旧论文状态核验)；下周继续 |
| [2609.17227](https://arxiv.org/abs/2609.17227) | FROD: Feature Matching Residual Denoising Oracle Bone Decipher | arXiv 2026 | 1 | 2026-10-13 / v1 (2026-09-15) | 作者声明 ICONIP 2026 录用，待官方确认 | arXiv Comments: Accepted at ICONIP 2026；ICONIP 官网及 Springer 精确题目检索未找到对应官方论文记录；[本周证据](weekly/2026-10-13.md#2-旧论文状态核验)；下周继续 |
| [10.2139/ssrn.6271072](https://doi.org/10.2139/ssrn.6271072) | Can Neural Networks Learn the Pictographic Nature of Oracle Bone Script? | SSRN 2026 | 1 | 2026-10-13 / 官方正文受阻 | 疑似与已收录 ESWA 论文同源，内容对应关系尚未确认；不合并 | 三位作者及两位 ORCID 对应，但 SSRN/ScienceDirect 403；[本周记录](weekly/2026-10-13.md#2-旧论文状态核验)；优先核对 OBS-VisSem 与正式版本 |
| [10.1038/s40494-026-03044-y](https://www.nature.com/articles/s40494-026-03044-y) | Relational graphic structure supports diachronic retrieval of wholly unseen ancient Chinese character identities | npj Heritage Science 2026 (advance online) | 1 | 2026-10-13 / Article in Press | 出版社已上线同行评审后接收稿，最终 Version of Record 待替换 | [Nature](https://www.nature.com/articles/s40494-026-03044-y) 明确 final version pending；[本周记录](weekly/2026-10-13.md#3-收录与资源核对)；跟踪最终元数据和资源 |

## 补充候选与归档规则

新增跟踪对象沿用上表字段：非 arXiv 论文将 ID 列填写 DOI 或其他稳定键，注明来源平台。已录用的论文继续留在活跃区，直至正式出版证据和索引同步完成。不要因为年份久远或本周未查到新信息而移出活跃区。

## 已发表且已同步（归档）

| 稳定 ID | 论文 / 项目 | 正式发表状态 | 证据 |
| --- | --- | --- | --- |
| [2303.07012](https://arxiv.org/abs/2303.07012) | AGTGAN: Unpaired Image Translation for Photographic Ancient Character Generation | ACM MM 2022 | DOI [10.1145/3503161.3548338](https://doi.org/10.1145/3503161.3548338)，正式论文元数据已核对；arXiv 为后续预印本入口 |
| [2604.06711](https://arxiv.org/abs/2604.06711) | Specializing Large Models for Oracle Bone Script Interpretation via Component-Grounded Multimodal Knowledge Augmentation | ACL 2026 Long Paper | [ACL Anthology](https://aclanthology.org/2026.acl-long.1626/)；DOI [10.18653/v1/2026.acl-long.1626](https://doi.org/10.18653/v1/2026.acl-long.1626) |
| [2604.11299](https://arxiv.org/abs/2604.11299) | Enhancing Multimodal Large Language Models for Ancient Chinese Character Evolution Analysis via Glyph-Driven Fine-Tuning | ACL 2026 Long Paper | [ACL Anthology](https://aclanthology.org/2026.acl-long.1043/)；DOI [10.18653/v1/2026.acl-long.1043](https://doi.org/10.18653/v1/2026.acl-long.1043) |
| [2607.00057](https://arxiv.org/abs/2607.00057) | Enhancing Oracle Bone Inscription Recognition via Multi-Scale Layer Attention | Information Sciences, online 2026; issue 2027 | [Elsevier DOI](https://doi.org/10.1016/j.ins.2026.124083)；PII `S0020025526010145` |
| `10.1038/s41598-026-71440-2` | Construction of multimodal oracle bone semantic reasoning and knowledge graphs in archaeology under artificial intelligence technology | Scientific Reports 2026 | Paper [10.1038/s41598-026-71440-2](https://doi.org/10.1038/s41598-026-71440-2)；Crossref/OpenAlex/Nature 元数据已核对 |
| `10.1038/s40494-026-02989-4` | ROOTS: recognizing oracle bone inscriptions via an organized tree structure | npj Heritage Science 2026 | Paper [10.1038/s40494-026-02989-4](https://doi.org/10.1038/s40494-026-02989-4)；Nature 页面与作者身份已核对；Research Square 预印本保留在 PAPERS/README |
| `10.1038/s40494-026-02995-6` | An interpretable parametric representation and open dataset for oracle bone script: adaptive Arc segmentation and SVG resource | npj Heritage Science 2026 | Paper [10.1038/s40494-026-02995-6](https://doi.org/10.1038/s40494-026-02995-6)；Nature 页面与题目/作者已核对；Research Square 预印本保留 |
| `10.1038/s40494-026-02970-1` | Denoising of oracle bone rubbing images via a residual network based on base-residual decomposition | npj Heritage Science 2026 | Paper [10.1038/s40494-026-02970-1](https://doi.org/10.1038/s40494-026-02970-1)；Nature 页面、Crossref/OpenAlex 元数据已核对 |
| `10.1038/s40494-026-03006-4` | Dual-branch segmentation of oracle bone drill chisel and its impact on group classification | npj Heritage Science 2026 | Paper [10.1038/s40494-026-03006-4](https://doi.org/10.1038/s40494-026-03006-4)；Nature 页面、Crossref/OpenAlex 元数据已核对 |
| `10.1016/j.eswa.2026.134178` | Can neural networks learn visual correspondence between pictographic oracle bone scripts and object images? | Expert Systems with Applications, online 2026; issue 2027 | Paper [10.1016/j.eswa.2026.134178](https://doi.org/10.1016/j.eswa.2026.134178)；Elsevier API、Crossref/OpenAlex 和 OBI-Survey 交叉核对 |
| [2510.13745](https://arxiv.org/abs/2510.13745) | UniCalli: A Unified Diffusion Framework for Column-Level Generation and Recognition of Chinese Calligraphy | ICLR 2026 Poster | 2026-10-13 核验：[ICLR 官方会议页](https://iclr.cc/virtual/2026/poster/10009779)、[OpenReview](https://openreview.net/forum?id=OSIPdrw56X)；标题、七位作者和摘要对应；[本周证据](weekly/2026-10-13.md#2-旧论文状态核验) |
| [10.21203/rs.3.rs-10039997/v1](https://doi.org/10.21203/rs.3.rs-10039997/v1) | Beyond aggregate metrics: diagnosing the long-tailed failure of oracle bone character detection and recognition | Discover Artificial Intelligence 2026 | 2026-10-13 核验：[正式出版页](https://link.springer.com/article/10.1007/s44163-026-02210-2)，Published 12 October 2026；正式 DOI 10.1007/s44163-026-02210-2；四位作者、OBIMD 与 FAR-YOLO 对应；[本周证据](weekly/2026-10-13.md#3-收录与资源核对) |

归档条目仍保留在本表以便追溯；如发现题目、作者或出版状态冲突，应重新激活并在周记录中说明。

