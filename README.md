<h1 align="center">Open-Oracle</h1>

<h3 align="center"> This project aims to open-source Oracle-related datasets and methods.</a></h3>
<h2></h2> 

<h5 align="center"> Please give us a star ⭐ for the latest update.  </h5>

<h5 align="center">

[![Demo](https://img.shields.io/badge/Demo-blue)](http://vlrlab-monkey.xyz:7680/index/)

## News 
* ```2024.8.14 ``` 🚀 OBSD won the Best Paper Award of ACL 2024!.


## Overview

[1. An open dataset for oracle bone script recognition and decipherment [ArXiv-2024]](#HUST-OBC)

<a href="https://arxiv.org/pdf/2401.15365"><img  src="https://img.shields.io/badge/arxiv-Paper-brightgreen" ></a> <a href="https://github.com/Pengjie-W/HUST-OBC"><img src="https://img.shields.io/github/stars/Pengjie-W/HUST-OBC.svg?logo=github&label=Stars"></a>
<a href="https://figshare.com/s/8a9c0420312d94fc01e3"><img src="https://img.shields.io/badge/Data-yellow"></a>

[2. An open dataset for the evolution of oracle bone characters: EVOBC [ArXiv-2024]](#EVOBC)

<a href="https://arxiv.org/pdf/2401.12467"><img  src="https://img.shields.io/badge/arxiv-Paper-brightgreen" ></a> <a href="https://github.com/RomanticGodVAN/character-Evolution-Dataset"><img src="https://img.shields.io/github/stars/RomanticGodVAN/character-Evolution-Dataset.svg?logo=github&label=Stars"></a>
<a href="https://figshare.com/s/ce2cf55b35a2f8ecc4c6"><img src="https://img.shields.io/badge/Data-yellow"></a>

[3. Puzzle Pieces Picker: Deciphering Ancient Chinese Characters with Radical Reconstruction [ICDAR-2024]](#ACCP)

<a href="https://arxiv.org/pdf/2406.03019"><img  src="https://img.shields.io/badge/arxiv-Paper-brightgreen" ></a> <a href="https://github.com/Pengjie-W/Puzzle-Pieces-Picker"><img src="https://img.shields.io/github/stars/Pengjie-W/Puzzle-Pieces-Picker.svg?logo=github&label=Stars"></a>

[4. Deciphering Oracle Bone Language with Diffusion Models [ACL-2024]](#OBSD)

<a href="https://arxiv.org/abs/2406.00684"><img  src="https://img.shields.io/badge/arxiv-Paper-brightgreen" ></a> <a href="https://github.com/guanhaisu/OBSD"><img src="https://img.shields.io/github/stars/guanhaisu/OBSD.svg?logo=github&label=Stars"></a>

## Projects

### <span id="HUST-OBC">📘 An open dataset for oracle bone script recognition and decipherment [ArXiv-2024]</span>

<em>Wang, Pengjie and Zhang, Kaile and Liu, Yuliang and Wan, Jinpeng and Guan, Haisu and Kuang, Zhebin and Wang, Xinyu and Jin, Lianwen and Bai, Xiang</em>.

[Paper](https://arxiv.org/pdf/2401.15365) | [Github Code](https://github.com/Pengjie-W/HUST-OBC) 

We propose HUST-OBC dataset. This dataset encompasses 77,064 images of 1,588 individual deciphered characters and 62,989 images of 9,411 undeciphered characters, with a total of 140,053 images, compiled from diverse sources.
<img src="https://v1.ax1x.com/2024/08/15/7GMW2B.jpg" width="100%">

***

### <span id="EVOBC">📘 An open dataset for the evolution of oracle bone characters: EVOBC [ArXiv-2024]</span>

<em>Guan, Haisu and Wan, Jinpeng and Wang, Pengjie and Zhang, Kaile and Kuang, Zhebin and Wang, Xinyu and Shengwei, Han and Yongge Liu and Bai, Xiang and Jin, Lianwen and Liu, Yuliang</em>.

[Paper](https://arxiv.org/pdf/2401.12467) | [Github Code](https://github.com/RomanticGodVAN/character-Evolution-Dataset) 

we systematically collected ancient characters from authoritative texts and websites spanning six historical stages: Oracle Bone Characters-OBC (15th century B.C.), Bronze Inscriptions-BI (13th to 221 B.C.), Seal Script-SS (11th to 8th centuries B.C.), Spring and Autumn period Characters-SAC (770 to 476 B.C.), Warring States period Characters-WSC (475 B.C. to 221 B.C.), and Clerical Script-CS (221 B.C. to 220 A.D.). Subsequently, we constructed an extensive dataset, namely EVolution Oracle Bone Characters (EVOBC), consisting of 229,170 images representing 13,714 distinct character categories. We conducted validation and simulated deciphering on the constructed dataset, and the results demonstrate its high efficacy in aiding the study of oracle bone script. This openly accessible dataset aims to digitalize ancient Chinese scripts across multiple eras, facilitating the decipherment of oracle bone script by examining the evolution of glyph forms.
<img src="https://v1.ax1x.com/2024/08/15/7GMVUG.jpg" width="100%">

***


### <span id="ACCP">📘 Puzzle Pieces Picker: Deciphering Ancient Chinese Characters with Radical Reconstruction [ICDAR-2024]</span>

<em>Wang, Pengjie and Zhang, Kaile and Wang, Xinyu and Han, Shengwei and Liu, Yongge and Jin, Lianwen and Bai, Xiang and Liu, Yuliang</em>.

[Paper](https://arxiv.org/pdf/2406.03019) | [Github Code](https://github.com/Pengjie-W/Puzzle-Pieces-Picker) 

This paper introduces a novel approach, namely Puzzle Pieces Picker (P3), to decipher these enigmatic characters through radical reconstruction. We deconstruct OBI into foundational strokes and radicals, then employ a Transformer model to reconstruct them into their modern counterparts, offering a groundbreaking solution to ancient script analysis.
<img src="https://v1.ax1x.com/2024/08/15/7GMAyJ.png" width="100%">

***

### <span id="OBSD">📘 Deciphering Oracle Bone Language with Diffusion Models [ACL-2024]</span>

<em>Guan, Haisu and Yang, Huanxin and Wang, Xinyu and Han, Shengwei and Liu, Yongge and Jin, Lianwen and Bai, Xiang and Liu, Yuliang</em>.

[Paper](https://arxiv.org/pdf/2406.03019) | [Github Code](https://github.com/Pengjie-W/Puzzle-Pieces-Picker) 

This paper introduces a novel approach by adopting image generation techniques, specifically through the development of Oracle Bone Script Decipher (OBSD). Utilizing a conditional diffusion-based strategy, OBSD generates vital clues for decipherment, charting a new course for AI-assisted analysis of ancient
languages. To validate its efficacy, extensive experiments were conducted on an oracle bone script dataset, with quantitative results demonstrating the effectiveness of OBSD.
<img src="https://v1.ax1x.com/2024/08/15/7GMxoL.jpg" width="100%">

***
