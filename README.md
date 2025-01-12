<p align="center">
    <img src="https://s2.loli.net/2024/03/19/JnbZmeh18VsqkxF.png" width="250" style="margin-bottom: 0.2;"/>
<p>

<h3 align="center"> 
With the support of big data and AI, Oracle bone script research has entered a new era. This once obscure field is poised to reveal more secrets, offering valuable insights for deciphering other ancient scripts. We aim to open-source Oracle-related datasets and methods, but our efforts alone are not enough. We welcome the community's support to further advance the decoding of Oracle bone script.

<h5 align="center"> Please give us a star ⭐ for the latest update.  </h5>


## Overview
### Our Projects
[1. [ACL-2024 Oral-Best Paper] Deciphering Oracle Bone Language with Diffusion Models ](#OBSD)

[![Source_code](https://img.shields.io/badge/Code-Available-white)](https://github.com/guanhaisu/OBSD)

[2. [ICDAR-2024 Oral] Puzzle Pieces Picker: Deciphering Ancient Chinese Characters with Radical Reconstruction ](#ACCP)

[![Source_code](https://img.shields.io/badge/Code-Available-white)](https://github.com/Pengjie-W/Puzzle-Pieces-Picker)

[3. [ArXiv-2024] An open dataset for the evolution of oracle bone characters: EVOBC ](#EVOBC)

[![Source_code](https://img.shields.io/badge/Code-Available-white)](https://github.com/RomanticGodVAN/character-Evolution-Dataset)
<a href="https://figshare.com/s/ce2cf55b35a2f8ecc4c6"><img src="https://img.shields.io/badge/Data-yellow"></a>

[4. [Scientific Data 2024] An open dataset for oracle bone script recognition and decipherment ](#HUST-OBC)

[![Source_code](https://img.shields.io/badge/Code-Available-white)](https://github.com/Pengjie-W/HUST-OBC)
<a href="https://figshare.com/s/8a9c0420312d94fc01e3"><img src="https://img.shields.io/badge/Data-yellow"></a>
[![Download Dataset](https://img.shields.io/badge/hyper.ai-pink)](https://hyper.ai/datasets/33506)

### Other Projects

[1. [ArXiv-2024] A Cross-Font Image Retrieval Network for Recognizing Undeciphered Oracle Bone Inscriptions ](#CFIRN)

[![Source_code](https://img.shields.io/badge/ArXiv-Paper-white)](https://arxiv.org/abs/2409.06381)

[2. [ArXiv-2024] OBI-Bench: Can LMMs Aid in Study of Ancient Script on Oracle Bones? ](#OBI-Bench)

[![Source_code](https://img.shields.io/badge/ArXiv-Paper-white)](https://arxiv.org/abs/2412.01175)
## Projects

### <span id="OBSD">📘 [ACL-2024 Best Paper] Deciphering Oracle Bone Language with Diffusion Models </span>

<em>Guan, Haisu and Yang, Huanxin and Wang, Xinyu and Han, Shengwei and Liu, Yongge and Jin, Lianwen and Bai, Xiang and Liu, Yuliang</em>.

[Paper](https://arxiv.org/pdf/2406.00684) | [Github Code](https://github.com/guanhaisu/OBSD) 

This paper introduces a novel approach by adopting image generation techniques, specifically through the development of Oracle Bone Script Decipher (OBSD). Utilizing a conditional diffusion-based strategy, OBSD generates vital clues for decipherment, charting a new course for AI-assisted analysis of ancient
languages. To validate its efficacy, extensive experiments were conducted on an oracle bone script dataset, with quantitative results demonstrating the effectiveness of OBSD.
<img src="https://v1.ax1x.com/2024/08/15/7GMxoL.jpg" width="100%">

If you wish to refer to the baseline results published here, please use the following BibTeX entries:
```BibTeX
@inproceedings{guan2024deciphering,
  title={Deciphering Oracle Bone Language with Diffusion Model},
  author={Guan, Haisu and Yang, Huanxin and Wang, Xinyu and Han, Shengwei and Liu, Yongge and Jin, Lianwen and Bai, Xiang and Liu, Yuliang},
  booktitle={Proceedings of the 62th Annual Meeting of the Association for Computational Linguistics},
  year={2024}
}
```
***


### <span id="ACCP">📘 [ICDAR-2024 Oral] Puzzle Pieces Picker: Deciphering Ancient Chinese Characters with Radical Reconstruction </span>

<em>Wang, Pengjie and Zhang, Kaile and Wang, Xinyu and Han, Shengwei and Liu, Yongge and Jin, Lianwen and Bai, Xiang and Liu, Yuliang</em>.

[Paper](https://arxiv.org/pdf/2406.03019) | [Github Code](https://github.com/Pengjie-W/Puzzle-Pieces-Picker) 

This paper introduces a novel approach, namely Puzzle Pieces Picker (P3), to decipher these enigmatic characters through radical reconstruction. We deconstruct OBI into foundational strokes and radicals, then employ a Transformer model to reconstruct them into their modern counterparts, offering a groundbreaking solution to ancient script analysis.
<img src="https://v1.ax1x.com/2024/08/15/7GMAyJ.png" width="100%">

If you wish to refer to the baseline results published here, please use the following BibTeX entries:
```BibTeX
@inproceedings{wang2024puzzle,
  title={Puzzle Pieces Picker: Deciphering Ancient Chinese Characters with Radical Reconstruction},
  author={Wang, Pengjie and Zhang, Kaile and Wang, Xinyu and Han, Shengwei and Liu, Yongge and Jin, Lianwen and Bai, Xiang and Liu, Yuliang},
  booktitle={International Conference on Document Analysis and Recognition},
  year={2024},
  organization={Springer}
}
```
***


### <span id="EVOBC">📘 [ArXiv-2024] An open dataset for the evolution of oracle bone characters: EVOBC </span>

<em>Guan, Haisu and Wan, Jinpeng and Wang, Pengjie and Zhang, Kaile and Kuang, Zhebin and Wang, Xinyu and Shengwei, Han and Yongge Liu and Bai, Xiang and Jin, Lianwen and Liu, Yuliang</em>.

[Paper](https://arxiv.org/pdf/2401.12467) | [Github Code](https://github.com/RomanticGodVAN/character-Evolution-Dataset) 

we systematically collected ancient characters from authoritative texts and websites spanning six historical stages: Oracle Bone Characters-OBC (15th century B.C.), Bronze Inscriptions-BI (13th to 221 B.C.), Seal Script-SS (11th to 8th centuries B.C.), Spring and Autumn period Characters-SAC (770 to 476 B.C.), Warring States period Characters-WSC (475 B.C. to 221 B.C.), and Clerical Script-CS (221 B.C. to 220 A.D.). Subsequently, we constructed an extensive dataset, namely EVolution Oracle Bone Characters (EVOBC), consisting of 229,170 images representing 13,714 distinct character categories. We conducted validation and simulated deciphering on the constructed dataset, and the results demonstrate its high efficacy in aiding the study of oracle bone script. This openly accessible dataset aims to digitalize ancient Chinese scripts across multiple eras, facilitating the decipherment of oracle bone script by examining the evolution of glyph forms.
<img src="https://v1.ax1x.com/2024/08/15/7GMVUG.jpg" width="100%">

If you wish to refer to the baseline results published here, please use the following BibTeX entries:
```BibTeX
@article{guan2024open,
  title={An open dataset for the evolution of oracle bone characters: EVOBC},
  author={Guan, Haisu and Wan, Jinpeng and Wang, Pengjie and Zhang, Kaile and Kuang, Zhebin and Wang, Xinyu and Shengwei, Han and Yongge Liu and Bai, Xiang and Jin, Lianwen and Liu, Yuliang},
  journal={arXiv preprint arXiv:2401.12467},
  year={2024}
}
```
***


### <span id="HUST-OBC">📘 [Scientific Data 2024] An open dataset for oracle bone script recognition and decipherment </span>

<em>Wang, Pengjie and Zhang, Kaile and Liu, Yuliang and Wan, Jinpeng and Guan, Haisu and Kuang, Zhebin and Wang, Xinyu and Jin, Lianwen and Bai, Xiang</em>.

[Paper](https://arxiv.org/pdf/2401.15365) | [Github Code](https://github.com/Pengjie-W/HUST-OBC) 

We propose HUST-OBC dataset. This dataset encompasses 77,064 images of 1,588 individual deciphered characters and 62,989 images of 9,411 undeciphered characters, with a total of 140,053 images, compiled from diverse sources.
<img src="https://v1.ax1x.com/2024/08/15/7GMW2B.jpg" width="100%">

If you wish to refer to the baseline results published here, please use the following BibTeX entries:
```BibTeX
@article{wang2024open,
  title={An open dataset for oracle bone script recognition and decipherment},
  author={Wang, Pengjie and Zhang, Kaile and Liu, Yuliang and Wan, Jinpeng and Guan, Haisu and Kuang, Zhebin and Wang, Xinyu and Jin, Lianwen and Bai, Xiang},
  journal={arXiv preprint arXiv:2401.15365},
  year={2024}
}
```
***
### <span id="CFIRN"> 📘 [ArXiv-2024] A Cross-Font Image Retrieval Network for Recognizing Undeciphered Oracle Bone Inscriptions </span>

<!-- *Zhicong Wu, Qifeng Su, Ke Gu, Xiaodong Shi*. -->

<em>Zhicong Wu, Qifeng Su, Ke Gu, Xiaodong Shi</em>.

[Paper](https://arxiv.org/pdf/2409.06381) 

This paper proposes a cross-font image retrieval network (CFIRN) to assist in deciphering Oracle Bone Inscriptions (OBI) by matching undeciphered OBI characters with characters from other script forms. The approach uses a siamese network framework to extract deep features from character images across various fonts. By incorporating a multiscale feature integration (MFI) module and multiscale refinement classifier (MRC), CFIRN effectively retrieves and matches characters from three ancient scripts: Bronze Inscription (BI), Bamboo Slip Inscription (BSI), and Clerical Script (CS). Extensive experiments demonstrate the efficacy of CFIRN, advancing the recognition of undeciphered OBI characters.

<a href="https://imgse.com/i/pAudgT1"><img src="https://s21.ax1x.com/2024/09/15/pAudgT1.png" alt="pAudgT1.png" border="0" /></a>

If you wish to refer to the baseline results published here, please use the following BibTeX entries:

```BibTeX
@article{wu2024cross,
  title={A Cross-Font Image Retrieval Network for Recognizing Undeciphered Oracle Bone Inscriptions},
  author={Wu, Zhicong and Su, Qifeng and Gu, Ke and Shi, Xiaodong},
  journal={arXiv preprint arXiv:2409.06381},
  year={2024}
}
```
***

### <span id="OBI-Bench"> 📘 [ArXiv-2024] OBI-Bench: Can LMMs Aid in Study of Ancient Script on Oracle Bones? </span>

<!-- *Zhicong Wu, Qifeng Su, Ke Gu, Xiaodong Shi*. -->

<em>Zijian Chen, Tingzhu Chen, Wenjun Zhang, Guangtao Zhai</em>.

[Paper](https://arxiv.org/abs/2412.01175) 


The paper introduces OBI-Bench, a comprehensive benchmark designed to evaluate large multi-modal models (LMMs) on oracle bone inscription (OBI) processing tasks. These tasks—recognition, rejoining, classification, retrieval, and deciphering—demand expert-level knowledge in deciphering ancient Chinese scripts. The benchmark comprises 5,523 images spanning diverse formats and historical contexts, testing both visual and cognitive abilities. Evaluations of 23 LMMs reveal significant challenges, with advanced models like GPT-4o achieving close to untrained human-level performance in deciphering but struggling in fine-grained perception tasks. OBI-Bench aims to advance domain-specific LMMs to assist experts in the study of ancient scripts, highlighting both their current capabilities and limitations.

<a href="https://imgse.com/i/pEPaQ4U"><img src="https://s21.ax1x.com/2025/01/12/pEPaQ4U.png" alt="pEPaQ4U.png" border="0" /></a>

If you wish to refer to the baseline results published here, please use the following BibTeX entries:

```BibTeX
@article{chen2024obi,
  title={OBI-Bench: Can LMMs Aid in Study of Ancient Script on Oracle Bones?},
  author={Chen, Zijian and Chen, Tingzhu and Zhang, Wenjun and Zhai, Guangtao},
  journal={arXiv preprint arXiv:2412.01175},
  year={2024}
}
```
***
## Copyright
We welcome suggestions to help us improve the Open-Oracle. For any query, please contact Prof. Yuliang Liu: ylliu@hust.edu.cn. If you find something interesting, please also feel free to share with us through email or open an issue. Thanks!
