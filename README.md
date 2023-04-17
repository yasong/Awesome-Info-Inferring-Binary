# Awesome-Info-Inferring-Binary
### A collection of papers, tools about type inferring, variable renaming, function name inferring on stripped binary executables.

## Papers
|    Paper        |    Venue     | Year |     Slide      |       Video      |       Source Code       | Dataset                |
| :-------------: | :----------: | :--: |  :-----------: | :--------------: | :---------------------: |:---------------------: |
| [CFG2VEC: Hierarchical Graph Neural Network for Cross-Architectural Software Reverse Engineering](https://arxiv.org/pdf/2301.02723.pdf)| ICSE | 2023| S | V | [CFG2VEC](https://github.com/AICPS/mindsight_cfg2vec) | |
| A Transformer-based Function Symbol Name Inference Model from an Assembly Language for Binary Reversing | AsiaCCS | 2023 | S | V | [AsmDepictor](https://github.com/agwaBom/AsmDepictor) | D |
| [SymLM: Predicting Function Names in Stripped Binaries via Context-Sensitive Execution-Aware Code Embeddings](https://xinjin95.github.io/assets/pdf/SymLM_ccs2022_paper.pdf) | CCS | 2022 | S | V | [SymLM](https://github.com/OSUSecLab/SymLM) | [SymLM](https://github.com/OSUSecLab/SymLM) |
| [DnD: A Cross-Architecture Deep Neural Network Decompiler](https://wuruoyu.github.io/assets/pdf/dnd.pdf) | Usenix Sec | 2022 | S | V | [DnD](https://github.com/purseclab/DnD) | D |
| [DIRECT : A Transformer-based Model for Decompiled Variable Name Recovery](https://aclanthology.org/2021.nlp4prog-1.6.pdf) | nlp4prog | 2021 | S | V | [DIRECT-nlp4prog](https://github.com/DIRECT-team/DIRECT-nlp4prog) | [D](https://drive.google.com/drive/folders/19Rf7NtW56r6fz-ycldZq9hjxNr5osAJW?usp=sharing)|
| [XFL: Naming Functions in Binaries with Extreme Multi-label Learning](https://arxiv.org/pdf/2107.13404.pdf) | S&P(Arxiv) | 2023(2021) | S |  V | [XFL](https://github.com/lmu-plai/xfl) | D |
| [Variable Name Recovery in Decompiled Binary Code using Constrained Masked Language Modeling](https://arxiv.org/pdf/2103.12801.pdf) | Arxiv | 2021 | S |  V | G | D |
| [DIRTY: Augmenting Decompiler Output with Learned Variable Names and Types](https://www.usenix.org/system/files/sec22summer_chen-qibin.pdf) | Usenix Sec | 2022 | S |  V | [DIRTY](https://github.com/CMUSTRUDEL/DIRTY) \| [Demo](https://dirtdirty.github.io/explorer.html) | D |
| [A Lightweight Framework for Function Name Reassignment Based on Large-Scale Stripped Binaries](https://dl.acm.org/doi/10.1145/3460319.3464804) | ISSTA | 2021 | S | V | [NFRE](https://github.com/USTC-TTCN/NFRE)| D |
| [StateFormer: Fine-Grained Type Recovery from Binaries using Generative State Modeling](https://www.cs.columbia.edu/~suman/docs/stateformer.pdf) | ESEC/FSE | 2021 | S | V | [StateFormer](https://github.com/CUMLSec/stateformer) | D |
| [OSPREY: Recovery of Variable and Data Structure via Probabilistic Analysis for Stripped Binary](https://www.cs.purdue.edu/homes/zhan3299/res/SP21a.pdf) | S&P (Oakland) | 2021 | S | [V](https://youtu.be/RugYdcF8-uc) | OSPREY| D |
| [Devil Is Virtual: Reversing Virtual Inheritance in C++ Binaries](https://arxiv.org/abs/2003.05039v1) | CCS | 2020 | S | V | G | D |
| [Neural reverse engineering of stripped binaries using augmented control flow graphs](https://arxiv.org/abs/1902.09122v4)| OOPLSA | 2020 | [S](https://www.cs.technion.ac.il/~biham/Workshops/Cyberday/2020/Slides/yaniv-david.slides.pdf) | V| [Nero](https://github.com/tech-srl/Nero) | D |
| [CATI: Context-Assisted Type Inference from Stripped Binaries](https://ieeexplore.ieee.org/document/9153442) | DSN | 2020 | S | V | G | D |
| [Typilus: Neural Type Hints](https://export.arxiv.org/abs/2004.10657) | PLDI | 2020 | S | V | [Typilus](https://github.com/JetBrains-Research/typilus) | D |
| [In Nomine Function: Naming Functions in Stripped Binaries with Neural Networks](https://arxiv.org/abs/1912.07946v2)| Arxiv | 2019 | S | V | [in_nomine_function](https://github.com/lucamassarelli/in_nomine_function) | D |
| [DIRE: A Neural Approach to Decompiled Identifier Naming](https://ieeexplore.ieee.org/document/8952404) | ASE | 2019 | S | V | [Dire](https://github.com/pcyin/dire)| [D](https://zenodo.org/record/3403078#.YZxV7j5Bzep) |
| [Type Learning for Binaries and its Applications](https://ieeexplore.ieee.org/document/8588310) | IEEETR | 2019 | S | V | [BITY](https://github.com/wcventure/BITY) | D |
| [DeClassifier: Class-Inheritance Inference Engine for Optimized C++ Binaries](https://arxiv.org/pdf/1901.10073.pdf) | AsiaCCS | 2019 | S | V | DeClassifier | D |
| [DEBIN:Predicting Debug Information in Stripped Binaries](https://files.sri.inf.ethz.ch/website/papers/ccs18-debin.pdf) | CCS | 2018 | S | V | [DEBIN](https://github.com/eth-sri/debin) \| [debin.ai](https://debin.ai/) | D |
| [Meaningful variable names for decompiled code: a machine translation approach](https://dl.acm.org/doi/10.1145/3196321.3196330) | ICPC | 2018 | S | V | G | D |
| [Neural Nets Can Learn Function Type  Signatures From Binaries](https://www.usenix.org/conference/usenixsecurity17/technical-sessions/presentation/chua) | Usenix Sec | 2017 | S | [V](https://youtu.be/eCF002qNntk) | [EKLAVYA](https://github.com/shensq04/EKLAVYA) | [binary.tar.gz](https://drive.google.com/file/d/0B2qBKMQRQLHGS1JESVQ0TlF1eWs/view?usp=sharing&resourcekey=0-8RY3CA6LaeP739W42Yji7w), [pickles.tar.gz](https://drive.google.com/file/d/0B2qBKMQRQLHGdGpuTUlmMmZJYXM/view?usp=sharing&resourcekey=0-kHnq_w-Cj9OYx1MfI84x4Q), [clean_pickles.tar.gz](https://drive.google.com/file/d/0B2qBKMQRQLHGOFphWjkzcnV2LTQ/view?usp=sharing&resourcekey=0-5O0MUnDLYMdW_Hx0VjAQ2Q) |
| [DSIbin: Identifying Dynamic Data Structures in C/C++ Binaries](https://www.swt-bamberg.de/luettgen/publications/pdf/ASE2017.pdf) | ASE | 2017 | S | V | [DSIbin](https://github.com/uniba-swt/DSIbin) | D |
| [A Tough call: Mitigating Advanced Code-Reuse Attacks At The Binary Level]()| S&P (Oakland) | 2016 | [S](https://vvdveen.com/publications/TypeArmor.slides.pdf) | V | [TypeArmor](https://github.com/vusec/typearmor) | D |
| [Type Inference on Executables](https://dl.acm.org/doi/10.1145/2896499) | ACMCS | 2016 | S | V | G | D |
| [Scalable variable and data type detection in a binary rewriter](https://dl.acm.org/doi/10.1145/2491956.2462165) | PLDI |  2013 | S | V | G | D |
| [TIE: Principled reverse engineering of types in binary programs](https://www.ndss-symposium.org/ndss2011/tie-principled-reverse-engineering-of-types-in-binary-programs/) | NDSS | 2011 | S | V | G | D |
| [Automatic Reverse Engineering of Data Structures from Binary Execution](https://www.ndss-symposium.org/ndss2010/automatic-reverse-engineering-data-structures-binary-execution/) | NDSS  | 2010 | S | V | G | D |

## Tools
- 2019 [in_nomine_function](https://github.com/lucamassarelli/in_nomine_function)
- 2019 [Dire](https://github.com/pcyin/dire) && [New URL](https://github.com/CMUSTRUDEL/DIRE) && [datasets](https://zenodo.org/record/3403078#.XtTi-TozaUk)
- 2018 [DEBIN](https://github.com/eth-sri/debin) && [debin.ai](https://debin.ai/)
- 2017 [EKLAVYA](https://github.com/shensq04/EKLAVYA)
- 2018 [decomp](https://github.com/decomp/decomp)

