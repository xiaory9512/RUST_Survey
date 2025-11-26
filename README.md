# Rust Security & Verification Survey

A curated list of research papers on Rust programming language security, verification, and vulnerability detection.

## Table of Contents
- [Overview](#overview)
- [Research Areas](#research-areas)
- [Papers by Year](#papers-by-year)
- [Contributing](#contributing)
- [Citation Format](#citation-format)

## Overview

This repository maintains a comprehensive survey of academic research papers related to Rust programming language, with a focus on:
- Security vulnerability detection
- Type system analysis
- Formal verification
- Memory safety
- Concurrency bugs

**Total Papers:** X papers spanning 2020-2025

## Research Areas

### 🔍 Vulnerability Detection
Papers focusing on identifying security vulnerabilities in Rust programs.

### ✅ Formal Verification
Research on proving correctness of Rust code.

### 🔒 Type Safety
Studies on type system bugs and type confusion.

### ⚡ Concurrency & Memory Safety
Papers analyzing concurrent programming and memory safety guarantees.

---

## Papers by Year

### 2025

#### Type Confusion & Security

# Rust Security Research Survey

## 2025

1. **[`TYPEPULSE: Detecting Type Confusion Bugs in Rust Programs`](https://www.usenix.org/conference/usenixsecurity25/presentation/chen-hung-mao)**  
   Chen, H.-M., He, X., Wang, S., Zhang, X., & Sun, K., *USENIX Security (2025)*  
   
2. **[`Autoverus: Automated Proof Generation for Rust Code`](https://dl.acm.org/doi/pdf/10.1145/3763174)**  
   Yang, C., Li, X., Misu, M. R. H., et al.,  *OOPSLA 2025*, 9(OOPSLA2), 3454-3482  

3. **[`Benefits and drawbacks of adopting a secure programming language: Rust as a case study`](https://arxiv.org/pdf/2506.15648)**  
   Androutsopoulos, Georgios and Bianchi, Antonio. (2025), *arXiv preprint*, arXiv:2508.04295

4. **[`HALURust: Exploiting Hallucinations of Large Language Models to Detect Vulnerabilities in Rust`](https://arxiv.org/pdf/2503.10793)**  
   Luo, Yu and Zhou, Han and Zhang, Mengtao and De La Rosa, Dylan and Ahmed, Hafsa and Xu, Weifeng and Xu, Dianxiang, *arXiv preprint*, arXiv:2503.10793

5. **[`Safe4U: Identifying Unsound Safe Encapsulations of Unsafe Calls in Rust using LLMs`](https://doi.org/10.1145/3728890)**  
   Li, Huan, Bei Wang, Xing Hu, and Xin Xia, *Proceedings of the ACM on Software Engineering 2, no. ISSTA (2025): 457-480*

6. **[`Stack Filtering: Elevating Precision and Efficiency in Rust Pointer Analysis`](https://doi.org/10.5281/zenodo.13634201)**  
   Li, Wei, Dongjie He, Wenguang Chen, and Jingling Xue, *Proceedings of the 23rd ACM/IEEE International Symposium on Code Generation and Optimization (2025), pp. 331-346*

7. **[`Targeted Fuzzing for Unsafe Rust Code: Leveraging Selective Instrumentation`](https://arxiv.org/abs/2505.02464)**  
   Paa{\ss}en, David and Giesen, Jens-Rene and Davi, Lucas, *arXiv preprint arXiv:2505.02464 (2025)*

8. **[`Unlocking a New Rust Programming Experience: Fast and Slow Thinking with LLMs to Conquer Undefined Behaviors`](https://arxiv.org/abs/2503.02335)**  
   Jiang, Renshuang and Dong, Pan and Duan, Zhenling and Shi, Yu and Fang, Xiaoxiang and Ding, Yan and Ma, Jun and Zhao, Shuai and Jiang, Zhe, *arXiv preprint arXiv:2503.02335 (2025)*

9. **[`From Rust Till Run: Extending Memory Safety From Rust to Cryptographic Assembly`](https://dl.acm.org/doi/abs/10.1145/3764860.3768333)**  
   Caspin, Shai and Pimpalkhare, Nikhil and Levy, Amit, *Proceedings of the 13th Workshop on Programming Languages and Operating Systems (2025), pp. 108-117*

10. **[`Place Capability Graphs: A General-Purpose Model of Rust’s Ownership and Borrowing Guarantee`](https://doi.org/10.1145/3763122)**  
   Grannan, Zachary and Bily, Aurel and Fiala, Jonavs and Geer, Jasper and de Medeiros, Markus and Muller, Peter and Summers, Alexander J, *Proceedings of the 13th Workshop on Programming Languages and Operating Systems, OOPSLA2 (2025), pp. 2002-2029*

11. **[`Carapace: Static--Dynamic Information Flow Control in Rust`](https://doi.org/10.5281/zenodo.14915697)**  
   Beardsley, Vincent and Xiong, Chris and Lamba, Ada and Bond, Michael D, *Proceedings of the ACM on Programming Languages, OOPSLA1 (2025), pp. 364-392*

12. **[`Paralegal: Practical static analysis for privacy bugs`](https://www.usenix.org/conference/osdi25/presentation/adam)**  
   Adam, Justus and Zech, Carolyn and Zhu, Livia and Rajesh, Sreshtaa and Harbison, Nathan and Jethwa, Mithi and Crichton, Will and Krishnamurthi, Shriram and Schwarzkopf, Malte, *19th USENIX Symposium on Operating Systems Design and Implementation (2025), pp. 957-978*

13. **[`deepSURF: Detecting Memory Safety Vulnerabilities in Rust Through Fuzzing LLM-Augmented Harnesses`](https://doi.org/10.48550/arXiv.2506.15648)**  
   Androutsopoulos, Georgios and Bianchi, Antonio, *arXiv preprint arXiv:2506.15648 (2025)*

14. **[`Decompiling Rust: An Empirical Study of Compiler Optimizations and Reverse Engineering Challenges`](https://arxiv.org/abs/2507.18792)**  
   Zhou, Zixu, *arXiv preprint arXiv:2507.18792 (2025)*

15. **[`Detecting Memory Errors in Rust Programs Including Unsafe Foreign Code`](https://link.springer.com/chapter/10.1007/978-3-032-10444-1_11)**  
   Franceschi, Andrea and Galletta, Letterio and Degano, Pierpaolo, *International Conference on Software Engineering and Formal Methods (2025), pp. 167-184*

16. **[`Improving Software Reliability with Rust: Implementation for Enhanced Control Flow Checking Methods`](https://ieeexplore.ieee.org/abstract/document/10992995)**  
   Sini, Jacopo and Solouki, Mohammadreza Amel and Violante, Massimo and Di Natale, Giorgio, *Design, Automation & Test in Europe Conference (2025), pp. 1-7*

17. **[`SafeFFI: Efficient Sanitization at the Boundary Between Safe and Unsafe Code in Rust and Mixed-Language Applications`](https://arxiv.org/abs/2510.20688)**  
   Braunsdorf, Oliver and Lange, Tim and Hohentanner, Konrad and Horsch, Julian and Kinder, Johannes, *arXiv preprint arXiv:2510.20688 (2025)*

18. **[`Automatic Linear Resource Bound Analysis for Rust via Prophecy Potentials`](https://dl.acm.org/doi/pdf/10.1145/3720492)**
    Lian, Qihao and Wang, Di, *Proceedings of the ACM on Programming Languages, OOPSLA1 (2025)*

19. **[`LiteRSan: Lightweight Memory Safety Via Rust-specific Program Analysis and Selective Instrumentation`](https://arxiv.org/abs/2509.16389)**
    Xia, Tianrou and Huang, Kaiming and Yu, Dongyeon and Jeon, Yuseok and Zhou, Jie and Wu, Dinghao and Kim, Taegyu, *arXiv preprint arXiv:2509.16389 (2025)*

20. **[`Vest: Verified, secure, high-performance parsing and serialization for Rust`](https://www.andrew.cmu.edu/user/bparno/papers/vest.pdf)**
    Cai, Yi and Singh, Pratap and Lin, Zhengyao and Bosamiya, Jay and Gancher, Joshua and Surbatovich, Milijana and Parno, Bryan and Model, Reviewing, *Proceedings of the USENIX Security Symposium (2025)*

21. **[`Enhancing Type Safety in MPI with Rust: A Statically Verified Approach for RSMPI`](https://link.springer.com/chapter/10.1007/978-3-031-97196-9_11)**
    Iqbal, Nafees and Brown, Jed, *Workshop on Asynchronous Many-Task Systems and Applications (2025), pp. 133-139*

22. **[`rustc++: Facilitating Advanced Analysis of Rust Code`](https://dl.acm.org/doi/abs/10.1145/3722041.3723102)**
    Louka, Antonis and Portokalidis, Georgios and Athanasopoulos, Elias, *Proceedings of the 18th European Workshop on Systems Security (2025), pp. 63-69*

23. **[`Securing Mixed Rust with Hardware Capabilities`](https://www.comp.nus.edu.sg/~prateeks/papers/CapsLock.pdf)**
    Zhijingcheng Yu, Jason and Han, Fangqi and Choudhury, Kaustab and Carlson, Trevor E and Saxena, Prateek, *arXiv e-prints (2025)*

24. **[`Charon: an analysis framework for rust`](https://link.springer.com/chapter/10.1007/978-3-031-98685-7_18)**
    Ho, Son and Boisseau, Guillaume and Franceschino, Lucas and Prak, Yoann and Fromherz, Aymeric and Protzenko, Jonathan, *International Conference on Computer Aided Verification (2025), pp. 377-391*

25. **[`SBD: Securing safe rust automatically from unsafe rust`](https://www.sciencedirect.com/science/article/pii/S0167642325000206)**
    Li, Shaowen and Sato, Hiroyuiki, *Science of Computer Programming (2025), pp. 377-391*

26. **[`RUST: A Memory Leakage-Proof Way of Building Applications`](https://sarcouncil.com/2025/09/rust-a-memory-leakage-proof-way-of-building-applications)**
    Gadkari, Bhooshan Ravikumar, *Journal Of Engineering And Computer Sciences (2025), pp. 10-15*

27. **[`Demystifying Rust Unstable Features at Ecosystem Scale: Evolution, Propagation, and Mitigation`](https://ieeexplore.ieee.org/abstract/document/10919478)**
    Li, Chenghao and Wu, Yifei and Shen, Wenbo and Chang, Rui and Liu, Chengwei and Liu, Yang, *IEEE Transactions on Software Engineering (2025)*

28. **[`Demystifying Rust Unstable Features at Ecosystem Scale: Evolution, Propagation, and Mitigation`](https://ieeexplore.ieee.org/abstract/document/10919478](https://dl.acm.org/doi/10.1145/3735592)**
    Villani, Neven and Hostert, Johannes and Dreyer, Derek and Jung, Ralf, *Proceedings of the ACM on Programming Languages (2025), pp. 1019-1042*

29. **[`Bringing Memory Safety Close to the Wire`](https://dl.acm.org/doi/10.1145/3744969.3748444)**
    Giovannoni, Leonardo and Lettieri, Giuseppe and Procissi, Gregorio, *Proceedings of the ACM SIGCOMM 2025 Posters and Demos (2025), pp. 106-108*


### 2024

1. **[`Validating Memory Safety in Rust Binaries`](https://arxiv.org/pdf/2506.15648)**  
   Louka, Antonis, Antreas Dionysiou, and Elias Athanasopoulos, *IEEE Proceedings of the 17th European Workshop on Systems Security (2024), pp. 8-14*

2. **[`Crabtree: Rust API Test Synthesis Guided by Coverage and Type`](https://doi.org/10.5281/zenodo.13626235)**  
   Takashima, Yoshiki, Chanhee Cho, Ruben Martins, Limin Jia, and Corina S. Păsăreanu, *Proceedings of the ACM on Programming Languages 8, no. OOPSLA2 (2024): 618-647.*
   
3. **[`Understanding and detecting real-world safety issues in Rust`](https://ieeexplore.ieee.org/abstract/document/10479047)**  
   Qin, Boqin and Chen, Yilun and Liu, Haopeng and Zhang, Hua and Wen, Qiaoyan and Song, Linhai and Zhang, Yiying, *IEEE Transactions on Software Engineering 50, no. 6 (2024): 1306-1324*

4. **[`Understanding the Challenges in Detecting Vulnerabilities of Rust Applications`](https://ieeexplore.ieee.org/abstract/document/10734062)**  
   Stephens, Diane B., Kawkab Aldoshan, and Mustakimur Rahman Khandaker, *IEEE Secure Development Conference (SecDev), (2024), pp. 54-63*.

5. **[`Yuga Automatically Detecting Lifetime Annotation Bugs in the Rust Language`](https://arxiv.org/abs/2310.08507)**  
   Nitin, Vikram and Mulhern, Anne and Arora, Sanjay and Ray, Baishakhi, *IEEE Transactions on Software Engineering 2024), pp. 2602–2613*.

6. **[`RustSan Retrofitting AddressSanitizer for Efficient Sanitization of Rust`](https://www.usenix.org/conference/usenixsecurity24/presentation/cho-kyuwon)**  
   Cho, Kyuwon and Kim, Jongyoon and Duy, Kha Dinh and Lim, Hajeong and Lee, Hojoon, 2024, *USENIX Security 2024), pp. 3729-3746*.

7. **[`FRIES: Fuzzing Rust Library Interactions via Efficient Ecosystem-Guided Target Generation`](https://doi.org/10.1145/3650212.368034)**  
   Yin, Xizhe and Feng, Yang and Shi, Qingkai and Liu, Zixi and Liu, Hongwang and Xu, Baowen, *Proceedings of the 33rd ACM SIGSOFT International Symposium on Software Testing and Analysis 2024), pp. 1137-1148*.

8. **[`Rust-twins: Automatic rust compiler testing through program mutation and dual macros generation`](https://doi.org/10.1145/3691620.3695059)**  
   Yang, Wenzhang and Gao, Cuifeng and Liu, Xiaoyuan and Li, Yuekang and Xue, Yinxing, *Proceedings of the 39th IEEE/ACM International Conference on Automated Software Engineering 2024), pp. 631-642*.

9. **[`Semi-Automated Verification of Interior Unsafe Code Encapsulation in Real-World Rust Systems`](https://doi.org/10.1145/3691620.3695373)**  
   Rao, Zihao, *Proceedings of the 39th IEEE/ACM International Conference on Automated Software Engineering 2024), pp. 2435-2437*.

10. **[`Erasan: Efficient rust address sanitizer`](https://ieeexplore.ieee.org/document/10646812)**  
   Min, Jiun and Yu, Dongyeon and Jeong, Seongyun and Song, Dokyung and Jeon, Yuseok, *IEEE Symposium on Security and Privacy (SP) 2024), pp. 4053-4068*.

11. **[`Cocoon: Static information flow control in rust`](https://doi.org/10.1145/3649817)**  
   Lamba, Ada and Taylor, Max and Beardsley, Vincent and Bambeck, Jacob and Bond, Michael D and Lin, Zhiqiang, *Proceedings of the ACM on Programming Languages, OOPSLA1 (2024), pp. 166-193*.

12. **[`Static-Dynamic Information Flow Control in Rust`](https://doi.org/10.1145/3689491.3691820)**  
   Beardsley, Vincent, *Companion Proceedings of the 2024 ACM SIGPLAN International Conference on Systems, Programming, Languages, and Applications: Software for Humanity (2024), pp. 16-18*

13. **[`Formally understanding Rust’s ownership and borrowing system at the memory level`](https://link.springer.com/article/10.1007/s10703-024-00460-3)**  
   Kan, Shuanglong and Chen, Zhe and Sanan, David and Liu, Yang, *Formal Methods in System Design (2024), pp. 200-236*

14. **[`RPG: Rust library fuzzing with pool-based fuzz target generation and generic support`](https://doi.org/10.1145/3597503.3639102)**  
   Xu, Zhiwu and Wu, Bohao and Wen, Cheng and Zhang, Bin and Qin, Shengchao and He, Mengda, *Proceedings of the IEEE/ACM 46th International Conference on Software Engineering (2024), pp. 1-13*

15. **[`Reasoning about Interior Mutability in Rust using Library-Defined Capabilities`](https://doi.org/10.48550/arXiv.2405.08372)**  
   Poli, Federico and Denis, Xavier and Muller, Peter and Summers, Alexander J, *arXiv preprint arXiv:2405.08372 (2024)*

16. **[`UnsafeCop: Towards Memory Safety for Real-World Unsafe Rust Co de with Practical Bounded Model Checking`](https://link.springer.com/chapter/10.1007/978-3-031-71177-0_19)**  
   Wang, Minghua and Xue, Jingling and Huang, Lin and Zi, Yuan and Wei, Tao, *International Symposium on Formal Methods (2024), pp. 307-324*

17. **[`Safe Shared State in Dataflow Systems`](https://doi.org/10.1145/3629104.3666029)**  
   De Martini, Luca and Margara, Alessandro, *Proceedings of the 18th ACM International Conference on Distributed and Event-Based Systems (2024), pp. 30-41*

18. **[`Surveying the Rust Verification Landscape`](https://doi.org/10.48550/arXiv.2410.01981)**  
   Blanc, Alex Le and Lam, Patrick, *arXiv preprint arXiv:2410.01981 (2024)*

19. **[`SafeNet: Towards mitigating replaceable unsafe Rust code via a recommendation-based approach`](https://onlinelibrary.wiley.com/doi/epdf/10.1002/stvr.1875)**  
   Dong, Yan and Zhang, Zhicong and Cui, Mohan and Xu, Hui, *Software Testing, Verification and Reliability (2024)*

20. **[`Refinedrust: A type system for high-assurance verification of Rust programs`](https://doi.org/10.1145/3656422)**  
   Gaher, Lennard and Sammler, Michael and Jung, Ralf and Krebbers, Robbert and Dreyer, Derek, *Proceedings of the ACM on Programming Languages (2024), pp. 1115-1139*

21. **[`rCanary: Detecting Memory Leaks Across Semi-automated Memory Management Boundary in Rust`](https://ieeexplore.ieee.org/abstract/document/10636096)**  
   Cui, Mohan and Xu, Hui and Tian, Hongliang and Zhou, Yangfan, *IEEE Transactions on Software Engineering (2024)*

22. **[`A mixed-methods study on the implications of unsafe Rust for interoperation, encapsulation, and tooling`](https://arxiv.org/abs/2404.02230)**  
   McCormack, Ian and Dougan, Tomas and Estep, Sam and Hibshi, Hanan and Aldrich, Jonathan and Sunshine, Joshua, *IEEE arXiv preprint arXiv:2404.02230 (2024)*

23. **[`PanicFI: An Infrastructure for Fixing Panic Bugs in Real-World Rust Programs`](https://arxiv.org/abs/2408.03262)**  
   Ni, Yunbo and Feng, Yang and Liu, Zixi and Chen, Runtao and Xu, Baowen, *arXiv preprint arXiv:2408.03262 (2024)*

24. **[`rOOM: A Rust-Based Linux Out of Memory Kernel Component`](https://globals.ieice.org/en_transactions/information/10.1587/transinf.2023MPP0001/_p)**  
   Li, Linhan and Zhang, IEICE TRANSACTIONS on Information and Systems, *The Institute of Electronics, Information and Communication Engineers (2024), pp. 245-256*

25. **[`An Empirical Study on Bugs in Rust Programming Language`](https://ieeexplore.ieee.org/abstract/document/10684664)**  
   Yu, Sijie and Wang, Ziyuan, *IEEE 24th International Conference on Software Quality, Reliability and Security (QRS) (2024), pp. 296-305*

26. **[`LEA Block Cipher in Rust Language: Trade-off between Memory Safety and Performance`](https://ieeexplore.ieee.org/abstract/document/10830717?casa_token=auT_ruSE1Z8AAAAA:DQ2bzLVL15oSnM6-mqq_4Dpm4_McbfPnaFFPzDWcrl5ARqME_ZtW1P8vHgkX5_qKh0-3cAPW7Fo)**  
   Kim, Sangwon and Eum, Siwoo and Song, Minho and Seo, Hwajeong, *International Conference on Platform Technology and Service (PlatCon) (2024), pp. 166-171*

27. **[`$\{$MetaSafe$\}$: Compiling for Protecting Smart Pointer Metadata to Ensure Safe Rust Integrity`](https://www.usenix.org/conference/usenixsecurity24/presentation/kayondo)**  
   Kayondo, Martin and Bang, Inyoung and Kwak, Yeongjun and Moon, Hyungon and Paek, Yunheung, *33rd USENIX Security Symposium (USENIX Security 24) (2024), pp. 3711-3728*

28. **[`Towards Understanding Rust in the Era of AI for Science at an Ecosystem Scale`](https://ieeexplore.ieee.org/abstract/document/10653388)**  
   Kayondo, Martin and Bang, Inyoung and Kwak, Yeongjun and Moon, Hyungon and Paek, Yunheung, *6th International Conference on Communications, Information System and Computer Engineering (CISCE) (2024), pp. 1450-1455*

29. **[`Fearless Unsafe. A More User-friendly Document for Unsafe Rust Programming Base on Refined Safety Properties`](https://arxiv.org/abs/2412.06251)**  
   Cui, Mohan and Mao, Penglei and Sun, Shuran and Zhou, Yangfan and Xu, Hui, *arXiv preprint arXiv:2412.06251 (2024)*

30. **[`Characterizing Unsafe Code Encapsulation In Real-world Rust Systems`](https://arxiv.org/abs/2406.07936)**  
   Rao, Zihao and Yang, Yiran and Xu, Hui, *arXiv preprint arXiv:2406.07936 (2024)*

31. **[`A Study of Undefined Behavior Across Foreign Function Boundaries in Rust Libraries`](https://arxiv.org/abs/2404.11671)**  
   McCormack, Ian and Sunshine, Joshua and Aldrich, Jonathan, *arXiv preprint arXiv:2404.11671 (2024)*

32. **[`A context-sensitive pointer analysis framework for Rust and its application to call graph construction`](https://dl.acm.org/doi/abs/10.1145/3640537.3641574)**  
   Li, Wei and He, Dongjie and Gui, Yujiang and Chen, Wenguang and Xue, Jingling, *Proceedings of the 33rd ACM SIGPLAN International Conference on Compiler Construction (2024), pp. 60-72*

33. **[`Static deadlock detection for rust programs`](https://arxiv.org/abs/2401.01114)**  
   Zhang, Yu and Zhang, Kaiwen and Liu, Guanjun, *arXiv preprint arXiv:2401.01114 (2024)*

34. **[`Beyond memory safety: an empirical study on bugs and fixes of rust programs`](https://ieeexplore.ieee.org/abstract/document/10684674)**  
   Zhang, Chengquan and Feng, Yang and Zhang, Yaokun and Dai, Yuxuan and Xu, Baowen, *IEEE 24th International Conference on Software Quality, Reliability and Security (QRS) (2024), 272-283*

35. **[`Can Secure Software be developed in Rust? On Vulnerabilities and Secure Coding Guidelines`](https://ieeexplore.ieee.org/abstract/document/10684674)**  
   Gasiba, Tiago Espinha and Amburi, Sathwik and Iosif, Andrei-Cristian, *International Journal on Advances in Security (2024), pp. 53-71*

36. **[`Unleashing the power of clippy in real-world rust projects`](https://dl.acm.org/doi/pdf/10.1145/3639478.3643096)**  
   Li, Chunmiao and Yu, Yijun and Wu, Haitao and Carlig, Luca and Nie, Shijie and Jiang, Lingxiao, *Proceedings of the 2024 IEEE/ACM 46th International Conference on Software Engineering: Companion Proceedings (2024), pp. 318-319*

37. **[`Is unsafe an Achilles' Heel? A Comprehensive Study of Safety Requirements in Unsafe Rust Programming`](https://dl.acm.org/doi/10.1145/3597503.3639136)**  
   Cui, Mohan and Sun, Shuran and Xu, Hui and Zhou, Yangfan, *Proceedings of the IEEE/ACM 46th International Conference on Software Engineering (2024), pp. 1-13*

38. **[`Improving Memory Management, Performance with Rust: Why Rust is becoming the programming language of choice for many high-level developers`](https://dl.acm.org/doi/10.1145/3673648)**  
  Williams, Alex, *Communications of the ACM (2024), pp. 8-9*

39. **[`Rust-lancet: Automated ownership-rule-violation fixing with behavior preservation`](https://dl.acm.org/doi/10.1145/3597503.3639103)**  
 Yang, Wenzhang and Song, Linhai and Xue, Yinxing, *Proceedings of the IEEE/ACM 46th International Conference on Software Engineering (2024), pp. 1-13*


### 2023

1. **[`A closer look at the security risks in the rust ecosystem`](https://doi.org/10.1145/3624738)**  
   Zheng, Xiaoye, Zhiyuan Wan, Yun Zhang, Rui Chang, and David Lo, *ACM Transactions on Software Engineering and Methodology 33, no. 2 (2023), pp. 1-30.*

2. **[`CrabSandwich: Fuzzing Rust with Rust (Registered Report)`](https://doi.org/10.1145/3605157.3605176)**  
   Crump, Addison, Dongjia Zhang, Syeda Mahnur Asif, Dominik Maier, Andrea Fioraldi, Thorsten Holz, and Davide Balzarotti,  *Proceedings of the 2nd International Fuzzing Workshop (2023), pp. 39-46.*

3. **[`SafeDrop: Detecting memory deallocation bugs of rust programs via static data-flow analysis`](https://doi.org/10.1145/3542948)**  
   Cui, Mohan and Chen, Chengjun and Xu, Hui and Zhou, Yangfan, *ACM Transactions on Software Engineering and Methodology (2023), pp. 1-21.*

4. **[`TRust: A compilation framework for in-process isolation to protect safe rust against untrusted code`](https://www.usenix.org/conference/usenixsecurity23/presentation/bang)**  
   Bang, Inyoung and Kayondo, Martin and Moon, HyunGon and Paek, Yunheung, *USENIX Security (2023), pp. 6947-6964.*

5. **[`Friend or foe inside? exploring in-process isolation to maintain memory safety for unsafe rust`](https://arxiv.org/abs/2306.08127)**  
   G{u}lmez, Merve and Nyman, Thomas and Baumann, Christoph and M{u}hlberg, Jan Tobias, *IEEE Secure Development Conference (SecDev) (2023), pp. 54-66.*

6. **[`Using LLMs to fix compilation errors in Rust code`](https://arxiv.org/abs/2308.05177)**  
   Deligiannis, Pantazis and Lal, Akash and Mehrotra, Nikita and Poddar, Rishi and Rastogi, Aseem, *IEEE/ACM 47th International Conference on Software Engineering (ICSE) (2023), pp. 3097-3109.*

7. **[`A grounded conceptual model for ownership types in rust`](https://doi.org/10.1145/3622841)**  
   Deligiannis, Pantazis and Lal, Akash and Mehrotra, Nikita and Poddar, Rishi and Rastogi, Aseem, *Proceedings of the ACM on Programming Languages, OOPSLA2 (2023), pp. 1224-1252.*

8. **[`I wouldn't want my unsafe code to run my pacemaker: An Interview Study on the Use, Comprehension, and Perceived Risks of Unsafe Rust`](https://www.usenix.org/system/files/usenixsecurity23-holtervennhoff.pdf)**  
   Holtervennhoff, Sandra and Klostermeyer, Philip and Wohler, Noah and Acar, Yasemin and Fahl, Sascha, *32nd USENIX Security Symposium (USENIX Security 23) (2023), pp. 2509-2525*

9. **[`A Comparative Analysis of Rust-Based SGX Frameworks: Implications for Building SGX Applications`](https://link.springer.com/chapter/10.1007/978-981-97-1238-0_1)**  
   Shin, Heekyung and Ock, Jiwon and No, Hyeon and Kim, Seongmin, *International Conference on Information Security and Cryptology (2023), pp. 3-19*

10. **[`On the dual nature of necessity in use of Rust unsafe code`](https://dl.acm.org/doi/abs/10.1145/3611643.3613878)**  
   Zhang, Yuchen and Kundu, Ashish and Portokalidis, Georgios and Xu, Jun, *Proceedings of the 31st ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (2023), pp. 2032-2037*

11. **[`An Analysis of the Rust Programming Practice for Memory Safety Assurance`](https://link.springer.com/chapter/10.1007/978-981-99-6222-8_37)**  
   Xu, Baowen and Chu, Bei and Fan, Hongcheng and Feng, Yang, *International Conference on Web Information Systems and Applications (2023), pp. 440-451*

12. **[`Rustcheck: Safety Enhancement of Unsafe Rust via Dynamic Program Analysis`](https://ieeexplore.ieee.org/abstract/document/10429951)**  
   Xia, Lei and Wu, Yufei and Hua, Baojian, *IEEE 23rd International Conference on Software Quality, Reliability, and Security Companion (QRS-C) (2023), pp. 871--872*

13. **[`Understanding bugs in rust compilers`](https://ieeexplore.ieee.org/abstract/document/10366531)**  
   Xia, Xinmeng and Feng, Yang and Shi, Qingkai, *IEEE 23rd International Conference on Software Quality, Reliability, and Security (QRS) (2023), pp. 138-149*

14. **[`Fuzz Testing for Rust Library Functions`](https://ieeexplore.ieee.org/abstract/document/10538774)**  
   Guo, Yongjian and Xiao, Xi and Lin, Yuanyi and Li, Hao and Wu, Xiangbo and Zhou, Tao, *IEEE 22nd International Conference on Trust, Security and Privacy in Computing and Communications (TrustCom) (2023), pp. 990-997*

15. **[`Rust for embedded systems: Current state, challenges and open problems`](https://arxiv.org/abs/2311.05063)**  
   Sharma, Ayushi and Sharma, Shashank and Torres-Arias, Santiago and Machiry, Aravind, *arXiv preprint arXiv:2311.05063 (2023)*

16. **[`Panic Recovery in Rust-based Embedded Systems`](https://dl.acm.org/doi/10.1145/3623759.3624549)**  
   Ma, Zhiyao and Chen, Guojun and Zhong, Lin, *Proceedings of the 12th Workshop on Programming Languages and Operating Systems (2023), pp. 66-73*

17. **[`Verus: Verifying rust programs using linear ghost types`](https://doi.org/10.1145/3586037)**  
   Lattuada, Andrea and Hance, Travis and Cho, Chanhee and Brun, Matthias and Subasinghe, Isitha and Zhou, Yi and Howell, Jon and Parno, Bryan and Hawblitzel, Chris, *Proceedings of the ACM on Programming Languages (OOPSLA1), (2023), pp. 286-315*

18. **[`Encapsulated functions: fortifying rust's ffi in embedded systems`](https://dl.acm.org/doi/10.1145/3625275.3625397)**  
   Schuermann, Leon and Thomas, Arun and Levy, Amit, *Proceedings of the 1st Workshop on Kernel Isolation, Safety and Verification (2023), pp. 41-48*

19. **[`Symrustc: A hybrid fuzzer for rust`](https://dl.acm.org/doi/10.1145/3597926.3604927)**  
   Tuong, Fr{\'e}d{\'e}ric and Omidvar Tehrani, Mohammad and Gaboardi, Marco and Ko, Steven Y, *Proceedings of the 32nd ACM SIGSOFT International Symposium on Software Testing and Analysis (2023), pp. 1515-1518*

20. **[`Flux: Liquid types for rust`](https://dl.acm.org/doi/10.1145/3591283)**  
   Lehmann, Nico and Geller, Adam T and Vazou, Niki and Jhala, Ranjit, *Proceedings of the ACM on Programming Languages (2023), pp. 1533-1557*

21. **[`Leveraging rust types for program synthesis`](https://dl.acm.org/doi/10.1145/3591278)**  
   Fiala, Jon{\'a}{\v{s}} and Itzhaky, Shachar and M{\"u}ller, Peter and Polikarpova, Nadia and Sergey, Ilya, *Proceedings of the ACM on Programming Languages (2023), pp. 1414-1437*


### 2022

1. **[`Learning and programming challenges of rust: A mixed-methods study`](https://doi.org/10.1145/3510003.3510164)**  
   Zhu, Shuofei and Zhang, Ziyi and Qin, Boqin and Xiong, Aiping and Song, Linhai, *Proceedings of the 44th International Conference on Software Engineering (2022), pp. 1269-1281.*

2. **[`Modular information flow through ownership`](https://doi.org/10.1145/3519939.3523445)**  
   Crichton, Will and Patrignani, Marco and Agrawala, Maneesh and Hanrahan, Pat, *Proceedings of the 43rd ACM SIGPLAN International Conference on Programming Language Design and Implementation (2022), pp. 1-14.*

3. **[`Unsafe's Betrayal: Abusing Unsafe Rust in Binary Reverse Engineering via Machine Learning`](https://doi.org/10.48550/arXiv.2211.00111)**  
   Park, Sangdon and Cheng, Xiang and Kim, Taesoo, *arXiv preprint arXiv:2211.00111 (2022).*

4. **[`RustHornBelt: a semantic foundation for functional verification of Rust programs with unsafe code`](https://doi.org/10.1145/3519939.3523704)**  
   Matsushita, Yusuke and Denis, Xavier and Jourdan, Jacques-Henri and Dreyer, Derek, *Proceedings of the 43rd ACM SIGPLAN International Conference on Programming Language Design and Implementation (2022), pp. 841-856.*

5. **[`Creusot: A foundry for the deductive verification of Rust programs`](https://link.springer.com/chapter/10.1007/978-3-031-17244-1_6)**  
   Denis, Xavier and Jourdan, Jacques-Henri and Marche, Claude, *International Conference on Formal Engineering Methods (2022), pp. 90-105.*

6. **[`Verifying dynamic trait objects in rust`](https://dl.acm.org/doi/abs/10.1145/3510457.3513031)**  
   VanHattum, Alexa and Schwartz-Narbonne, Daniel and Chong, Nathan and Sampson, Adrian, *Proceedings of the 44th International Conference on Software Engineering: Software Engineering in Practice, (2022), pp. 321-330*

7. **[`Pkru-safe: automatically locking down the heap between safe and unsafe languages`](https://dl.acm.org/doi/abs/10.1145/3492321.3519582)**  
   Kirth, Paul and Dickerson, Mitchel and Crane, Stephen and Larsen, Per and Dabrowski, Adrian and Gens, David and Na, Yeoul and Volckaert, Stijn and Franz, Michael, *Proceedings of the Seventeenth European Conference on Computer Systems, (2022), pp. 132-148*

8. **[`Towards understanding the runtime performance of rust`](https://doi.org/10.1145/3551349.3559494)**  
   Zhang, Yuchen and Zhang, Yunhang and Portokalidis, Georgios and Xu, Jun, *Proceedings of the 37th IEEE/ACM International Conference on Automated Software Engineering, (2022), pp. 1-6*

9. **[`VRust: Automated vulnerability detection for solana smart contracts`](https://dl.acm.org/doi/abs/10.1145/3548606.3560552)**  
   Cui, Siwei and Zhao, Gang and Gao, Yifei and Tavu, Tien and Huang, Jeff, *Proceedings of the 2022 ACM SIGSAC Conference on Computer and Communications Security, (2022), pp. 639-652*

10. **[`Comprehensiveness, Automation and Lifecycle: A New Perspective for Rust Security`](https://ieeexplore.ieee.org/abstract/document/10062361)**  
   Hu, Shuang and Hua, Baojian and Wang, Yang, *IEEE 22nd International Conference on Software Quality, Reliability and Security (QRS), (2022), pp. 982-991*


### 2021

1. **[`Rudra: finding memory safety bugs in rust at the ecosystem scale`](https://doi.org/10.1145/3477132.3483570)**  
   Bae, Yechan and Kim, Youngsuk and Askar, Ammar and Lim, Jungwon and Kim, Taesoo, *Proceedings of the ACM SIGOPS 28th Symposium on Operating Systems Principles (2021), pp. 84-99.*

2. **[`MirChecker: detecting bugs in Rust programs via static analysis`](https://doi.org/10.1145/3460120.3484541)**  
   Li, Zhuohua and Wang, Jincheng and Sun, Mingshen and Lui, John CS, *Proceedings of the ACM SIGSAC conference on computer and communications security (2021), pp. 2183-2196.*

3. **[`Memory-safety challenge considered solved? An in-depth study with all Rust CVEs`](https://doi.org/10.1145/3466642)**  
   Xu, Hui and Chen, Zhuangbin and Sun, Mingshen and Zhou, Yangfan and Lyu, Michael R, *ACM Transactions on Software Engineering and Methodology (TOSEM) (2021), pp. 1-25.*

4. **[`Keeping safe rust safe with galeed`](https://doi.org/10.1145/3485832.3485903)**  
   Rivera, Elijah and Mergendahl, Samuel and Shrobe, Howard and Okhravi, Hamed and Burow, Nathan, *Proceedings of the 37th Annual Computer Security Applications Conference (2021), pp. 824-836*

5. **[`RustHorn: CHC-based verification for Rust programs`](https://doi.org/10.1145/3462205)**  
   Matsushita, Yusuke and Tsukada, Takeshi and Kobayashi, Naoki, *ACM Transactions on Programming Languages and Systems (TOPLAS) (2021), pp. 1-54*

6. **[`GhostCell: separating permissions from data in Rust`](https://doi.org/10.1145/3473597)**  
   Yanovski, Joshua and Dang, Hoang-Hai and Jung, Ralf and Dreyer, Derek, *Proceedings of the ACM on Programming Languages (2021), pp. 1-30*

7. **[`Safe systems programming in Rust`](https://dl.acm.org/doi/fullHtml/10.1145/3418295)**  
   Jung, Ralf and Jourdan, Jacques-Henri and Krebbers, Robbert and Dreyer, Derek, *Communications of the ACM (2021), pp. 144-152*

8. **[`Syrust: automatic testing of rust libraries with semantic-aware program synthesis`](https://doi.org/10.1145/3453483.3454084)**  
   Takashima, Yoshiki and Martins, Ruben and Jia, Limin and Puasuareanu, Corina S, *Proceedings of the 42nd ACM SIGPLAN International Conference on Programming Language Design and Implementation (2021), pp. 899-913*

9. **[`A lightweight formalism for reference lifetimes and borrowing in Rust`](https://doi.org/10.1145/3443420)**  
   Pearce, David J, *ACM Transactions on Programming Languages and Systems (TOPLAS) (2021), pp. 1-73*

10. **[`Safer at any speed: automatic context-aware safety enhancement for Rust`](https://doi.org/10.1145/3485480)**  
   Popescu, Natalie and Xu, Ziyang and Apostolakis, Sotiris and August, David I and Levy, Amit, *Proceedings of the ACM on Programming Languages (OOPSLA), (2021), pp. 1-23*

11. **[`RULF: Rust library fuzzing via API dependency graph traversal`](https://ieeexplore.ieee.org/abstract/document/9678813?casa_token=GZVQ40vnE9wAAAAA:lfyvN6zLjKS1iBPmu8vLkufAjgwf5pyK-zvLHFQzsOzwNo991KH3K3G2EwkO4VHXumljtoEyVx4)**  
   Jiang, Jianfeng and Xu, Hui and Zhou, Yangfan, *2021 36th IEEE/ACM International Conference on Automated Software Engineering (ASE), (2021), pp. 581-592*

12. **[`Rupair: towards automatic buffer overflow detection and rectification for rust`](https://doi.org/10.1145/3485832.3485841)**  
   Hua, Baojian and Ouyang, Wanrong and Jiang, Chengman and Fan, Qiliang and Pan, Zhizhong, *Proceedings of the 37th Annual Computer Security Applications Conference, (2021), pp. 812-823*

13. **[`Modular specification and verification of closures in Rust`](https://dl.acm.org/doi/10.1145/3485522)**  
   Wolff, Fabian and B{\'\i}l{\`y}, Aurel and Matheja, Christoph and M{\"u}ller, Peter and Summers, Alexander J, *Proceedings of the ACM on Programming Languages (OOPSLA), (2021), pp. 1-29*


### 2020

1. **[`Is rust used safely by software developers?`](https://doi.org/10.1145/3377811.3380413)**  
   Evans, Ana Nora and Campbell, Bradford and Soffa, Mary Lou, *Proceedings of the ACM/IEEE 42nd International Conference on Software Engineering (2020), pp. 246-257.*

2. **[`Understanding memory and thread safety practices and issues in real-world Rust programs`](https://doi.org/10.1145/3385412.3386036)**  
   Qin, Boqin and Chen, Yilun and Yu, Zeming and Song, Linhai and Zhang, Yiying, *Proceedings of the 41st ACM SIGPLAN Conference on Programming Language Design and Implementation (2020), pp. 763-779.*

3. **[`How do programmers use unsafe rust?`](https://doi.org/10.1145/3428204)**  
   Astrauskas, Vytautas and Matheja, Christoph and Poli, Federico and Muller, Peter and Summers, Alexander J, *Proceedings of the ACM on Programming Languages (OOPSLA), (2020), pp. 1-27.*

4. **[`Securing unsafe rust programs with XRust`](https://doi.org/10.1145/3377811.3380325)**  
   Liu, Peiming and Zhao, Gang and Huang, Jeff, *Proceedings of the ACM/IEEE 42nd International Conference on Software Engineering, (2020), pp. 234-245.* 

5. **[`Understanding and evolving the Rust programming language`](https://universaar.uni-saarland.de/handle/20.500.11880/29647)**  
   Jung, Ralf, *Dizertavcna praca. Saarland University, (2020)* 

6. **[`VRLifeTime--An IDE Tool to Avoid Concurrency and Memory Bugs in Rust`](https://dl.acm.org/doi/10.1145/3372297.3420024)**  
   Zhang, Ziyi and Qin, Boqin and Chen, Yilun and Song, Linhai and Zhang, Yiying, *Proceedings of the 2020 ACM SIGSAC Conference on Computer and Communications Security, (2020), pp. 2085-2087* 


---

## Statistics

| Year | Number of Papers | Top Venues |
|------|------------------|------------|
| 2025 | 2 | USENIX Security, OOPSLA |
| 2024 | TBD | TBD |
| 2023 | TBD | TBD |
| 2022 | TBD | TBD |
| 2021 | TBD | TBD |
| 2020 | TBD | TBD |

## Research Trends

- **Memory Safety:** X papers
- **Type Systems:** X papers
- **Formal Verification:** X papers
- **Concurrency:** X papers

## Citation Format

All papers follow the Chicago citation format as provided by Google Scholar.

To cite this repository:
```bibtex
