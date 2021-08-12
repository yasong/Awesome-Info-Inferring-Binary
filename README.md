# awesome-type-infer
### A collection of papers, tools about type inferring, variable renaming, function name inferring on stripped binary executables.

## Papers
- [ISSTA 2021]: [A Lightweight Framework for Function Name Reassignment
Based on Large-Scale Stripped Binaries](https://dl.acm.org/doi/10.1145/3460319.3464804).--[[NFRE]](https://github.com/USTC-TTCN/NFRE)
- [ESEC/FSE 2021]: [StateFormer: Fine-Grained Type Recovery from Binaries using Generative State Modeling](https://www.cs.columbia.edu/~suman/docs/stateformer.pdf).--[[StateFormer]](https://github.com/CUMLSec/stateformer)
- [S&P 2021]: [OSPREY: Recovery of Variable and Data Structure via Probabilistic Analysis for Stripped Binary](https://www.cs.purdue.edu/homes/zhan3299/res/SP21a.pdf).--[[OSPREY]]()
- [CCS 2020]: [Devil Is Virtual: Reversing Virtual Inheritance in C++ Binaries](https://arxiv.org/abs/2003.05039v1).
- [OOPLSA 2020]: [Neural reverse engineering of stripped binaries using augmented control flow graphs](https://arxiv.org/abs/1902.09122v4).--[[Nerp]](https://github.com/tech-srl/Nero)
- [DSN 2020]: [CATI: Context-Assisted Type Inference from Stripped Binaries](https://ieeexplore.ieee.org/document/9153442).
- [PLDI 2020]: [Typilus: Neural Type Hints](https://export.arxiv.org/abs/2004.10657).
- [Arxiv 2019]: [In Nomine Function: Naming Functions in Stripped Binaries with Neural Networks](https://arxiv.org/abs/1912.07946v2).--[[in_nomine_function]](https://github.com/lucamassarelli/in_nomine_function)
- [ASE 2019]: [DIRE: A Neural Approach to Decompiled Identifier Naming](https://ieeexplore.ieee.org/document/8952404).--[[Dire]](https://github.com/pcyin/dire)
- [IEEETR 2019]: [Type Learning for Binaries and its Applications](https://ieeexplore.ieee.org/document/8588310).--[[BITY]](https://github.com/wcventure/BITY)
- [CCS 2018]: [DEBIN:Predicting Debug Information in Stripped Binaries](https://files.sri.inf.ethz.ch/website/papers/ccs18-debin.pdf).--[[DEBIN]](https://github.com/eth-sri/debin) && [debin.ai](https://debin.ai/)
- [ICPC 2018]: [Meaningful variable names for decompiled code: a machine translation approach](https://dl.acm.org/doi/10.1145/3196321.3196330).
- [USENIX 2017]: [Neural Nets Can Learn Function Type  Signatures From Binaries](https://www.usenix.org/conference/usenixsecurity17/technical-sessions/presentation/chua).--[[EKLAVYA]](https://github.com/shensq04/EKLAVYA)
- [ACMCS 2016]: [Type Inference on Executables](https://dl.acm.org/doi/10.1145/2896499).
- [PLDI 2013]: [Scalable variable and data type detection in a binary rewriter](https://dl.acm.org/doi/10.1145/2491956.2462165).
- [NDSS 2011]: [TIE: Principled reverse engineering of types in binary programs](https://www.ndss-symposium.org/ndss2011/tie-principled-reverse-engineering-of-types-in-binary-programs/).
- [NDSS 2010]: [Automatic Reverse Engineering of Data Structures from Binary Execution](https://www.ndss-symposium.org/ndss2010/automatic-reverse-engineering-data-structures-binary-execution/).

## Tools
- 2019 [in_nomine_function](https://github.com/lucamassarelli/in_nomine_function)
- 2019 [Dire](https://github.com/pcyin/dire) && [New URL](https://github.com/CMUSTRUDEL/DIRE) && [datasets](https://zenodo.org/record/3403078#.XtTi-TozaUk)
- 2018 [DEBIN](https://github.com/eth-sri/debin) && [debin.ai](https://debin.ai/)
- 2017 [EKLAVYA](https://github.com/shensq04/EKLAVYA)
- 2018 [decomp](https://github.com/decomp/decomp)


|                           Year | Approach           | Venue    | Analysis |   |   | Open Source                        |
|--------------------------------|--------------------|----------|----------|---|---|------------------------------------|
| 2010                           | REWARDS \[ \]      | NDSS     | D        |   |   |                                    |
| 2011                           | TIE \[ \]          | S&P      | S        |   |   |                                    |
| 2011                           | Howard \[ \]       | NDSS     | D        |   |   |                                    |
| 2013                           | Phoenix \[ \]      | Usenix   |          |   |   |                                    |
| 2013                           | Compiler IR \[ \]  | PLDI     | S        |   |   |                                    |
| 2014                           | DREAM \[ \]        | NDSS     |          |   |   |                                    |
| 2014                           | ObJDIGGER \[ \]    | PPREW    |          |   |   |                                    |
| 2015                           | Argos \[ \]        | RAID     |          |   |   |                                    |
| 2016                           | DREAM\+\+ \[ \]    | S&P      |          |   |   |                                    |
| 2016                           | MemPick \[ ,  \]   | ESE/WCRE |          |   |   |                                    |
| 2016                           | Retypd \[ \]       | PLDI     |          |   |   |                                    |
| 2016                           | SLM \[ \]          | POPL     |          |   |   |                                    |
| 2016                           | DSI \[ \]          | ISSTA    |          |   |   |                                    |
| 2016                           | TypeArmor \[ \]    | CCS      |          |   |   |                                    |
| 2016                           | angr \[ \]         | S&P      |          |   |   |                                    |
| 2017                           | BITY \[ \]         | ICFEM    |          |   |   |                                    |
| 2017                           | EKLAVYA \[ \]      | Usenix   |          |   |   |                                    |
| 2017                           | DSIbin \[ \]       | ASE      |          |   |   |                                    |
| 2018                           | Debin \[ \]        | CCS      |          |   |   |                                    |
| 2018                           | ROCK \[ \]         | ASPLOS   |          |   |   |                                    |
| 2018                           | OOAnalyzer \[ \]   | CCS      |          |   |   |                                    |
| 2018                           | Naming \[ \]       | ICPC     |          |   |   |                                    |
| 2019                           | TypeMiner \[ \]    | DIMVA    |          |   |   |                                    |
| 2019                           | BITY \[ \]         | IEEETR   |          |   |   | https://github.com/wcventure/BITY  |
| 2019                           | DeClassifier \[ \] | CCS      |          |   |   |                                    |
| 2019                           | Coda \[ \]         | NeurIPS  |          |   |   |                                    |
| 2019                           | DIRE \[ \]         | ASE      |          |   |   |                                    |
| 2020                           | Typilus \[ \]      | PLDI     |          |   |   |                                    |
| 2020                           | CATI \[ \]         | DSN      |          |   |   |                                    |
| 2020                           | Nero \[ \]         | OOPSLA   |          |   |   | https://github.com/tech-srl/Nero   |
| 2020                           | VirtAnalyzer \[ \] | CCS      |          |   |   |                                    |
| 2021                           | OSPREY \[ \]       | S&P      | S        |   |   |                                    |
| 2021                           | NFRE \[ \]         | ISSTA    |          |   |   | https://github.com/USTC-TTCN/NFRE  |
| 2021                           | StateFormer \[ \]  | ESEC\FSE |          |   |   | https://github.com/CUMLSec/stateformer |



- [1] 	Lin, Zhiqiang, Xiangyu Zhang, and Dongyan Xu. 2010. “Automatic Reverse Engineering of Data Structures from Binary Execution.” In NDSS.
- [2]	Lee, JongHyup, Thanassis Avgerinos, and David Brumley. 2011. “TIE: Principled Reverse Engineering of Types in Binary Programs.” In NDSS.
- [3] 	Slowinska, J.M., T. Stancescu, and H.J. Bos. 2011. “Howard: A Dynamic Excavator for Reverse Engineering Data Structures.” In NDSS 2011.
- [4] 	Schwartz, Edward J., JongHyup Lee, Maverick Woo, and David Brumley. 2013. “Native ×86 Decompilation Using Semantics-Preserving Structural Analysis and Iterative Control-Flow Structuring.” In SEC’13 Proceedings of the 22nd USENIX Conference on Security, 353–68.
- [5] 	ElWazeer, Khaled, Kapil Anand, Aparna Kotha, Matthew Smithson, and Rajeev Barua. 2013. “Scalable Variable and Data Type Detection in a Binary Rewriter.” In Proceedings of the 34th ACM SIGPLAN Conference on Programming Language Design and Implementation, 48:51–60.
- [6]	Yakdan, Khaled, Sebastian Eschweiler, Elmar Gerhards-Padilla, and Matthew Smith. 2015. “No More Gotos: Decompilation Using Pattern-Independent Control-Flow Structuring and Semantics-Preserving Transformations.” In Network and Distributed System Security Symposium.
- [7] 	Jin, Wesley, Cory Cohen, Jeffrey Gennari, Charles Hines, Sagar Chaki, Arie Gurfinkel, Jeffrey Havrilla, and Priya Narasimhan. 2014. “Recovering C++ Objects From Binaries Using Inter-Procedural Data-Flow Analysis.” In Proceedings of ACM SIGPLAN on Program Protection and Reverse Engineering Workshop 2014, 1–11.
- [8]	Zeng, Junyuan, and Zhiqiang Lin. 2015. “Towards Automatic Inference of Kernel Object Semantics from Binary Code.” In RAID 2015 Proceedings of the 18th International Symposium on Research in Attacks, Intrusions, and Defenses - Volume 9404, 538–61.
- [9]	Yakdan, Khaled, Sergej Dechand, Elmar Gerhards-Padilla, and Matthew Smith. 2016. “Helping Johnny to Analyze Malware: A Usability-Optimized Decompiler and Malware Analysis User Study.” In 2016 IEEE Symposium on Security and Privacy (SP), 158–77.
- [10] 	Haller, Istvan, Asia Slowinska, and Herbert Bos. 2016. “Scalable Data Structure Detection and Classification for C/C++ Binaries.” Empirical Software Engineering 21 (3): 778–810.
- [11] 	Haller, Istvan, Asia Slowinska, and Herbert Bos. 2013. “MemPick: High-Level Data Structure Detection in C/C++ Binaries.” In 2013 20th Working Conference on Reverse Engineering (WCRE), 32–41.
- [12] Noonan, Matt, Alexey Loginov, and David Cok. 2016. “Polymorphic Type Inference for Machine Code.” In Proceedings of the 37th ACM SIGPLAN Conference on Programming Language Design and Implementation, 51:27–41.
- [13] Katz, Omer, Ran El-Yaniv, and Eran Yahav. 2016. “Estimating Types in Binaries Using Predictive Modeling.” In Proceedings of the 43rd Annual ACM SIGPLAN-SIGACT Symposium on Principles of Programming Languages, 51:313–26.
- [14] White, David H., Thomas Rupprecht, and Gerald Lüttgen. 2016. “DSI: An Evidence-Based Approach to Identify Dynamic Data Structures in C Programs.” In Proceedings of the 25th International Symposium on Software Testing and Analysis, 259–69.
- [15] Veen, Victor van der, Enes Goktas, Moritz Contag, Andre Pawoloski, Xi Chen, Sanjay Rawat, Herbert Bos, Thorsten Holz, Elias Athanasopoulos, and Cristiano Giuffrida. 2016. “A Tough Call: Mitigating Advanced Code-Reuse Attacks at the Binary Level.” In 2016 IEEE Symposium on Security and Privacy (SP), 934–53.
- [16] Shoshitaishvili, Yan, Ruoyu Wang, Christopher Salls, Nick Stephens, Mario Polino, Andrew Dutcher, John Grosen, Siji Feng, Christophe Hauser, and Christopher Kruegel. 2016. “SOK: (State of) The Art of War: Offensive Techniques in Binary Analysis.” In 2016 IEEE Symposium on Security and Privacy (SP), 138–57.
- [17] Xu, Zhiwu, Cheng Wen, and Shengchao Qin. 2017. “Learning Types for Binaries.” In International Conference on Formal Engineering Methods, 430–46.
- [18]	Chua, Zheng Leong, Shiqi Shen, Prateek Saxena, and Zhenkai Liang. 2017. “Neural Nets Can Learn Function Type Signatures From Binaries.” In 26th {USENIX} Security Symposium ({USENIX} Security 17), 99–116.
- [19] Rupprecht, Thomas, Xi Chen, David H. White, Jan H. Boockmann, Gerald Lüttgen, and Herbert Bos. 2017. “DSIbin: Identifying Dynamic Data Structures in C/C++ Binaries.” In Proceedings of the 32nd IEEE/ACM International Conference on Automated Software Engineering, 331–41.
- [20]	He, Jingxuan, Pesho Ivanov, Petar Tsankov, Veselin Raychev, and Martin Vechev. 2018. “Debin: Predicting Debug Information in Stripped Binaries.” In CCS ’18 Proceedings of the 2018 ACM SIGSAC Conference on Computer and Communications Security, 1667–80.
- [21] Katz, Omer, Noam Rinetzky, and Eran Yahav. 2018. “Statistical Reconstruction of Class Hierarchies in Binaries.” In Proceedings of the Twenty-Third International Conference on Architectural Support for Programming Languages and Operating Systems, 53:363–76.
- [22] Schwartz, Edward J., Cory F. Cohen, Michael Duggan, Jeffrey Gennari, Jeffrey S. Havrilla, and Charles Hines. 2018. “Using Logic Programming to Recover C++ Classes and Methods from Compiled Executables.” In CCS ’18 Proceedings of the 2018 ACM SIGSAC Conference on Computer and Communications Security, 426–41.
- [23] Jaffe, Alan, Jeremy Lacomis, Edward J. Schwartz, Claire Le Goues, and Bogdan Vasilescu. 2018. “Meaningful Variable Names for Decompiled Code: A Machine Translation Approach.” In 2018 IEEE/ACM 26th International Conference on Program Comprehension (ICPC), 20–30.
- [24] Maier, Alwin, Hugo Gascon, Christian Wressnegger, and Konrad Rieck. 2019. “TypeMiner: Recovering Types in Binary Programs Using Machine Learning.” In International Conference on Detection of Intrusions and Malware, and Vulnerability Assessment, 288–308.
- [25] Erinfolami, Rukayat Ayomide, and Aravind Prakash. 2019. “DeClassifier: Class-Inheritance Inference Engine for Optimized C++ Binaries.” In Proceedings of the 2019 ACM Asia Conference on Computer and Communications Security, 28–40.
- [26] Fu, Cheng, Huili Chen, Haolan Liu, Xinyun Chen, Yuandong Tian, Farinaz Koushanfar, and Jishen Zhao. 2019. “Coda: An End-to-End Neural Program Decompiler.” In Advances in Neural Information Processing Systems, 32:3708–19.
- [27] Lacomis, Jeremy, Pengcheng Yin, Edward J. Schwartz, Miltiadis Allamanis, Claire Le Goues, Graham Neubig, and Bogdan Vasilescu. 2019. “DIRE: A Neural Approach to Decompiled Identifier Naming.” In Proceedings of the 34th IEEE/ACM International Conference on Automated Software Engineering, 628–39.
- [28] Allamanis, Miltiadis, Earl T. Barr, Soline Ducousso, and Zheng Gao. 2020. “Typilus: Neural Type Hints.” In Proceedings of the 41st ACM SIGPLAN Conference on Programming Language Design and Implementation, 91–105.
- [29] Chen, Ligeng, Zhongling He, and Bing Mao. 2020. “CATI: Context-Assisted Type Inference from Stripped Binaries.” In 2020 50th Annual IEEE/IFIP International Conference on Dependable Systems and Networks (DSN), 88–98.
- [30] Yaniv David, Uri Alon, and Eran Yahav. 2020. Neural reverse engineering of stripped binaries using augmented control flow graphs. Proc. ACM Program. Lang. 4, OOPSLA, Article 225 (November 2020), 28 pages. 
- [31] Erinfolami, Rukayat Ayomide, and Aravind Prakash. 2020. “Devil Is Virtual: Reversing Virtual Inheritance in C++ Binaries.” In Proceedings of the 2020 ACM SIGSAC Conference on Computer and Communications Security, 133–48.
- [32]	Zhuo Zhang, Yapeng Ye, Wei You, Guanhong Tao, Wen-chuan Lee, Yonghwi Kwon, Yousra Aafer, Xiangyu Zhang. 2021. OSPREY: Recovery of Variable and Data Structure via Probabilistic Analysis for Stripped Binary. Proceedings of the 42th IEEE Symposiums on Security and Privacy. (Oakland 2021).
- [33] Xu, Z., Wen, C., & Qin, S. 2018. Type Learning for Binaries and its Applications. IEEE Transactions on Reliability, 68(3), 893-912.
- [34] Gao, H., Cheng, S., Xue, Y., & Zhang, W. 2021. A lightweight framework for function name reassignment based on large-scale stripped binaries. In Proceedings of the 30th ACM SIGSOFT International Symposium on Software Testing and Analysis pp. 607–619.
- [35] K. Pei, J. Guan, M. Broughton, Z. Chen, S. Yao, D. Williams-King, V. Ummadisetty, J. Yang, B. Ray, and S. Jana. StateFormer: Fine-Grained Type Recovery from Binaries using Generative State Modeling. FSE 2021




