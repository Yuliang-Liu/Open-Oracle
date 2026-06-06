# Open-Oracle Paper Index

> Last updated: 2026-06-06. This file is a task-oriented bibliography for AI-assisted oracle bone inscription (OBI) and oracle bone script (OBS) processing. PRs are welcome.

## Contents

- [Surveys, Position Papers, and Knowledge Resources](#surveys-position-papers-and-knowledge-resources)
- [Datasets and Benchmarks](#datasets-and-benchmarks)
- [Decipherment, Interpretation, and LMM and Agent Systems](#decipherment-interpretation-and-lmm-and-agent-systems)
- [Recognition, Classification, and Category Discovery](#recognition-classification-and-category-discovery)
- [Detection and Segmentation](#detection-and-segmentation)
- [Retrieval, Rubbing Retrieval, and Literature Retrieval](#retrieval-rubbing-retrieval-and-literature-retrieval)
- [Rejoining, Bone Association, and Duplicate Discovery](#rejoining-bone-association-and-duplicate-discovery)
- [Restoration, Inpainting, Augmentation, and Generation](#restoration-inpainting-augmentation-and-generation)
- [Ancient Script and Chinese Character Evolution Beyond OBI](#ancient-script-and-chinese-character-evolution-beyond-obi)

## Surveys, Position Papers, and Knowledge Resources

| Paper or Resource | Venue and Year | Focus | Links |
| :--- | :---: | :--- | :--- |
| Oracle Bone Inscriptions Information Processing: A Comprehensive Survey | npj Heritage Science 2026 | Task-centric OBI information-processing survey | [Paper](https://www.nature.com/articles/s40494-026-02511-w), [Repo](https://github.com/OBI-Future/OBI-Survey) |
| A Comprehensive Survey of Oracle Character Recognition: Challenges, Datasets, Methodology, and Beyond | Pattern Recognition 2026, arXiv 2024 | Oracle character recognition survey | [Paper](https://doi.org/10.1016/j.patcog.2025.111824), [arXiv](https://arxiv.org/abs/2411.11354) |
| Ancient Script Image Recognition and Processing: A Review | arXiv 2025 | Ancient-script image processing survey | [arXiv](https://arxiv.org/abs/2506.19208) |
| Towards Computational Chinese Paleography | arXiv 2026 | Position paper on computational paleography | [arXiv](https://arxiv.org/abs/2601.06753) |
| Oracle Bone Inscriptions Information Processing Based on Multi-modal Knowledge Graph | Computers and Electrical Engineering 2021 | Multi-modal OBI knowledge graph | [Paper](https://doi.org/10.1016/j.compeleceng.2021.107173) |
| The Current State of the OBI DICT Project: A Bilingual e-Dictionary of Oracle-Bone Inscriptions with AI Image Recognition | Lexikos 2024 | Digital dictionary and AI recognition | [Paper](https://doi.org/10.5788/34-1-1906) |
| Crowd-OBIGA: A Crowdsourced Approach for Oracle Bone Inscriptions Glyph Annotation | WAIM 2024 | Crowdsourced glyph annotation | [Paper](https://doi.org/10.1007/978-981-97-7244-5_34) |

## Datasets and Benchmarks

| Dataset or Paper | Venue and Year | Task and Data | Links |
| :--- | :---: | :--- | :--- |
| Oracle-MNIST: A Dataset of Oracle Characters for Benchmarking Machine Learning Algorithms | Scientific Data 2024, arXiv 2022 | 30,222 images, 10 categories | [Paper](https://www.nature.com/articles/s41597-024-02933-w), [arXiv](https://arxiv.org/abs/2205.09442), [Code](https://github.com/wm-bupt/oracle-mnist) |
| OBC306: A Large-Scale Oracle Bone Character Recognition Dataset | ICDAR 2019 | Recognition benchmark | [Paper](https://ieeexplore.ieee.org/document/8978032), [Data](https://jgw.aynu.edu.cn/home/down/detail/index.html?sysid=16) |
| Oracle-50K: Self-supervised Learning of Orc-Bert Augmentor for Recognizing Few-Shot Oracle Characters | MMM 2021 | Few-shot OBI recognition | [Paper](https://doi.org/10.1007/978-3-030-69544-6_39), [Code](https://github.com/whhamber/Oracle-50K) |
| Toward Zero-shot Character Recognition: A Gold Standard Dataset with Radical-level Annotations | ACM MM 2023 | Radical-level annotations and zero-shot recognition | [Paper](https://arxiv.org/abs/2308.00655) |
| An Open Dataset for the Evolution of Oracle Bone Characters: EVOBC | arXiv 2024 | Multi-stage Chinese character evolution | [arXiv](https://arxiv.org/abs/2401.12467), [Code](https://github.com/RomanticGodVAN/character-Evolution-Dataset), [Data](https://figshare.com/s/ce2cf55b35a2f8ecc4c6) |
| An Open Dataset for Oracle Bone Character Recognition and Decipherment | Scientific Data 2024 | HUST-OBC recognition and decipherment dataset | [Paper](https://www.nature.com/articles/s41597-024-03807-x), [Code](https://github.com/Pengjie-W/HUST-OBC), [Data](https://figshare.com/s/8a9c0420312d94fc01e3) |
| Oracle Bone Inscriptions Multi-modal Dataset | arXiv 2024, Scientific Data 2026 | OBIMD; rubbings, facsimiles, character and sentence annotations | [Paper](https://www.nature.com/articles/s41597-026-06967-0), [arXiv](https://arxiv.org/abs/2407.03900), [Code](https://github.com/libang1991/OBIMD), [HF](https://huggingface.co/datasets/KLOBIP/OBIMD) |
| OBI-Bench: Can LMMs Aid in Study of Ancient Script on Oracle Bones? | ICLR 2025 Spotlight, arXiv 2024 | LMM benchmark for five OBI tasks | [OpenReview](https://openreview.net/forum?id=hL5jone2Oh), [arXiv](https://arxiv.org/abs/2412.01175), [Code](https://github.com/zijianchen98/OBI-Bench) |
| ROBC: A Radical-Level Oracle Bone Character Dataset | PRCV 2024 and 2025 | Radical-level dataset | [Paper](https://doi.org/10.1007/978-981-97-8511-7_8) |
| A Graph-Based Evolutionary Dataset for Oracle Bone Characters from Inscriptions to Modern Chinese Scripts | npj Heritage Science 2025 | GEVOBC graph-based evolution dataset | [Paper](https://www.nature.com/articles/s40494-025-01951-0), [Code](https://github.com/BrisksHan/GBEDOBC) |
| Mitigating Long-tail Distribution in Oracle Bone Inscriptions: Dataset, Model, and Benchmark | ACM MM 2025 | Oracle-P15K, long-tail recognition | [Paper](https://dl.acm.org/doi/10.1145/3746027.3755067), [Code](https://github.com/OBI-Future/Oracle-P15K) |
| Pictographic Decipherment OBS Dataset (PD-OBS) | arXiv 2025 | Radical and pictographic annotations for LVLM decipherment | [Paper](https://arxiv.org/abs/2508.10113), [Code](https://github.com/PKXX1943/PD-OBS) |
| PictOBI-20k: Unveiling Large Multimodal Models in Visual Decipherment for Pictographic Oracle Bone Characters | ICASSP 2026, arXiv 2025 | 20k OBC-object image pairs; 15k+ MCQs | [IEEE](https://ieeexplore.ieee.org/document/11462601), [arXiv](https://arxiv.org/abs/2509.05773), [Code](https://github.com/OBI-Future/PictOBI-20k) |
| An Open Benchmark for Oracle Bone Rubbing Image Retrieval | npj Heritage Science 2025 | Homologous rubbing retrieval benchmark | [Paper](https://www.nature.com/articles/s40494-025-01859-9) |
| Deep Rejoining Model and Dataset of Oracle Bone Fragment Images | npj Heritage Science 2025 | Fragment-image rejoining dataset | [Paper](https://www.nature.com/articles/s40494-025-01651-9) |
| A Multi-modal Dataset and Method for Bone-level Association Prediction in Oracle Bone Inscriptions | npj Heritage Science 2026 | Bone-level association prediction | [Paper](https://www.nature.com/articles/s40494-025-02282-w) |

## Decipherment, Interpretation, and LMM and Agent Systems

| Paper or Project | Venue and Year | Focus | Links |
| :--- | :---: | :--- | :--- |
| AlphaOracle: Oracle Bone Script Decipherment via Human-Workflow-Inspired Deep Learning | The Innovation, Accepted | Human-workflow-inspired decipherment framework | [Code](https://github.com/Yuliang-Liu/AlphaOracle) |
| Deciphering Ancient Chinese Oracle Bone Inscriptions Using Case-Based Reasoning | ICCBR 2021 | Case-based reasoning and multi-font retrieval | [Paper](https://doi.org/10.1007/978-3-030-86957-1_21) |
| Study on the Evolution of Chinese Characters Based on Few-shot Learning: From Oracle Bone Inscriptions to Regular Script | PLOS ONE 2022 | Few-shot character evolution | [Paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0272974) |
| Sundial-GAN: A Cascade GAN Framework for Deciphering Oracle Bone Inscriptions | ACM MM 2022 | Oracle-to-modern evolution simulation | [Paper](https://dl.acm.org/doi/10.1145/3503161.3547925) |
| Diff-Oracle: Deciphering Oracle Bone Scripts with Controllable Diffusion Model | arXiv 2023, ACM TOMM 2026 | Diffusion-based OBI generation and decipherment | [arXiv](https://arxiv.org/abs/2312.13631), [Paper](https://dl.acm.org/doi/abs/10.1145/3806389) |
| Deciphering Oracle Bone Language with Diffusion Models | ACL 2024 Best Paper | Conditional diffusion for OBS-to-modern-character clues | [Paper](https://aclanthology.org/2024.acl-long.831/), [Code](https://github.com/guanhaisu/OBSD) |
| Puzzle Pieces Picker: Deciphering Ancient Chinese Characters with Radical Reconstruction | ICDAR 2024 Oral | Radical and stroke reconstruction | [arXiv](https://arxiv.org/abs/2406.03019), [Code](https://github.com/Pengjie-W/Puzzle-Pieces-Picker) |
| Making Visual Sense of Oracle Bones for You and Me | CVPR 2024 | Visual guides for pictographic understanding | [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Qiao_Making_Visual_Sense_of_Oracle_Bones_for_You_and_Me_CVPR_2024_paper.html) |
| OracleSage: Towards Unified Visual-Linguistic Understanding of Oracle Bone Scripts through Cross-Modal Knowledge Fusion | arXiv 2024 | Cross-modal visual-linguistic reasoning | [arXiv](https://arxiv.org/abs/2411.17837) |
| OBI-Bench: Can LMMs Aid in Study of Ancient Script on Oracle Bones? | ICLR 2025 Spotlight | Benchmarking LMMs on whole-process OBI tasks | [OpenReview](https://openreview.net/forum?id=hL5jone2Oh), [Code](https://github.com/zijianchen98/OBI-Bench) |
| Component-Level Segmentation for Oracle Bone Inscription Decipherment | AAAI 2025 | Component segmentation for decipherment support | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/35030), [Code](https://github.com/hutt94/Component-Level-OBI-Segmentation) |
| V-Oracle: Making Progressive Reasoning in Deciphering Oracle Bones for You and Me | ACL 2025 | Progressive VQA-style reasoning | [Paper](https://aclanthology.org/2025.acl-long.986/) |
| A Cross-Font Image Retrieval Network for Recognizing Undeciphered Oracle Bone Inscriptions | ICIC 2025, arXiv 2024 | Historical-font retrieval for undeciphered OBI | [arXiv](https://arxiv.org/abs/2409.06381) |
| A Graph-Based Evolutionary Dataset for Oracle Bone Characters from Inscriptions to Modern Chinese Scripts | npj Heritage Science 2025 | Graph-based evolutionary evidence | [Paper](https://www.nature.com/articles/s40494-025-01951-0) |
| A Text-Image Dual Conditional Stable Diffusion Model for Oracle Bone Inscription Decipherment | npj Heritage Science 2025 | Dual visual and semantic conditional diffusion | [Paper](https://www.nature.com/articles/s40494-025-02019-9) |
| OracleFusion: Assisting the Decipherment of Oracle Bone Script with Structurally Constrained Semantic Typography | ICCV 2025 | MLLM with vectorized semantic typography | [Paper](https://openaccess.thecvf.com/content/ICCV2025/html/Li_OracleFusion_Assisting_the_Decipherment_of_Oracle_Bone_Script_with_Structurally_ICCV_2025_paper.html), [Code](https://github.com/lcs0215/OracleFusion) |
| Interpretable Oracle Bone Script Decipherment through Radical and Pictographic Analysis with LVLMs | arXiv 2025 | Interpretable LVLM decipherment with PD-OBS | [arXiv](https://arxiv.org/abs/2508.10113), [Code](https://github.com/PKXX1943/PD-OBS) |
| OracleAgent: A Multimodal Reasoning Agent for Oracle Bone Script Research | arXiv 2025 | Agentic workflow for OBS research | [arXiv](https://arxiv.org/abs/2510.26114), [Code](https://github.com/lcs0215/OralceAgent) |
| Specializing Large Models for Oracle Bone Script Interpretation via Component-Grounded Multimodal Knowledge Augmentation | arXiv 2026 | Component-grounded multimodal RAG with OB-Radix | [arXiv](https://arxiv.org/abs/2604.06711), [OpenReview](https://openreview.net/forum?id=hCVGAnQ7eE) |
| Decoding Ancient Oracle Bone Script via Generative Dictionary Retrieval | arXiv 2026 | Generative dictionary retrieval | [arXiv](https://arxiv.org/abs/2604.09668) |
| Can Neural Networks Learn the Pictographic Nature of Oracle Bone Script? | SSRN 2026 | Pictographic nature and neural-network analysis | [Preprint](https://doi.org/10.2139/ssrn.6271072) |
| Explainable Oracle Bone Script Recognition via Multimodal Pictographic Reasoning | AAAI 2026 | Explainable MLLM recognition and interpretation | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/41296) |
| Human--Computer Collaborative Approach to the Decipherment of Oracle Bone Inscriptions with Generative Adversarial Networks | npj Heritage Science 2026 | Image-to-image translation and human-computer collaboration | [Paper](https://www.nature.com/articles/s40494-026-02509-4) |
| A Multi-task Multimodal Reasoning Framework for Oracle Bone Character Interpretation | Scientia Sinica Informationis 2026 | Semantic interpretation and multi-task reasoning | [Paper](https://doi.org/10.1360/SSI-2025-0551) |
| Deciphering Oracle Bone Characters: Pictographic Captioning and Reasoning for Morphological Recognition | Information Processing & Management 2026 | Pictographic captioning and LMM reasoning | [Paper](https://www.sciencedirect.com/science/article/pii/S0306457326002396) |

## Recognition, Classification, and Category Discovery

| Paper | Venue and Year | Focus | Links |
| :--- | :---: | :--- | :--- |
| A Method of Jia Gu Wen Recognition Based on a Two-level Classification | ICDAR 1995 | Topological two-level classification | [Paper](https://ieeexplore.ieee.org/document/602030/) |
| Recognition of Oracular Bone Inscriptions Using Template Matching | IJCTE 2016 | Template matching | [Paper](https://www.ijcte.org/vol8/1019-C010.pdf) |
| Building Hierarchical Representations for Oracle Character and Sketch Recognition | IEEE TIP 2016 | Hierarchical representation | [Paper](https://ieeexplore.ieee.org/document/7327196/) |
| Two-Stage Recognition for Oracle Bone Inscriptions | ICIAP 2017 | Two-stage recognition | [Paper](https://doi.org/10.1007/978-3-319-68548-9_61) |
| OBC306: A Large-Scale Oracle Bone Character Recognition Dataset | ICDAR 2019 | Dataset and CNN baselines | [Paper](https://ieeexplore.ieee.org/document/8978032/) |
| Oracle Character Recognition by Nearest Neighbor Classification with Deep Metric Learning | ICDAR 2019 | Deep metric learning | [Paper](https://ieeexplore.ieee.org/document/8977960) |
| Recognition of Oracle Radical Based on the Capsule Network | TIS 2019 | Radical recognition | [Paper](https://html.rhhz.net/tis/html/201904069.htm) |
| A Classification Method of Oracle Materials Based on Local Convolutional Neural Network Framework | IEEE CG&A 2020 | Material classification | [Paper](https://ieeexplore.ieee.org/document/9004518/) |
| Oracle Character Image Retrieval by Combining Deep Neural Networks and Clustering Technology | IAENG IJCS 2020 | DNN and clustering for retrieval and classification | [Paper](https://www.iaeng.org/IJCS/issues_v47/issue_2/IJCS_47_2_08.pdf) |
| Distinguishing Oracle Variants Based on Isomorphism and Symmetry Invariances of Oracle-bone Inscriptions | IEEE Access 2020 | Variant discrimination | [Paper](https://ieeexplore.ieee.org/document/9171826/) |
| Oracle Bone Inscriptions Recognition Based on Deep Convolutional Neural Network | JOIG 2020 | CNN recognition | [Paper](https://www.joig.net/index.php?m=content&c=index&a=show&catid=66&id=249) |
| Recognition of Oracle Bone Inscriptions by Using Two Deep Learning Models | IJDH 2021 and 2023 | YOLO and MobileNet pipeline | [arXiv](https://arxiv.org/abs/2105.00777) |
| Unsupervised Structure-Texture Separation Network for Oracle Character Recognition | IEEE TIP 2022 | Structure-texture disentanglement | [Paper](https://ieeexplore.ieee.org/document/9757826/), [Code](https://github.com/wm-bupt/STSN) |
| Radical-based Extract and Recognition Networks for Oracle Character Recognition | IJDAR 2022 | Radical-aware recognition | [Paper](https://link.springer.com/article/10.1007/s10032-021-00392-2) |
| Improvement of Oracle Bone Inscription Recognition Accuracy: A Deep Learning Perspective | ISPRS IJGI 2022 | Recognition baselines | [Paper](https://www.mdpi.com/2220-9964/11/1/45) |
| Oracle Character Recognition Using Unsupervised Discriminative Consistency Network | Pattern Recognition 2024, arXiv 2023 | Unsupervised domain adaptation | [Paper](https://doi.org/10.1016/j.patcog.2023.110180), [arXiv](https://arxiv.org/abs/2312.06075) |
| RZCR: Zero-shot Character Recognition via Radical-based Reasoning | IJCAI 2023 | Zero-shot radical reasoning | [Paper](https://www.ijcai.org/proceedings/2023/73) |
| OraclePoints: A Hybrid Neural Representation for Oracle Character | ACM MM 2023 | Image-point hybrid representation | [Paper](https://dl.acm.org/doi/10.1145/3581783.3612534) |
| AGTGAN: Unpaired Image Translation for Photographic Ancient Character Generation | arXiv 2023 | Photographic ancient-character generation for recognition | [arXiv](https://arxiv.org/abs/2303.07012) |
| UFCNet: Unsupervised Network Based on Fourier Transform and Convolutional Attention for Oracle Character Recognition | ML4AL @ ACL 2024 | Fourier and convolutional attention | [Paper](https://aclanthology.org/2024.ml4al-1.11/) |
| Unsupervised Attention Regularization Based Domain Adaptation for Oracle Character Recognition | arXiv 2024 | Domain adaptation | [arXiv](https://arxiv.org/abs/2409.15893) |
| LCINet: Local Cross-position Interaction Network for Oracle Bone Inscriptions Recognition | IJCNN 2024 | Local cross-position interaction | [Paper](https://doi.org/10.1109/IJCNN60899.2024.10651282) |
| Oracle Bone Inscription Character Recognition Based on a Novel Convolutional Neural Network Architecture | IEEE Access 2024 | CNN recognition | [Paper](https://doi.org/10.1109/ACCESS.2024.3521319) |
| Enhancing Oracle Bone Character Category Discovery via Character Component Distillation and Self-Merged Pseudo-Label | Symmetry 2024 | Category discovery | [Paper](https://www.mdpi.com/2073-8994/16/9/1098) |
| Oracle Bone Script Similar Character Screening Approach Based on SimSiam Contrastive Learning and Supervised Learning | AIPMV 2024, arXiv 2024 | Similar-character screening | [arXiv](https://arxiv.org/abs/2408.06811) |
| OBCTeacher: Resisting Labeled Data Scarcity in Oracle Bone Character Detection by Semi-supervised Learning | Information Processing & Management 2024 | Semi-supervised character detection and recognition | [Paper](https://doi.org/10.1016/j.ipm.2024.103864) |
| OBI-CMF: Self-supervised Learning with Contrastive Masked Frequency Modeling for Oracle Bone Inscription Recognition | npj Heritage Science 2025 | Self-supervised contrastive learning | [Paper](https://www.nature.com/articles/s40494-025-01644-8) |
| Historical Oracle Bone Character Recognition through Domain Transfer and Mutual Learning | Applied Soft Computing 2025 | Domain transfer and mutual learning | [Paper](https://doi.org/10.1016/j.asoc.2025.113031) |
| Dual-Pyramid Attention Collaborative Network for Oracle Bone Inscription Classification | ICASSP 2025 | Classification with dual-pyramid attention | [Paper](https://doi.org/10.1109/ICASSP49660.2025.10888675) |
| Long-tailed Oracle Character Recognition Based on Convolutional Neural Networks and Vision Transformers | ICASSP 2025 | Long-tail recognition | [Paper](https://doi.org/10.1109/ICASSP49660.2025.10888269) |
| OracleNet: Enhancing Oracle Bone Script Recognition with Adaptive Deformation and Texture-Structure Decoupling | npj Heritage Science 2025 | Adaptive deformation + disentanglement | [Paper](https://www.nature.com/articles/s40494-025-01839-z) |
| Oracle Character Recognition Using Universal Inverted Bottleneck and Inverse Image Frequency | IJDAR 2025 | Universal inverted bottleneck and inverse image frequency | [Paper](https://doi.org/10.1007/s10032-025-00512-2) |
| WMAR-CB: Wavelet-Enhanced Multi-Strategy Network for Oracle-Bone Script Recognition | IEEE Access 2025 | Wavelet-enhanced recognition | [Paper](https://doi.org/10.1109/ACCESS.2025.3640506) |
| OracleGCD: Generalized Category Discovery for Oracle Bone Scripts | ICDAR 2025 | Generalized category discovery | [Paper](https://doi.org/10.1007/978-3-032-04624-6_27) |
| OracleProtoPNet: Oracle Character Recognition with Interpretability | ICDAR 2025 | Interpretable prototype recognition | [Paper](https://doi.org/10.1007/978-3-032-04627-7_12) |
| Open Set Oracle Character Recognition via Adaptive Decision Boundary | ICDAR Workshops 2025 | Open-set recognition | [Paper](https://doi.org/10.1007/978-3-032-09371-4_16) |
| Ora-NSC: A Novel Semi-supervised Approach for Oracle Bone Fragment Classification with Imbalanced Classes | ACM MM Asia 2025 | Semi-supervised imbalanced classification | [Paper](https://dl.acm.org/doi/10.1145/3743093.3770992) |
| InteChar: A Unified Oracle Bone Character List for Ancient Chinese Language Modeling | AAAI 2026, arXiv 2025 | Unified character list for ancient Chinese LM | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/36981), [arXiv](https://arxiv.org/abs/2508.15791) |
| Stroke-Based Perception: Discover Novel Oracle Characters | IEEE TMM 2026 | Semi-supervised novel category discovery | [Paper](https://ieeexplore.ieee.org/document/11482847/) |
| Dual Manifold Volume-Balanced Framework for Long-Tailed Oracle Character Recognition | PRCV 2025 and 2026 | Long-tailed recognition | [Paper](https://doi.org/10.1007/978-981-95-5676-2_40) |
| Prism-OBI: A Novel Framework for Oracle Bone Inscription Recognition via Visual Perception and Feature Decoupling | npj Heritage Science 2026 | Visual perception + feature decoupling | [Paper](https://www.nature.com/articles/s40494-026-02493-9) |
| Chronicles-OCR: A Cross-Temporal Perception Benchmark for the Evolutionary Trajectory of Chinese Characters | arXiv 2026 | Cross-temporal VLLM OCR benchmark | [arXiv](https://arxiv.org/abs/2605.11960) |

## Detection and Segmentation

| Paper | Venue and Year | Focus | Links |
| :--- | :---: | :--- | :--- |
| Oracle Bone Inscription Detector Based on SSD | ICIAP 2019 | SSD-based detection | [Paper](https://doi.org/10.1007/978-3-030-30754-7_13) |
| Oracle Bone Inscriptions Detection in Rubbings Based on Deep Learning | ITAIC 2020 | Detection in rubbings | [Paper](https://doi.org/10.1109/ITAIC49862.2020.9339132) |
| Oracle Character Detection Based on Improved Faster R-CNN | ICITBS 2021 | Faster R-CNN with feature fusion | [Paper](https://ieeexplore.ieee.org/document/9526033/) |
| Shape Prior Fusion for Oracle Bone Inscriptions Detection | ICIGP 2024 | Shape-prior detection | [Paper](https://doi.org/10.1145/3647649.3647711) |
| Detecting Oracle Bone Inscriptions via Pseudo-category Labels | Heritage Science 2024 | Pseudo-category labels | [Paper](https://heritagesciencejournal.springeropen.com/articles/10.1186/s40494-024-01221-5) |
| An Oracle Bone Inscriptions Detection Algorithm Based on Improved YOLOv8 | Algorithms 2024 | Improved YOLOv8 | [Paper](https://www.mdpi.com/1999-4893/17/5/174) |
| Automatic Segmentation of Oracle Bone Inscriptions Using YOLOv8 | Procedia Computer Science 2024 | YOLOv8 segmentation | [Paper](https://doi.org/10.1016/j.procs.2024.08.201) |
| Oracle Bone Character Detection Based on Optimized YOLOv10 | MLPR 2024 | Optimized YOLOv10 | [Paper](https://doi.org/10.1145/3696687.3696701) |
| Rubbing Oracle Bone Character Recognition Based on Improved YOLOv8 Network | ICMA 2024 | YOLOv8 detection and recognition | [Paper](https://doi.org/10.1109/ICMA61710.2024.10633150) |
| Lightweight Oracle Bone Character Detection Algorithm Based on Improved YOLOv7-tiny | ICMA 2024 | Lightweight YOLOv7-tiny | [Paper](https://doi.org/10.1109/ICMA61710.2024.10633204) |
| Text Detection and Character Recognition of Oracle Original Topographies Based on PP-YOLOE+ | ICSECE 2024 | PP-YOLOE+ | [Paper](https://doi.org/10.1109/ICSECE61636.2024.10729332) |
| Clustering-based Feature Representation Learning for Oracle Bone Inscriptions Detection | npj Heritage Science 2025, arXiv 2025 | Clustering-based feature representation | [Paper](https://www.nature.com/articles/s40494-025-01850-4), [arXiv](https://arxiv.org/abs/2508.18641) |
| Information Disentanglement for Unsupervised Domain Adaptive Oracle Bone Inscriptions Detection | Signal Processing: Image Communication 2025 | Unsupervised domain-adaptive detection | [Paper](https://doi.org/10.1016/j.image.2025.117334) |
| Oracle Character Prototype-Guided Cyclic Disentanglement for Oracle Bone Inscriptions Detection | ICPRAI 2024 and 2025 | Prototype-guided cyclic disentanglement | [Paper](https://doi.org/10.1007/978-981-97-8705-0_14) |
| OBTD-Net: Oracle Bone Text Detection Based on ResNet | ICCPA 2025 | ResNet-based text detection | [Paper](https://doi.org/10.1117/12.3076335) |
| FDW-YOLO: An Improved YOLOv12 for Oracle Bone Inscriptions Detection | ICONIP 2025 and 2026 | YOLOv12 detection | [Paper](https://doi.org/10.1007/978-981-95-4378-6_18) |
| OracleDet: Structure-guided and Spatial-frequency Aware Detection of Oracle Bone Inscriptions in Complex Heritage Scenes | npj Heritage Science 2026 | Structure-aware and spatial-frequency-aware detection | [Paper](https://www.nature.com/articles/s40494-026-02621-5) |
| Detecting Unknown and Classifying Known Oracle Bone Characters via Novel Data Augmentation | npj Heritage Science 2026 | OOD detection and known-class classification | [Paper](https://www.nature.com/articles/s40494-026-02678-2) |
| ROOTS: Recognizing Oracle Bone Inscriptions via an Organized Tree Structure | Preprint 2026 | Organized tree structure for recognition | [Preprint](https://doi.org/10.21203/rs.3.rs-9733608/v1) |

## Retrieval, Rubbing Retrieval, and Literature Retrieval

| Paper | Venue and Year | Focus | Links |
| :--- | :---: | :--- | :--- |
| Oracle Bone Inscriptions Image Retrieval Based on Metric Learning | ICDAR 2024 | Metric learning retrieval | [Paper](https://doi.org/10.1007/978-3-031-70543-4_10) |
| Component-Level Oracle Bone Inscription Retrieval | ICMR 2024 | Component-level retrieval | [Paper](https://dl.acm.org/doi/10.1145/3652583.3658116), [Code](https://github.com/hutt94/Component-Level-OBI-Retrieval) |
| Linking Unknown Characters via Oracle Bone Inscriptions Retrieval | Multimedia Systems 2024 | Unknown-character retrieval | [Paper](https://link.springer.com/article/10.1007/s00530-024-01327-7) |
| A Cross-Font Image Retrieval Network for Recognizing Undeciphered Oracle Bone Inscriptions | ICIC 2025, arXiv 2024 | Cross-font retrieval | [arXiv](https://arxiv.org/abs/2409.06381) |
| Oracle Bone Inscription Image Retrieval Based on Improved ResNet Network | ICPR 2024 and 2025 | ResNet-based image retrieval | [Paper](https://doi.org/10.1007/978-3-031-78305-0_4) |
| An Open Benchmark for Oracle Bone Rubbing Image Retrieval | npj Heritage Science 2025 | Rubbing-image retrieval benchmark | [Paper](https://www.nature.com/articles/s40494-025-01859-9) |
| A Deep Learning Method for Image-based Retrieval of Oracle Bone Inscriptions Literature | npj Heritage Science 2026 | Literature retrieval from images | [Paper](https://www.nature.com/articles/s40494-026-02573-w) |

## Rejoining, Bone Association, and Duplicate Discovery

| Paper | Venue and Year | Focus | Links |
| :--- | :---: | :--- | :--- |
| Research on Key Technologies of the Computer Aided Rejoining of Oracle Bone Inscriptions | ICIFE 2010 | Freeman chain code and contour matching | [Paper](https://ieeexplore.ieee.org/document/5609279) |
| System Design for Computer Aided Rejoining of Bones and Tortoise Shells with Inscriptions Based on Contour Matching | ICCCT 2010 | Shape-function contour matching | [Paper](https://ieeexplore.ieee.org/document/5688700) |
| AI-Powered Oracle Bone Inscriptions Recognition and Fragments Rejoining | IJCAI 2020 | Recognition + fragment rejoining | [Paper](https://www.ijcai.org/proceedings/2020/779) |
| The Research on Rejoining of the Oracle Bone Rubbings Based on Curve Matching | TALLIP 2021 | Curve matching | [Paper](https://dl.acm.org/doi/10.1145/3460393) |
| Data-driven Oracle Bone Rejoining: A Dataset and Practical Self-supervised Learning Scheme | KDD 2022 | Self-supervised rejoining | [Paper](https://dl.acm.org/doi/10.1145/3534678.3539050) |
| Internal Similarity Network for Rejoining Oracle Bone Fragment Images | Symmetry 2022 | Internal similarity pooling | [Paper](https://www.mdpi.com/2073-8994/14/7/1464) |
| SFF-Siam: A New Oracle Bone Rejoining Method Based on Siamese Network | IEEE CG&A 2023 | Similarity feature fusion Siamese network | [Paper](https://ieeexplore.ieee.org/document/10153461) |
| Explainable Coarse-to-Fine Ancient Manuscript Duplicates Discovery, OBD-Finder | arXiv 2025 | Duplicate discovery | [arXiv](https://arxiv.org/abs/2505.03836) |
| Deep Rejoining Model and Dataset of Oracle Bone Fragment Images | npj Heritage Science 2025 | Deep fragment rejoining | [Paper](https://www.nature.com/articles/s40494-025-01651-9) |
| A Multi-modal Dataset and Method for Bone-level Association Prediction in Oracle Bone Inscriptions | npj Heritage Science 2026 | Bone-level association | [Paper](https://www.nature.com/articles/s40494-025-02282-w), [Code](https://github.com/Borisfwyy/SGBSAP) |

## Restoration, Inpainting, Augmentation, and Generation

| Paper | Venue and Year | Focus | Links |
| :--- | :---: | :--- | :--- |
| Dynamic Dataset Augmentation for Deep Learning-based Oracle Bone Inscriptions Recognition | ACM JOCCH 2022 | GAN-based dynamic augmentation | [Paper](https://dl.acm.org/doi/abs/10.1145/3532868) |
| RCRN: Real-world Character Image Restoration Network via Skeleton Extraction | ACM MM 2022 | Character image restoration | [Paper](https://dl.acm.org/doi/10.1145/3503161.3548344), [Code](https://github.com/daqians/Noisy-character-image-benchmark) |
| Large Kernel Convolutional Attention Based U-Net Network for Inpainting Oracle Bone Inscription | PRCV 2023 | U-Net inpainting | [Paper](https://doi.org/10.1007/978-981-99-8552-4_10) |
| Coarse-to-Fine Generative Model for Oracle Bone Inscriptions Inpainting | ML4AL @ ACL 2024 | GAN-based inpainting | [Paper](https://aclanthology.org/2024.ml4al-1.12/) |
| Oracle Bone Heritage Data Augmentation Based on Two-stage Decomposition GANs | npj Heritage Science 2025 | Two-stage decomposition GAN | [Paper](https://www.nature.com/articles/s40494-025-01774-z) |
| Oracle Bone Inscription Image Restoration via Glyph Extraction | npj Heritage Science 2025 | Glyph-driven restoration | [Paper](https://www.nature.com/articles/s40494-025-01795-8) |
| OBIFormer: A Fast Attentive Denoising Framework for Oracle Bone Inscriptions | Displays 2025, arXiv 2025 | Denoising and restoration | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0141938225000964), [arXiv](https://arxiv.org/abs/2504.13524), [Code](https://github.com/OBI-Future/OBIFormer) |
| Glyph Graph Isomorphism Network for Structure Recognition of Oracle Bone Inscription | Expert Systems with Applications 2026 | Glyph-graph structure recognition | [Paper](https://doi.org/10.1016/j.eswa.2025.129519) |
| Orpaint: A Zero-shot Inpainting Model for Oracle Bone Inscription Rubbings with Visual Mamba Block | SCIS 2025 | Zero-shot diffusion inpainting | [Paper](https://link.springer.com/article/10.1007/s11432-024-4493-4) |
| Multi-modal Ancient Scripts Recognition via Deep Learning with Data Homogenization and Augmentation | npj Heritage Science 2025 | Cross-modal data homogenization | [Paper](https://www.nature.com/articles/s40494-025-02095-x) |
| Generating Oracle Bone Inscriptions Based on the Structure-aware Diffusion Model | npj Heritage Science 2025 | Structure-aware diffusion generation | [Paper](https://www.nature.com/articles/s40494-025-02000-6) |
| OraGAN: A Deep Learning Based Model for Restoring Oracle Bone Script Images | npj Heritage Science 2025 | OBS restoration | [Paper](https://www.nature.com/articles/s40494-025-02195-8) |
| Restoration of Oracle Bone Inscriptions Using a Fast Residual Shrinkage Denoising Network with Fractal Gradient | npj Heritage Science 2026 | Fast residual shrinkage denoising | [Paper](https://www.nature.com/articles/s40494-026-02361-6) |

## Ancient Script and Chinese Character Evolution Beyond OBI

| Paper | Venue and Year | Focus | Links |
| :--- | :---: | :--- | :--- |
| CoLa: Chinese Character Decomposition with Compositional Latent Components | arXiv 2025 | Compositional decomposition | [arXiv](https://arxiv.org/abs/2506.03798) |
| Bridging Vision, Language, and Mathematics: Pictographic Character Reconstruction with Bézier Curves | arXiv 2025 | Geometric reconstruction with Bézier curves | [arXiv](https://arxiv.org/abs/2511.00076) |
| UniCalli: A Unified Diffusion Framework for Column-Level Generation and Recognition of Chinese Calligraphy | arXiv 2025 | Chinese calligraphy generation and recognition | [arXiv](https://arxiv.org/abs/2510.13745) |
| From Edges to Meaning: Semantic Line Sketches as a Cognitive Scaffold for Ancient Pictograph Invention | arXiv 2026 | Cognitive scaffold for pictograph invention | [arXiv](https://arxiv.org/abs/2604.12865) |
| Enhancing Multimodal Large Language Models for Ancient Chinese Character Evolution Analysis via Glyph-Driven Fine-Tuning | arXiv 2026 | Glyph-driven MLLM fine-tuning | [arXiv](https://arxiv.org/abs/2604.11299) |

---

## Notes for Contributors

- Prefer official paper, publisher, arXiv, OpenReview, code, and dataset pages.
- If a paper spans multiple tasks, list it in the most representative section and optionally cross-reference it elsewhere.
- Please keep rows concise: one-line focus, stable links, and venue and year when known.
