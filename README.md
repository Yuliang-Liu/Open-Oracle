<p align="center">
    <img src="https://s41.ax1x.com/2026/06/08/pmnGSyj.png" width="250" style="margin-bottom: 0.2;">
</p>

<h1 align="center">Open-Oracle</h1>

<p align="center">
With the support of big data and AI, oracle bone script research has entered a new era. This repository curates open datasets, benchmarks, codebases, and papers for AI-assisted oracle bone inscription recognition, retrieval, rejoining, decipherment, and interpretation.
</p>

<h5 align="center">Please give us a star ⭐ for the latest updates.</h5>

<p align="center">
  <b>Last maintained:</b> 2026-06-13<br>
  <a href="PAPERS.md"><b>Comprehensive paper index</b></a>
</p>

---

## Contents

- [Recent Oracle Bone Projects and Papers](#recent-oracle-bone-projects-and-papers)
- [Datasets and Benchmarks](#datasets-and-benchmarks)
- [Paper Index](#paper-index)
- [Online Resources](#online-resources)
- [Our Projects](#our-projects)
- [Contributing](#contributing)
- [Copyright](#copyright)

## Recent Oracle Bone Projects and Papers

This section lists representative recent oracle bone inscription work from all groups, including our own projects, ordered by year. See [`PAPERS.md`](PAPERS.md) for the more detailed task-oriented paper index.

| Year | Project or Paper | Venue and Status | Category | Links |
| :---: | :--- | :---: | :--- | :--- |
| 2026 | **AlphaOracle** | The Innovation | Decipherment and interpretation | [Paper](https://www.sciencedirect.com/science/article/pii/S2666675826002092), [Code](https://github.com/Yuliang-Liu/AlphaOracle) |
| 2026 | **Oracle Bone Inscriptions Information Processing: A Comprehensive Survey** | npj Heritage Science 2026 | Survey and resources | [Paper](https://www.nature.com/articles/s40494-026-02511-w), [Repo](https://github.com/OBI-Future/OBI-Survey) |
| 2026 | **OBIMD: A Multi-modal Dataset for Contextual Interpretation of Oracle Bone Inscriptions** | Scientific Data 2026 | Multimodal dataset | [Paper](https://www.nature.com/articles/s41597-026-06967-0), [arXiv](https://arxiv.org/abs/2407.03900), [Code](https://github.com/libang1991/OBIMD), [HF](https://huggingface.co/datasets/KLOBIP/OBIMD) |
| 2026 | **PictOBI-20k** | ICASSP 2026 | Visual decipherment benchmark | [IEEE](https://ieeexplore.ieee.org/document/11462601), [arXiv](https://arxiv.org/abs/2509.05773), [Code](https://github.com/OBI-Future/PictOBI-20k) |
| 2026 | **Chronicles-OCR** | arXiv 2026 | Cross-temporal OCR benchmark | [arXiv](https://arxiv.org/abs/2605.11960), [Code](https://github.com/VirtualLUOUCAS/Chronicles-OCR), [HF](https://huggingface.co/datasets/VirtualLUO/Chronicles-OCR) |
| 2026 | **Explainable Oracle Bone Script Recognition via Multimodal Pictographic Reasoning** | AAAI 2026 | Explainable recognition | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/41296) |
| 2026 | **OracleDet** | npj Heritage Science 2026 | Complex-scene OBI detection | [Paper](https://www.nature.com/articles/s40494-026-02621-5), [Code](https://github.com/ZCDMW/OracleDet) |
| 2026 | **OBI Designer** | npj Heritage Science 2026 | Artistic OBI character generation | [Paper](https://www.nature.com/articles/s40494-026-02417-7) |
| 2026 | **Specializing Large Models for OBS Interpretation via Component-Grounded Multimodal Knowledge Augmentation** | arXiv 2026 | Knowledge-augmented interpretation | [arXiv](https://arxiv.org/abs/2604.06711) |
| 2026 | **Decoding Ancient Oracle Bone Script via Generative Dictionary Retrieval** | arXiv 2026 | Dictionary retrieval | [arXiv](https://arxiv.org/abs/2604.09668) |
| 2025 | **OracleFusion** | ICCV 2025 | Structurally constrained semantic typography | [Paper](https://openaccess.thecvf.com/content/ICCV2025/html/Li_OracleFusion_Assisting_the_Decipherment_of_Oracle_Bone_Script_with_Structurally_ICCV_2025_paper.html), [arXiv](https://arxiv.org/abs/2506.21101), [Code](https://github.com/lcs0215/OracleFusion) |
| 2025 | **V-Oracle** | ACL 2025 | Progressive VQA-style reasoning | [Paper](https://aclanthology.org/2025.acl-long.986/) |
| 2025 | **OBI-Bench: Can LMMs Aid in Study of Ancient Script on Oracle Bones?** | ICLR 2025 Spotlight | LMM benchmark | [OpenReview](https://openreview.net/forum?id=hL5jone2Oh), [arXiv](https://arxiv.org/abs/2412.01175), [Code](https://github.com/zijianchen98/OBI-Bench) |
| 2025 | **OracleAgent** | arXiv 2025 | Multimodal research agent | [Paper](https://arxiv.org/abs/2510.26114), [Code](https://github.com/lcs0215/OralceAgent) |
| 2025 | **Interpretable OBS Decipherment with LVLMs, PD-OBS** | arXiv 2025 | Interpretable decipherment | [Paper](https://arxiv.org/abs/2508.10113), [Code](https://github.com/PKXX1943/PD-OBS) |
| 2025 | **Oracle-P15K** | ACM MM 2025 | Long-tail recognition dataset and benchmark | [Paper](https://dl.acm.org/doi/10.1145/3746027.3755067), [Code](https://github.com/OBI-Future/Oracle-P15K) |
| 2025 | **OBIFormer** | Displays 2025 | Denoising and restoration | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0141938225000964), [Code](https://github.com/OBI-Future/OBIFormer) |
| 2025 | **A Graph-based Evolutionary Dataset for Oracle Bone Characters** | npj Heritage Science 2025 | Character evolution graph | [Paper](https://www.nature.com/articles/s40494-025-01951-0), [Code](https://github.com/BrisksHan/GBEDOBC) |
| 2025 | **An Open Benchmark for Oracle Bone Rubbing Image Retrieval** | npj Heritage Science 2025 | Rubbing-image retrieval | [Paper](https://www.nature.com/articles/s40494-025-01859-9) |
| 2025 | **Deep Rejoining Model and Dataset of Oracle Bone Fragment Images** | npj Heritage Science 2025 | Fragment rejoining | [Paper](https://www.nature.com/articles/s40494-025-01651-9) |
| 2025 | **A Text-Image Dual Conditional Stable Diffusion Model for OBI Decipherment** | npj Heritage Science 2025 | Dual conditional diffusion | [Paper](https://www.nature.com/articles/s40494-025-02019-9) |
| 2025 | **A Cross-Font Image Retrieval Network for Recognizing Undeciphered OBI** | ICIC 2025, arXiv 2024 | Cross-font retrieval | [arXiv](https://arxiv.org/abs/2409.06381) |
| 2025 | **Component-Level Segmentation for OBI Decipherment** | AAAI 2025 | Component segmentation | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/35030), [Code](https://github.com/hutt94/Component-Level-OBI-Segmentation) |
| 2024 | **OBSD: Deciphering Oracle Bone Language with Diffusion Models** | ACL 2024 Best Paper | Diffusion-based decipherment | [Paper](https://aclanthology.org/2024.acl-long.831/), [arXiv](https://arxiv.org/abs/2406.00684), [Code](https://github.com/guanhaisu/OBSD) |
| 2024 | **Puzzle Pieces Picker (P3)** | ICDAR 2024 Oral | Radical and stroke reconstruction | [Paper](https://arxiv.org/abs/2406.03019), [Code](https://github.com/Pengjie-W/Puzzle-Pieces-Picker) |
| 2024 | **HUST-OBC** | Scientific Data 2024 | Recognition and decipherment dataset | [Paper](https://www.nature.com/articles/s41597-024-03807-x), [arXiv](https://arxiv.org/abs/2401.15365), [Code](https://github.com/Pengjie-W/HUST-OBC), [Data](https://figshare.com/s/8a9c0420312d94fc01e3) |
| 2024 | **EVOBC** | arXiv 2024 | Multi-period character evolution dataset | [Paper](https://arxiv.org/abs/2401.12467), [Code](https://github.com/RomanticGodVAN/character-Evolution-Dataset), [Data](https://figshare.com/s/ce2cf55b35a2f8ecc4c6) |
| 2024 | **OracleSage** | arXiv 2024 | Visual-linguistic understanding | [Paper](https://arxiv.org/abs/2411.17837) |

## Datasets and Benchmarks

| Dataset or Benchmark | Task | Scale and Notes | Links |
| :--- | :--- | :--- | :--- |
| **HUST-OBC** | Recognition + decipherment | 140,053 images; deciphered and undeciphered character categories | [Paper](https://www.nature.com/articles/s41597-024-03807-x), [Code](https://github.com/Pengjie-W/HUST-OBC), [Data](https://figshare.com/s/8a9c0420312d94fc01e3) |
| **EVOBC** | Character evolution | Multi-period evolution data across OBC, BI, SS, SAC, WSC, CS | [Paper](https://arxiv.org/abs/2401.12467), [Code](https://github.com/RomanticGodVAN/character-Evolution-Dataset), [Data](https://figshare.com/s/ce2cf55b35a2f8ecc4c6) |
| **OBIMD** | Contextual interpretation | 10,077 OBI images; 93,652 annotated characters; sentence-level readings | [Paper](https://www.nature.com/articles/s41597-026-06967-0), [Code](https://github.com/libang1991/OBIMD), [HF](https://huggingface.co/datasets/KLOBIP/OBIMD) |
| **OBI-Bench** | LMM benchmark | Five OBI processing tasks; 5,523 images | [OpenReview](https://openreview.net/forum?id=hL5jone2Oh), [Code](https://github.com/zijianchen98/OBI-Bench) |
| **PictOBI-20k** | Visual decipherment | 20k OBC-object image pairs; 15k+ multi-choice questions | [IEEE](https://ieeexplore.ieee.org/document/11462601), [arXiv](https://arxiv.org/abs/2509.05773), [Code](https://github.com/OBI-Future/PictOBI-20k) |
| **Chronicles-OCR** | Cross-temporal OCR | 2,800 balanced images across the Seven Chinese Scripts, including oracle bone script | [arXiv](https://arxiv.org/abs/2605.11960), [Code](https://github.com/VirtualLUOUCAS/Chronicles-OCR), [HF](https://huggingface.co/datasets/VirtualLUO/Chronicles-OCR) |
| **Oracle-MNIST** | Benchmark classification | 30,222 grayscale oracle-character images in 10 categories | [Paper](https://www.nature.com/articles/s41597-024-02933-w), [Code](https://github.com/wm-bupt/oracle-mnist) |
| **Oracle-P15K** | Long-tail recognition | Long-tail OBI benchmark with synthesis-based augmentation | [Paper](https://dl.acm.org/doi/10.1145/3746027.3755067), [Code](https://github.com/OBI-Future/Oracle-P15K) |
| **PD-OBS** | Interpretable decipherment | Radical and pictographic annotations for LVLM training | [Paper](https://arxiv.org/abs/2508.10113), [Code](https://github.com/PKXX1943/PD-OBS) |
| **GEVOBC and GBEDOBC** | Evolution graph dataset | Graph-based evolutionary oracle bone character dataset | [Paper](https://www.nature.com/articles/s40494-025-01951-0), [Code](https://github.com/BrisksHan/GBEDOBC) |
| **OBI Rubbing Retrieval Benchmark** | Rubbing retrieval | Homologous rubbing retrieval benchmark | [Paper](https://www.nature.com/articles/s40494-025-01859-9) |
| **OBFI and OBID-ACR** | Fragment rejoining and bone association | Fragment-image and bone-level association benchmarks | [OBFI](https://www.nature.com/articles/s40494-025-01651-9), [OBID-ACR](https://www.nature.com/articles/s40494-025-02282-w) |
| **OBC306, HWOBC, YinQiWenYuan** | Recognition and detection | Public resources from Yin Qi Wen Yuan | [Website](https://jgw.aynu.edu.cn/home/down/index.html) |

## Paper Index

This README highlights representative works. For a broader task-oriented bibliography, see:

- 📚 **[`PAPERS.md`](PAPERS.md)**: surveys, knowledge resources, datasets, decipherment, multimodal reasoning, recognition, detection, segmentation, retrieval, rejoining, restoration, generation, and broader ancient-script processing.
- 🔎 **Recommended companion survey repo**: [OBI-Survey](https://github.com/OBI-Future/OBI-Survey).

## Online Resources

### OBI Websites and Databases

| Resource | Link |
| :--- | :--- |
| 殷契文渊 (Yin Qi Wen Yuan) | [Website](https://jgw.aynu.edu.cn/home/index.html) |
| 小学堂 (Xiao Xue Tang) | [Website](https://xiaoxue.iis.sinica.edu.tw/) |
| 国学大师 (Guo Xue Da Shi) | [Website](https://www.guoxuedashi.com/) |
| 缀玉联珠 (Zhui Yu Lian Zhu) | [Website](https://www.fdgwz.org.cn/ZhuiHeLab/Home) |
| Yin Xu OBI Database | [Database](https://obid.ancientbooks.cn/) |
| OBI AI Collaborative Platform | [Website](https://www.jgwlbq.org.cn/home) |
| Multi-function Chinese Character Database | [Database](https://humanum.arts.cuhk.edu.hk/Lexis/lexi-mf/) |
| Chinese Etymology | [Website](https://hanziyuan.net) |
| Omniglot: Oracle Bone Script | [Website](https://www.omniglot.com/chinese/jiaguwen.htm) |

### Museum Collections

| Museum | Link |
| :--- | :--- |
| 故宫博物院 | [Collection](https://digicol.dpm.org.cn/list?category=18&dynasty=1265) |
| 河南博物院 | [Collection](https://www.chnmus.net/ch/collection/boutique/details.html?id=7066680765915860992) |
| 辽宁省博物馆 | [Collection](https://www.lnmuseum.com.cn/#/collect/digital-culture) |
| 山东博物馆 | [Collection](https://www.sdmuseum.com/col/col353161/index.html?uid=750411&pageNum=1) |
| 陕西历史博物馆 | [Collection](https://www.sxhm.com/collection.html) |
| 上海博物馆 | [Collection](https://www.shanghaimuseum.net/mu/frontend/pg/lib1/antique?libTypes=LIB_TYPE_0005) |
| 殷墟博物馆 | [Collection](https://www.ayyx.com/yxgw/collection) |
| 浙江省博物馆 | [Collection](https://www.zhejiangmuseum.com/cn/#/Collection/ExcellentCollection) |
| 中国国家博物馆 | [Collection](https://www.chnmuseum.cn/zp/zpml/201812/t20181218_26025.shtml) |
| 重庆中国三峡博物馆 | [Collection](https://www.3gmuseum.cn/#/collectorsEdition/disclosure?recNo=4028808a5e3b12de015e3b2c79340003&acTiveNo=4028808a5e3b2c79340003) |

## Our Projects

### <span id="AlphaOracle">📘 [The Innovation] AlphaOracle: Oracle Bone Script Decipherment via Human-Workflow-Inspired Deep Learning</span>

<em>Yuliang Liu, Haisu Guan, Pengjie Wang, Xinyu Wang, Jinpeng Wan, Kaile Zhang, Handong Zheng, Xingchen Liu, Zhebin Kuang, Huanxin Yang, Bang Li, Yongge Liu, Lianwen Jin, Xiang Bai</em>.

[Paper](https://www.sciencedirect.com/science/article/pii/S2666675826002092) | [GitHub Code](https://github.com/Yuliang-Liu/AlphaOracle)

AlphaOracle is published in **The Innovation**. AlphaOracle integrates computer vision, computational linguistics, and philological validation into a human-workflow-inspired framework for oracle bone script analysis and decipherment.

<img src="https://s41.ax1x.com/2026/06/13/pmQir6K.jpg" width="100%">

```BibTeX
@article{liu2026alphaoracle,
  title   = {AlphaOracle: Oracle Bone Script Decipherment via Human-Workflow-Inspired Deep Learning},
  author  = {Liu, Yuliang and Guan, Haisu and Wang, Pengjie and Wang, Xinyu and Wan, Jinpeng and Zhang, Kaile and Zheng, Handong and Liu, Xingchen and Kuang, Zhebin and Yang, Huanxin and Li, Bang and Liu, Yongge and Jin, Lianwen and Bai, Xiang},
  journal = {The Innovation},
  year    = {2026},
  url     = {https://www.sciencedirect.com/science/article/pii/S2666675826002092}
}
```

***

### <span id="OraclePrime">📘 [SCIENTIA SINICA Informationis 2026] A Multi-task Multimodal Reasoning Framework for Oracle Bone Character Interpretation</span>

<em>Jinpeng Wan, Yuliang Liu, Xiang Bai</em>.

[Paper](http://engine.scichina.com/doi/10.1360/SSI-2025-0551) | [GitHub Code](https://github.com/RomanticGodVAN/OraclePrime.git) | [Data](https://drive.google.com/drive/folders/1ApeqdOZH_l_Dl3WZn1F_GGPcLCxe630m?usp=drive_link)

This paper introduces **ORACLE-PRIME**, a multi-task multimodal reasoning framework for oracle bone character interpretation. It integrates glyph perception, structural periodization, and evolutionary reasoning to generate philologically grounded reasoning chains.

<img src="https://ibb.co/TqtyVG5d" width="100%">

```BibTeX
@article{wan2026oracleprime,
  title   = {A multi-task multimodal reasoning framework for Oracle Bone character interpretation},
  author  = {Wan, Jinpeng and Liu, Yuliang and Bai, Xiang},
  journal = {SCIENTIA SINICA Informationis},
  year    = {2026},
  pages   = {-},
  url     = {http://www.sciengine.com/publisher/Science China Press/journal/SCIENTIA SINICA Informationis///10.1360/SSI-2025-0551},
  doi     = {10.1360/SSI-2025-0551}
}
```

***

### <span id="OBSD">📘 [ACL 2024 Best Paper] Deciphering Oracle Bone Language with Diffusion Models</span>

<em>Haisu Guan, Huanxin Yang, Xinyu Wang, Shengwei Han, Yongge Liu, Lianwen Jin, Xiang Bai, Yuliang Liu</em>.

[Paper](https://aclanthology.org/2024.acl-long.831/) | [arXiv](https://arxiv.org/abs/2406.00684) | [GitHub Code](https://github.com/guanhaisu/OBSD)

This paper introduces **Oracle Bone Script Decipher (OBSD)**, a conditional diffusion-based strategy that generates modern-character clues for oracle bone script decipherment.

<img src="https://v1.ax1x.com/2024/08/15/7GMxoL.jpg" width="100%">

```BibTeX
@inproceedings{guan2024deciphering,
  title     = {Deciphering Oracle Bone Language with Diffusion Models},
  author    = {Guan, Haisu and Yang, Huanxin and Wang, Xinyu and Han, Shengwei and Liu, Yongge and Jin, Lianwen and Bai, Xiang and Liu, Yuliang},
  booktitle = {Proceedings of the 62nd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)},
  pages     = {15554--15567},
  year      = {2024},
  doi       = {10.18653/v1/2024.acl-long.831}
}
```

***

### <span id="ACCP">📘 [ICDAR 2024 Oral] Puzzle Pieces Picker: Deciphering Ancient Chinese Characters with Radical Reconstruction</span>

<em>Pengjie Wang, Kaile Zhang, Xinyu Wang, Shengwei Han, Yongge Liu, Lianwen Jin, Xiang Bai, Yuliang Liu</em>.

[Paper](https://arxiv.org/abs/2406.03019) | [GitHub Code](https://github.com/Pengjie-W/Puzzle-Pieces-Picker)

Puzzle Pieces Picker (P3) deconstructs oracle bone inscriptions into strokes and radicals and reconstructs them into modern counterparts with a Transformer-based model.

<img src="https://v1.ax1x.com/2024/08/15/7GMAyJ.png" width="100%">

```BibTeX
@inproceedings{wang2024puzzle,
  title     = {Puzzle Pieces Picker: Deciphering Ancient Chinese Characters with Radical Reconstruction},
  author    = {Wang, Pengjie and Zhang, Kaile and Wang, Xinyu and Han, Shengwei and Liu, Yongge and Jin, Lianwen and Bai, Xiang and Liu, Yuliang},
  booktitle = {Document Analysis and Recognition -- ICDAR 2024},
  year      = {2024},
  publisher = {Springer},
  doi       = {10.1007/978-3-031-70533-5_11}
}
```

***

### <span id="EVOBC">📘 [arXiv 2024] An Open Dataset for the Evolution of Oracle Bone Characters: EVOBC</span>

<em>Haisu Guan, Jinpeng Wan, Yuliang Liu, Pengjie Wang, Kaile Zhang, Zhebin Kuang, Xinyu Wang, Xiang Bai, Lianwen Jin</em>.

[Paper](https://arxiv.org/abs/2401.12467) | [GitHub Code](https://github.com/RomanticGodVAN/character-Evolution-Dataset) | [Data](https://figshare.com/s/ce2cf55b35a2f8ecc4c6)

EVOBC collects character images across six historical stages: Oracle Bone Characters, Bronze Inscriptions, Seal Script, Spring and Autumn period characters, Warring States period characters, and Clerical Script.

<img src="https://v1.ax1x.com/2024/08/15/7GMVUG.jpg" width="100%">

```BibTeX
@article{guan2024open,
  title   = {An Open Dataset for the Evolution of Oracle Bone Characters: EVOBC},
  author  = {Guan, Haisu and Wan, Jinpeng and Liu, Yuliang and Wang, Pengjie and Zhang, Kaile and Kuang, Zhebin and Wang, Xinyu and Bai, Xiang and Jin, Lianwen},
  journal = {arXiv preprint arXiv:2401.12467},
  year    = {2024}
}
```

***

### <span id="HUST-OBC">📘 [Scientific Data 2024] An Open Dataset for Oracle Bone Character Recognition and Decipherment</span>

<em>Pengjie Wang, Kaile Zhang, Xinyu Wang, Shengwei Han, Yongge Liu, Jinpeng Wan, Haisu Guan, Zhebin Kuang, Lianwen Jin, Xiang Bai, Yuliang Liu</em>.

[Paper](https://www.nature.com/articles/s41597-024-03807-x) | [arXiv](https://arxiv.org/abs/2401.15365) | [GitHub Code](https://github.com/Pengjie-W/HUST-OBC) | [Data](https://figshare.com/s/8a9c0420312d94fc01e3) | [hyper.ai](https://hyper.ai/datasets/33506)

HUST-OBC is a large-scale open dataset for oracle bone character recognition and decipherment, containing deciphered and undeciphered OBC images.

<img src="https://v1.ax1x.com/2024/08/15/7GMW2B.jpg" width="100%">

```BibTeX
@article{wang2024open,
  title   = {An Open Dataset for Oracle Bone Character Recognition and Decipherment},
  author  = {Wang, Pengjie and Zhang, Kaile and Wang, Xinyu and Han, Shengwei and Liu, Yongge and Wan, Jinpeng and Guan, Haisu and Kuang, Zhebin and Jin, Lianwen and Bai, Xiang and Liu, Yuliang},
  journal = {Scientific Data},
  volume  = {11},
  number  = {1},
  year    = {2024},
  doi     = {10.1038/s41597-024-03807-x}
}
```

***


## Contributing

We welcome pull requests and issues. For new papers and resources, please include:

1. **Title**, **authors**, **venue and year**, and **task category**.
2. Official paper link, DOI, arXiv, or OpenReview page when available.
3. Code, data, or demo links if public.
4. A one-line summary of the contribution.


## Copyright

We welcome suggestions to help improve Open-Oracle. For any query, please contact Prof. Yuliang Liu: ylliu@hust.edu.cn. If you find something interesting, feel free to share it by email or open an issue. Thanks!
