<h1 align="center">
🧬📝 Awesome Bio-Foundation Models
</h1>
<div align="center">

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Stars](https://img.shields.io/github/stars/QizhiPei/Awesome-Biomolecule-Language-Cross-Modeling?color=yellow&labelColor=555555) 
</div>

The repository is a collection of awesome bio-foundation modeling papers, various domains include DNA, RNA, gene, protein, single-cell, and multimodalities.

🌟 **If you have a paper or resource you'd like to add, feel free to submit a pull request or open an issue.**

<p align="center">
  <img src="biofm.png" width="512">
</p>


## Table of Content
- [Models](#models)
  - [DNA & Gene](#dna--gene)
  - [RNA](#rna)
  - [Protein](#protein)
  - [Single-cell](#single-cell)
  - [Multimodalities](#multimodalities)
- [Datasets & Benchmarks](datasets--benchmarks)
- [Related Resources](#related-resources)
  - [Related Surveys & Evaluations](#related-surveys--evaluations) 
  - [Repositories](#related-repositories)
- [Acknowledgements](#acknowledgements)
---

## Models
### DNA & Gene

* **HyenaDNA: Long-Range Genomic Sequence Modeling at Single Nucleotide Resolution**
  
  [![](https://img.shields.io/badge/NeurIPS_2023-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://proceedings.neurips.cc/paper_files/paper/2023/file/86ab6927ee4ae9bde4247793c46797c7-Paper-Conference.pdf)
  ![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fbfd2b76998a0521c12903ef5ced517adf70ad2ba%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
  [![Stars](https://img.shields.io/github/stars/HazyResearch/hyena-dna?color=yellow&style=social)](https://github.com/HazyResearch/hyena-dna)
  [![Model](https://img.shields.io/badge/Model-5291C8?style=flat&logo=themodelsresource&labelColor=555555)](https://huggingface.co/LongSafari)
  
* **DNABERT: pre-trained Bidirectional Encoder Representations from Transformers model for DNA-language in genome**
  
  [![](https://img.shields.io/badge/Bioinformatics_2023-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://academic.oup.com/bioinformatics/article/37/15/2112/6128680)
  ![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fc43d9cade31600400a0f62beb5bbcc1b548e009e%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
  [![Stars](https://img.shields.io/github/stars/jerryji1993/DNABERT?color=yellow&style=social)](https://github.com/jerryji1993/DNABERT)
  [![Model](https://img.shields.io/badge/Model-5291C8?style=flat&logo=themodelsresource&labelColor=555555)](https://github.com/jerryji1993/DNABERT?tab=readme-ov-file#32-download-pre-trained-dnabert)

* **DNABERT-2: Efficient Foundation Model and Benchmark for Multi-Species Genome**
  
  [![](https://img.shields.io/badge/ICLR_2024-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/forum?id=oMLQB4EZE1&referrer=%5Bthe%20profile%20of%20Ramana%20V%20Davuluri%5D(%2Fprofile%3Fid%3D~Ramana_V_Davuluri1))
  ![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fd466fad9e1fe3edb1644d8ba8b906383c36abcea%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
  [![Stars](https://img.shields.io/github/stars/MAGICS-LAB/DNABERT_2?color=yellow&style=social)](https://github.com/MAGICS-LAB/DNABERT_2)
  [![Model](https://img.shields.io/badge/Model-5291C8?style=flat&logo=themodelsresource&labelColor=555555)](https://huggingface.co/zhihan1996/DNABERT-2-117M)

* **DNABERT-S: Learning Species-Aware DNA Embedding with Genome Foundation Models**
  
  [![](https://img.shields.io/badge/Arxiv_2024-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://arxiv.org/abs/2402.08777)
  ![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fbc8d58fcb7dbf6cc4942eda901a54412b2018a89%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
  [![Stars](https://img.shields.io/github/stars/MAGICS-LAB/DNABERT_S?color=yellow&style=social)](https://github.com/MAGICS-LAB/DNABERT_S)
  [![Model](https://img.shields.io/badge/Model-5291C8?style=flat&logo=themodelsresource&labelColor=555555)](https://huggingface.co/zhihan1996/DNABERT-S)


* **MoDNA: motif-oriented pre-training for DNA language model**
  
  [![](https://img.shields.io/badge/ACM_BCB_2022-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://dl.acm.org/doi/10.1145/3535508.3545512)
  ![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F485afddba6de9a5bc6e0104e0b1d463000415c60%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)

* **Species-aware DNA language modeling**
  
  [![](https://img.shields.io/badge/BioRxiv_2023-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.biorxiv.org/content/10.1101/2023.01.26.525670v1)
  ![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fc2a6c2b7c448840a398ba2c386eeedc537446165%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
  [![Stars](https://img.shields.io/github/stars/DennisGankin/species-aware-DNA-LM?color=yellow&style=social)](https://github.com/DennisGankin/species-aware-DNA-LM)
  
* **DNA language models are powerful predictors of genome-wide variant effects**
  
  [![](https://img.shields.io/badge/PNAS_2023-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.pnas.org/doi/abs/10.1073/pnas.2311219120?af=R)
  ![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F0a04d0f9ffc0d30157dea059abbf344c681908ed%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
  [![Stars](https://img.shields.io/github/stars/songlab-cal/gpn?color=yellow&style=social)](https://github.com/songlab-cal/gpn)
  







### RNA


### Protein
(also include antibody, peptide)
* **ProtTrans: Towards Cracking the Language of Life’s Code Through Self-Supervised Deep Learning and High Performance Computing**
  
  [![](https://img.shields.io/badge/bioRxiv_2020-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.pnas.org/doi/epdf/10.1073/pnas.2016239118)
  ![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fca9b4fc03ad3ea4680ab2204ecf215f333c616a4%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
  [![Stars](https://img.shields.io/github/stars/agemagician/ProtTrans?color=yellow&style=social)](https://github.com/agemagician/ProtTrans)
  [![Model](https://img.shields.io/badge/Model-5291C8?style=flat&logo=themodelsresource&labelColor=555555)](https://github.com/agemagician/ProtTrans)


* **Biological structure and function emerge from scaling unsupervised learning to 250 million protein sequences**
  
  [![](https://img.shields.io/badge/PNAS_2021-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.pnas.org/doi/epdf/10.1073/pnas.2016239118)
  ![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F18a93dc1558bf9d7534d0b416633cebaf75c1145%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
  [![Stars](https://img.shields.io/github/stars/facebookresearch/esm?color=yellow&style=social)](https://github.com/facebookresearch/esm)
  [![Model](https://img.shields.io/badge/Model-5291C8?style=flat&logo=themodelsresource&labelColor=555555)](https://github.com/facebookresearch/esm)

* **Language models of protein sequences at the scale of evolution enable accurate structure prediction**
  
  [![](https://img.shields.io/badge/bioRxiv_2022-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.biorxiv.org/content/10.1101/2022.07.20.500902v1.full.pdf)
  [![Stars](https://img.shields.io/github/stars/facebookresearch/esm?color=yellow&style=social)](https://github.com/facebookresearch/esm)
  [![Model](https://img.shields.io/badge/Model-5291C8?style=flat&logo=themodelsresource&labelColor=555555)](https://github.com/facebookresearch/esm)

* **ProLLaMA: A Protein Large Language Model for Multi-Task Protein Language Processing**
  
  [![](https://img.shields.io/badge/Arxiv_2024-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://arxiv.org/abs/2402.16445v1)
  ![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F1296d51001f8a73c0a3356f78b136a691928985c%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
  [![Stars](https://img.shields.io/github/stars/Lyu6PosHao/ProLLaMA?color=yellow&style=social)](https://github.com/Lyu6PosHao/ProLLaMA)
  [![Model](https://img.shields.io/badge/Model-5291C8?style=flat&logo=themodelsresource&labelColor=555555)](https://huggingface.co/GreatCaptainNemo/ProLLaMA)

* **Unified rational protein engineering with sequence-based deep representation learning**
  
  [![](https://img.shields.io/badge/Nature_Method_2019-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.nature.com/articles/s41592-019-0598-1)
  ![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F06eb3c3ccae16fced2222f8a45877906f54f2164%3Ffields%3DcitationCount&query=%859.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
  [![Stars](https://img.shields.io/github/stars/churchlab/UniRep?color=yellow&style=social)](https://github.com/churchlab/UniRep)


### Single-cell


### Multimodalities

* **Galactica: A Large Language Model for Science**
  
  [![](https://img.shields.io/badge/Arxiv_2022-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.nature.com/articles/s41467-023-36720-9)
  ![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F7d645a3fd276918374fd9483fd675c28e46506d1%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
  [![Stars](https://img.shields.io/github/stars/paperswithcode/galai?color=yellow&style=social)](https://github.com/paperswithcode/galai)
  [![Model](https://img.shields.io/badge/Model-5291C8?style=flat&logo=themodelsresource&labelColor=555555)](https://huggingface.co/models?other=galactica)

* **BioT5: Enriching Cross-modal Integration in Biology with Chemical Knowledge and Natural Language Associations**
  
  [![](https://img.shields.io/badge/EMNLP_2023-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.nature.com/articles/s41467-023-36720-9)
  ![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fc3382fd533b9dd7f8ed7ba7766159079bc1d3935%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
  [![Stars](https://img.shields.io/github/stars/QizhiPei/BioT5?color=yellow&style=social)](https://github.com/QizhiPei/BioT5)
  [![Model](https://img.shields.io/badge/Model-5291C8?style=flat&logo=themodelsresource&labelColor=555555)](https://huggingface.co/QizhiPei/biot5-base)

* **DARWIN Series: Domain Specific Large Language Models for Natural Science**
  
  [![](https://img.shields.io/badge/Arxiv_2023-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.nature.com/articles/s41467-023-36720-9)
  ![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F4c6fb350e7769cb730a15c62927b6e9b563d0157%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
  [![Stars](https://img.shields.io/github/stars/MasterAI-EAM/Darwin?color=yellow&style=social)](https://github.com/MasterAI-EAM/Darwin)
  [![Model](https://img.shields.io/badge/Model-5291C8?style=flat&logo=themodelsresource&labelColor=555555)](https://github.com/MasterAI-EAM/Darwin)

* **BioT5+: Towards Generalized Biological Understanding with IUPAC Integration and Multi-task Tuning**
  
  [![](https://img.shields.io/badge/Arxiv_2024-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.nature.com/articles/s41467-023-36720-9)
  ![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Ff740a2474b52675287166a003bd1313f8aabcd68%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
  [![Stars](https://img.shields.io/github/stars/QizhiPei/BioT5?color=yellow&style=social)](https://github.com/QizhiPei/BioT5)
  [![Model](https://img.shields.io/badge/Model-5291C8?style=flat&logo=themodelsresource&labelColor=555555)](https://github.com/QizhiPei/BioT5)

* **ChatCell: Facilitating Single-Cell Analysis with Natural Language**
  
  [![](https://img.shields.io/badge/Arxiv_2024-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.nature.com/articles/s41467-023-36720-9)
  ![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F6a3c0c897870c4f1897d2af0b88981fa2764359b%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
  [![Stars](https://img.shields.io/github/stars/zjunlp/ChatCell?color=yellow&style=social)](https://github.com/zjunlp/ChatCell)
  [![Model](https://img.shields.io/badge/Model-5291C8?style=flat&logo=themodelsresource&labelColor=555555)](https://huggingface.co/zjunlp)
  
## Datasets & Benchmarks

## Related Resources

### Related Surveys & Evaluations

### Related Repositories

## Acknowledgements
