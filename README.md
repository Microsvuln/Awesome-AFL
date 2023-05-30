# Awesome-AFL
Welcome to Awesome AFL 
========================================================
A curated list of different AFL forks and AFL inspired fuzzers with detailed equivalent academic papers including AFL-fuzzing tutorials

### Projects
- [AFL](http://lcamtuf.coredump.cx/afl/) by [Michal Zalewski](http://lcamtuf.coredump.cx/)
  + Original & first versions of AFL fuzzer, american fuzzy lop is a free security-oriented fuzzer that employs genetic algorithms in order to efficiently increase code coverage of the test cases. So far it helped in detection of significant software bugs in dozens of major free software projects, including X.Org Server, PHP, OpenSSL, pngcrush, bash, Firefox, BIND, Qt, and SQLite. 

- [AFL++](https://github.com/vanhauser-thc/AFLplusplus) by [van Hauser](https://github.com/vanhauser-thc) 
  + afl++ is afl 2.56b with community patches, AFLfast power schedules, qemu 3.1 upgrade + laf-intel support, MOpt mutators, InsTrim instrumentation, unicorn_mode and a lot more!
  
- [WinAFL](https://github.com/googleprojectzero/winafl) by [Ivan Fratric](https://github.com/ifratric)
  + A fork of AFL for fuzzing Windows binaries
  
- [afl-dyninst](https://github.com/talos-vulndev/afl-dyninst) by [Cisco Talos Lab](https://talosintelligence.com/)
  + American Fuzzy Lop + Dyninst == AFL Fuzzing blackbox binaries
  
- [TriforceAFL](https://github.com/nccgroup/TriforceAFL) by [Jesse Hertz and Tim Newsham of nccgroup](https://github.com/nccgroup)
  + This is a patched version of AFL that supports full-system fuzzing using QEMU. The included QEMU has been updated to allow tracing of branches when running a system emulator for x86_64. Extra instructions have been added to start AFL's forkserver, make fuzz settings, and mark the start and stop of test cases.

- [AFL-abiondo](https://github.com/abiondo/afl) by [Abiondo](https://github.com/abiondo)
  + Improved version of AFL-Qemu mode (https://abiondo.me/2018/09/21/improving-afl-qemu-mode/)

- [aflsmart](https://github.com/aflsmart/aflsmart) by Maintained by [Thuan Pham](https://github.com/thuanpv)
  + Smart Greybox Fuzzing (https://thuanpv.github.io/publications/TSE19_aflsmart.pdf)
  
- [aflfast](https://github.com/mboehme/aflfast) by [Marcel Böhme](https://github.com/mboehme)
  + Coverage-based Greybox Fuzzing as Markov Chain (https://mboehme.github.io/paper/CCS16.pdf)

- [WineAFLplusplusDEMO](https://github.com/andreafioraldi/WineAFLplusplusDEMO) by [Andrea Fioraldi](https://github.com/andreafioraldi)
  + A set of helpers and examples to fuzz Win32 binaries with AFL++ QEMU

- [afl-sensitive](https://github.com/bitsecurerlab/afl-sensitive/tree/cgc) by [Heng Yin](https://www.cs.ucr.edu/~heng/)
  + Be Sensitive and Collaborative: Analyzing Impact of Coverage Metrics in Greybox Fuzzing (https://www.cs.ucr.edu/~heng/pubs/afl-sensitive.pdf)

- [Redqueen](https://github.com/RUB-SysSec/redqueen) by [Syssec lab of Ruhr university of germany](https://www.syssec.ruhr-uni-bochum.de/chair/)
  + REDQUEEN: Fuzzing with Input-to-State Correspondence (http://synthesis.to/papers/NDSS19-Redqueen.pdf)

- [afl-pin](https://github.com/vanhauser-thc/afl-pin) by [van Hauser](https://github.com/vanhauser-thc)
  + run AFL with pintool

- [Driller](https://github.com/shellphish/driller) by [Shellphish team of University of Santa Barbara](https://github.com/shellphish)
  + Augmenting AFL with Symbolic execution, a powerful symbolic execution engine aims at hybrid fuzzing
  
- [AngoraFuzzer](https://github.com/AngoraFuzzer/Angora)
  + Angora is a mutation-based fuzzer. The main goal of Angora is to increase branch coverage by solving path constraints without symbolic execution. Angora: Efficient Fuzzing by Principled Search (https://arxiv.org/abs/1803.01307)
  
- [VUzzer](https://github.com/vusec/vuzzer) by [Systems and Network Security Group at VU Amsterdam](https://www.vusec.net/)
  + VUzzer: Application-aware Evolutionary Fuzzing (https://www.cs.vu.nl/~giuffrida/papers/vuzzer-ndss-2017.pdf)

- [Manul](https://github.com/mxmssh/manul) by [Maksim Shudrak](https://github.com/mxmssh)
  + Manul is a coverage-guided parallel fuzzer for open-source and blackbox binaries on Windows, Linux and MacOS (https://www.slideshare.net/MaximShudrak/shudrak-zero-bugs-found-hold-my-beer-afl-how-to-improve-coverageguided-fuzzing-and-find-new-zerodays-in-tough-targets)
  
- [QSYM](https://github.com/sslab-gatech/qsym) by [SSLab of Georgia Tech University](https://gts3.org/)
  + QSYM: A Practical Concolic Execution Engine Tailored for Hybrid Fuzzing

- [netafl](https://gitlab.com/gavz/netafl) by [gavz](https://gitlab.com/gavz)
  + winAFL patch to enable network-based apps fuzzing

- [Unicorefuzz](https://github.com/fgsect/unicorefuzz) by [The Computer Security Group at Berlin University of Technology](https://github.com/fgsect)
  + Fuzzing the Kernel using AFL Unicorn. For details, skim through the WOOT paper or watch this talk at CCCamp19 (https://www.usenix.org/system/files/woot19-paper_maier.pdf)

- [SharpFuzz: AFL-based fuzz testing for .NET](https://github.com/Metalnem/sharpfuzz) by [Nemanja Mijailovic](https://github.com/Metalnem)
  + SharpFuzz is a tool that brings the power of afl-fuzz to .NET platform (https://mijailovic.net/2019/01/03/sharpfuzz/)
  
- [Nautilus 2.0 - a grammar based feedback fuzzer](https://github.com/nautilus-fuzz/nautilus) by [Syssec lab of Ruhr university of germany](https://github.com/nautilus-fuzz/nautilus) 
  + https://www.syssec.ruhr-uni-bochum.de/media/emma/veroeffentlichungen/2018/12/17/NDSS19-Nautilus.pdf
  
- [frida-js-afl-instr](https://github.com/andreafioraldi/frida-js-afl-instr) by [Andrea Fioraldi](https://github.com/andreafioraldi)  

- [UnTracer-AFL](https://github.com/FoRTE-Research/UnTracer-AFL) by Stefan Nagy (snagy2@vt.edu) and Matthew Hicks (mdhicks2@vt.edu)
  + [Full-speed Fuzzing: Reducing Fuzzing Overhead through Coverage-guided Tracing](https://arxiv.org/abs/1812.11875)
  
- [kleefl](https://github.com/julieeen/kleefl) by [julieeen](https://github.com/julieeen/kleefl)
  + Seeding fuzzers with symbolic execution
  
- [AFLGo](https://github.com/aflgo/aflgo) Maintained by [@mboehme](https://github.com/mboehme), [@thuanpv](https://github.com/thuanpv), and [@strongcourage](https://github.com/strongcourage)
  + AFLGo is an extension of American Fuzzy Lop (AFL). Given a set of target locations (e.g., folder/file.c:582), AFLGo generates inputs specifically with the objective to exercise these target locations (https://mboehme.github.io/paper/CCS17.pdf)

- [afl-dyninst](https://github.com/vanhauser-thc/afl-dyninst) Maintained by [van Hauser](https://github.com/vanhauser-thc)
  + American Fuzzy Lop + Dyninst == AFL Fuzzing blackbox binaries
  
- [afl-dynamorio](https://github.com/vanhauser-thc/afl-dynamorio) Maintained by [van Hauser](https://github.com/vanhauser-thc)
  + run AFL with dynamorio - binary-only fuzzing with dynamorio and afl

- [FairFuzz](https://github.com/carolemieux/afl-rb) Maintained by [Caroline Lemieux of UC-Berkeley](https://github.com/carolemieux)
  + An AFL extension to increase code coverage by targeting rare branches. FairFuzz has a particular advantage on programs with highly nested structure (packet analyzers, xmllint, programs compiled with laf-inte, etc) (http://www.carolemieux.com/fairfuzz-ase18.pdf)
  
- [Superion](https://github.com/zhunki/Superion) Maintained by [zhunki](https://github.com/zhunki/)
  + Superion is a fuzzer which extends the famous AFL to support structured inputs such as JavaScript and XML (https://2019.icse-conferences.org/track/icse-2019-Technical-Papers#event-overview)
  
- [UnTracer-AFL](https://github.com/FoRTE-Research/UnTracer-AFL) Maintained by [FoRTE-Research](https://github.com/FoRTE-Research)
  + An AFL implementation with UnTracer (our coverage-guided tracer)
  
- [neuzz](https://github.com/Dongdongshe/neuzz) Maintained by [Dongdongshe](https://github.com/Dongdongshe)
  + neural network assisted fuzzer (https://arxiv.org/abs/1807.05620)
  
- [FuzzFactory](https://github.com/rohanpadhye/FuzzFactory) Maintained by [Rohan Padhye](https://github.com/rohanpadhye)
  + FuzzFactory is an extension of AFL that generalizes coverage-guided fuzzing to domain-specific testing goals. FuzzFactory allows users to guide the fuzzer's search process without having to modify anything in AFL's search algorithm (https://dl.acm.org/doi/10.1145/3360600)
  
  
- [kAFL](https://github.com/RUB-SysSec/kAFL) Maintained by [RUB-SysSec](https://github.com/RUB-SysSec)
  + Blazing fast x86-64 VM kernel fuzzing framework with performant VM reloads for Linux, MacOS and Windows (https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-schumilo.pdf)
  + It is now maintained by Intellabs : https://github.com/IntelLabs/kAFL

- [AFLNet](https://github.com/aflnet/aflnet) Maintained by [Thuan Pham](https://github.com/thuanpv)
  + AFLNet: A Greybox Fuzzer for Network Protocols
  (https://thuanpv.github.io/publications/AFLNet_ICST20.pdf)
  
- [Grimoire](https://github.com/RUB-SysSec/grimoire) Maintained by [Tim Blazytko](https://github.com/mrphrazer)
  + Grimoire: Synthesizing Structure while Fuzzing - Grimoire is coverage-guided fuzzer for structured input languages. It is built upon Redqueen (https://www.usenix.org/system/files/sec19-blazytko.pdf)
  
- [JQF](https://github.com/rohanpadhye/jqf) Maintained by [Rohan Padhye of UC-Berkeley](https://github.com/rohanpadhye)
  + JQF is a feedback-directed fuzz testing platform for Java, which uses the abstraction of property-based testing. JQF is built on top of junit-quickcheck: a tool for generating random arguments for parametric Junit test methods. JQF enables better input generation using coverage-guided fuzzing algorithms such as Zest. (https://cs.berkeley.edu/~rohanpadhye/files/zest-issta19.pdf)
  
- [PerfFuzz](https://github.com/carolemieux/perffuzz) Maintained by [Caroline Lemieux of UC-Berkeley](https://github.com/carolemieux)
  + PerfFuzz: Automatically Generate Pathological Inputs for C/C++ programs : Performance problems in software can arise unexpectedly when programs are provided with inputs that exhibit pathological behavior. But how can we find these inputs in the first place? PerfFuzz can generate such inputs automatically: given a program and at least one seed input, PerfFuzz automatically generates inputs that exercise pathological behavior across program locations, without any domain knowledge.PerfFuzz uses multi-dimensional performance feedback and independently maximizes execution counts for all program locations. This enables PerfFuzz to find a variety of inputs that exercise distinct hot spots in a program. (http://www.carolemieux.com/perffuzz-issta2018.pdf)

- [Ankou](https://github.com/SoftSec-KAIST/Ankou) Maintained by [Valentin Manès aka Jilyac](https://github.com/Jiliac)
  + Ankou is a source-based grey-box fuzzer. It intends to use a more rich fitness function by going beyond simple branch coverage and considering the combination of branches during program execution. The details of the technique can be found in our paper "Ankou: Guiding Grey-box Fuzzing towards Combinatorial Difference", which is published in ICSE 2020. (https://www.jiliac.com/files/ankou-icse2020.pdf)

- [Savior](https://github.com/evanmak/savior-source) Maintained by [@yaohway](https://github.com/evanmak)
  + SAVIOR, a new hybrid testing framework pioneering a bug-driven principle. Unlike the existing hybrid testing tools, SAVIOR prioritizes the concolic execution of the seeds that are likely to uncover more vulnerabilities. Moreover, SAVIOR verifies all vulnerable program locations along the executing program path. By modeling faulty situations using SMT constraints, SAVIOR reasons the feasibility of vulnerabilities and generates concrete test cases as proofs. Our evaluation shows that the bug-driven approach outperforms mainstream automated testing techniques, including state-of-the-art hybrid testing systems driven by code coverage. (https://arxiv.org/pdf/1906.07327.pdf)
  
- [T-Fuzz](https://github.com/HexHive/T-Fuzz) Maintained by [@HexHive](https://github.com/HexHive)
  + To improve coverage, existing approaches rely on imprecise heuristics or complex input mutation techniques (e.g., symbolic
execution or taint analysis) to bypass sanity checks. Our novel method tackles coverage from a different angle: by removing sanity checks in the target program. T-Fuzz leverages a coverage guided fuzzer to generate inputs. Whenever the fuzzer can
no longer trigger new code paths, a light-weight, dynamic tracing based technique detects the input checks that the fuzzergenerated inputs fail. These checks are then removed from the target program. Fuzzing then continues on the transformed
program, allowing the code protected by the removed checks to be triggered and potential bugs discovered.
Fuzzing transformed programs to find bugs poses two challenges: (1) removal of checks leads to over-approximation andfalse positives, and (2) even for true bugs, the crashing input on the transformed program may not trigger the bug in the original program. As an auxiliary post-processing step, T-Fuzz leverages a symbolic execution-based approach to filter out false positives and reproduce true bugs in the original program. (https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8418632)

- [afl-compiler-fuzzer](https://github.com/agroce/afl-compiler-fuzzer) Maintained by [Alex Groce](https://github.com/agroce) from [TrailOfBits](https://github.com/trailofbits)
  + This is basically afl, run as usual, except that the afl-fuzz-compiler executable should (considerably) improve effectveness when fuzzing any target that takes C-like (in terms of syntax, e.g., Java, Solidity, Rust, C#, Swift, Javascript, Scala, etc. etc.) language files as input. 
  
- [Eclipser](https://github.com/SoftSec-KAIST/Eclipser)  Maintained by [KAIST-Softsec Lab](https://github.com/SoftSec-KAIST)
  + Eclipser is a binary-based fuzz testing tool that improves upon classic coverage-based fuzzing by leveraging a novel technique called grey-box concolic testing. The details of the technique can be found in our paper ["Grey-box Concolic Testing on Binary Code"](https://softsec.kaist.ac.kr/~jschoi/data/icse2019.pdf), which is published in ICSE 2019.

- [Parmesan](https://github.com/vusec/parmesan) Maintained by [Sebastian Österlund](https://github.com/sirmc) of [VUSEC](https://github.com/vusec)
  + ParmeSan is a sanitizer-guided greybox fuzzer based on Angora. we present sanitizer-guided fuzzing, a new design point in this space that specifically optimizes for bug coverage. For this purpose, we make the key observation that while the instrumentation performed by existing software sanitizers are regularly used for detecting fuzzer-induced error conditions, they can further serve as a generic and effective mechanism to identify interesting basic blocks for guiding fuzzers. We present the design and implementation of ParmeSan, a new sanitizer-guided fuzzer that builds on this observation. We show that ParmeSan greatly reduces the TTE of real-world bugs, and finds bugs 37% faster than existing state-of-the-art coverage-based fuzzers (Angora) and 288% faster than directed fuzzers (AFLGo), while still covering the same set of bugs. [ParmeSan: Sanitizer-guided Greybox Fuzzing](https://download.vusec.net/papers/parmesan_sec20.pdf)
  
- [Weizz-Fuzzer](https://github.com/andreafioraldi/weizz-fuzzer) by [Andrea Fioraldi](https://github.com/andreafioraldi)
  + Fuzzing technologies have evolved at a fast pace in recent years, revealing bugs in programs with ever increasing depth and speed. Applications working with complex formats are however more difficult to take on, as inputs need to meet certain format-specific characteristics to get through the initial parsing stage and reach deeper behaviors of the program. Unlike prior proposals based on manually written format specifications, we propose a technique to automatically generate and mutate inputs for unknown chunk-based binary formats. We identify dependencies between input bytes and comparison instructions, and use them to assign tags that characterize the processing logic of the program. Tags become the building block for structure-aware mutations involving chunks and fields of the input. Our technique can perform comparably to structure-aware fuzzing proposals that require human assistance. Our prototype implementation Weizz revealed 16 unknown bugs in widely used programs. [WEIZZ: Automatic Grey-Box Fuzzing for Structured Binary Formats](https://andreafioraldi.github.io/assets/weizz-issta2020.pdf) [Slides-ISSTA-2020](https://andreafioraldi.github.io/assets/weizz-issta2020-slides.pdf)

- [MOpt-AFL](https://github.com/Microsvuln/MOpt-AFL) by [puppet-meteor](https://github.com/puppet-meteor)
  + MOpt-AFL is a AFL-based fuzzer that utilizes a customized Particle Swarm Optimization (PSO) algorithm to find the optimal selection probability distribution of operators with respect to fuzzing effectiveness. More details can be found in the technical report. The installation of MOpt-AFL is the same as AFL's. [MOpt: Optimized Mutation Scheduling for Fuzzers](https://www.usenix.org/system/files/sec19-lyu.pdf)
  
- [Kirenenko](https://github.com/ChengyuSong/Kirenenko) by [Chengyu Song](https://github.com/ChengyuSong/Kirenenko) from University of California, Riverside
  + Super Fast Concolic Execution Engine based on Source Code Taint Tracing

- [UAFuzz](https://github.com/strongcourage/uafuzz) by [@strongcourage](https://github.com/strongcourage)
  + Binary-level Directed Fuzzing for Use-After-Free Vulnerabilities, built on top of AFL-QEMU.
  
- [Intriguer](https://github.com/seclab-yonsei/intriguer) by [Seclab@Yonsei University](https://github.com/seclab-yonsei)
  + Hybrid fuzzing, which combines fuzzing and concolic execution, is promising in light of the recent performance improvements in concolic engines. We have observed that there is room for further improvement: symbolic emulation is still slow, unnecessary constraints dominate solving time, resources are overly allocated, and hard-to-trigger bugs are missed. To address these problems, we present a new hybrid fuzzer named Intriguer. The key idea of Intriguer is field-level constraint solving, which optimizes symbolic execution with field-level knowledge. Intriguer performs instruction-level taint analysis and records execution traces without data transfer instructions like mov. Intriguer then reduces the execution traces for tainted instructions that accessed a wide range of input bytes, and infers input fields to build field transition trees. With these optimizations, Intriguer can efficiently perform symbolic emulation for more relevant instructions and invoke a solver for complicated constraints only. Our evaluation results indicate that Intriguer outperforms the state-of-the-art fuzzers: Intriguer found all the bugs in the LAVAM(5h) benchmark dataset for ground truth performance, and also discovered 43 new security bugs in seven real-world programs. We reported the bugs and received 23 new CVEs. [Intriguer: Field-Level Constraint Solving for Hybrid Fuzzing](https://wcventure.github.io/FuzzingPaper/Paper/CCS19_Intriguer.pdf)
  
- [TinyAFL](https://github.com/linhlhq/TinyAFL) by [linhlhq](https://github.com/linhlhq)  
  + TinyAFL is built on top of AFL and TinyInst. It can be fuzz on windows user-mode application without source (supports both x32 and x64) but it is not so reliable and dirty. 
  
- [DeepFuzzer](https://github.com/Ljiee/deepfuzz) by [Ljiee](https://github.com/Ljiee)
  + In this paper, we present DeepFuzzer, an enhanced greybox fuzzer with qualiﬁed seed generation, balanced seed selection, and hybrid seed mutation. First, we use symbolic execution in a lightweight approach to generate qualiﬁed initial seeds which then guide the fuzzer through complex checks. Second, we apply a statistical seed selection algorithm to balance the mutation frequency between different seeds. Further, we develop a hybrid mutation strategy. The random and restricted mutation strategies are combined to maintain a dynamic balance between global exploration and deep search . [DeepFuzzer: Accelerated Deep Greybox Fuzzing](https://commons.erau.edu/cgi/viewcontent.cgi?article=2462&context=publication)
  
- [MEUZZ](https://github.com/RiS3-Lab/muse) by [RiS3 Lab Of Northeastern University](https://github.com/RiS3-Lab)
  + Seed scheduling is a prominent factor in determining the yields of hybrid fuzzing. Existing hybrid fuzzers schedule seeds based on fixed heuristics that aim to predict input utilities. However, such heuristics are not generalizable as there exists no one-size-fits-all rule applicable to different programs. They may work well on the programs from which they were derived, but not others. To overcome this problem, we design a Machine learning-Enhanced hybrid fUZZing system (MEUZZ), which employs supervised machine learning for adaptive and generalizable seed scheduling. MEUZZ determines which new seeds are expected to produce better fuzzing yields based on the knowledge learned from past seed scheduling decisions made on the same or similar programs. MEUZZ's learning is based on a series of features extracted via code reachability and dynamic analysis, which incurs negligible runtime overhead (in microseconds). Moreover, MEUZZ automatically infers the data labels by evaluating the fuzzing performance of each selected seed. [MEUZZ: Smart Seed Scheduling for Hybrid Fuzzing](https://yaohway.github.io/meuzz.pdf)
  
- [winafl-powermopt](https://github.com/hardik05/winafl-powermopt) by [Hardik Shah](https://github.com/hardik05)
  + winafl with mopt mutators and afl fast power schedulers

- [SymQEMU](https://github.com/eurecom-s3/symqemu) by [Sebastian Poeplau](https://github.com/sebastianpoeplau) and [Aurélien Francillon](https://twitter.com/aurelsec)
  + Symbolic execution is a powerful technique for software analysis and bug detection. Compilation-based symbolic execution is a recently proposed flavor that has been shown to improve the performance of symbolic execution significantly when source code is available. We demonstrate a novel technique to enable compilation-based symbolic execution of binaries (i.e., without the need for source code). Our system, SymQEMU, builds on top of QEMU, modifying the intermediate representation of the target program before translating it to the host architecture. This enables SymQEMU to compile symbolic-execution capabilities into binaries and reap the associated performance benefits while maintaining architecture independence. We present our approach and implementation, and we show that it outperforms the state-of-the-art binary symbolic executors S2E and QSYM with statistical significance; on some benchmarks, it even achieves better performance than the source-based SymCC. Moreover, our tool has found a previously unknown vulnerability in the well-tested libarchive library, demonstrating its utility in testing real-world software. [SymQEMU - Compilation-based symbolic execution for binaries](http://s3.eurecom.fr/docs/ndss21_symqemu.pdf)

- [uAFL - Typestate-Guided Fuzzer for Discovering Use-after-Free Vulnerabilities ](https://yuleisui.github.io/publications/icse20.pdf) 
  + Existing coverage-based fuzzers usually use the individual control flow graph (CFG) edge coverage to guide the fuzzing process, which has shown great potential in finding vulnerabilities. However, CFG edge coverage is not effective in discovering vulnerabilities such as use-after-free (UaF). This is because, to trigger UaF vulnerabilities, one needs not only to cover individual edges, but also to traverse some (long) sequence of edges in a particular order, which is challenging for existing fuzzers. To this end, we propose to model UaF vulnerabilities as typestate properties, and develop a typestateguided fuzzer, named UAFL, for discovering vulnerabilities violating typestate properties. Given a typestate property, we first perform a static typestate analysis to find operation sequences potentially violating the property. Our fuzzing process is then guided by the operation sequences in order to progressively generate test cases triggering property violations. In addition, we also employ an information flow analysis to improve the efficiency of the fuzzing process. We have performed a thorough evaluation of UAFL on 14 widely-used real-world programs. The experiment results show that UAFL substantially outperforms the state-of-the-art fuzzers, including AFL, AFLFast, FairFuzz, MOpt, Angora and QSYM, in terms of the time taken to discover vulnerabilities. We have discovered 10 previously unknown vulnerabilities, and received 5 new CVEs.


- [fuzzilli](https://github.com/googleprojectzero/fuzzilli) maintained by [Samuel Groß](https://github.com/saelo) from Google Project Zero
  + A (coverage-)guided fuzzer for dynamic language interpreters based on a custom intermediate language ("FuzzIL") which can be mutated and translated to JavaScript.

- [winnie](https://github.com/sslab-gatech/winnie) by [SSLab of Georgia Tech University](https://gts3.org/)
  + [WINNIE : Fuzzing Windows Applications with Harness Synthesis and Fast Cloning](https://www.ndss-symposium.org/wp-content/uploads/ndss2021_6A-3_24334_paper.pdf)
  In this paper, we propose two solutions to address the challenges Windows fuzzing faces. Our system, WINNIE, first tries to synthesize a harness for the application, a simple program that directly invokes target functions, based on sample executions. It then tests the harness, instead of the original complicated program, using an efficient implementation of fork on Windows. Using these techniques, WINNIE can bypass irrelevant GUI code to test logic deep within the application. We used WINNIE to fuzz 59 closed-source Windows binaries, and it successfully generated valid fuzzing harnesses for all of them. In our evaluation, WINNIE can support 2.2x more programs than existing Windows fuzzers could, and identified 3.9x more program states and achieved 26.6x faster execution. In total, WINNIE found 61 unique bugs in 32 Windows binaries.

- [fuzzolic](https://github.com/season-lab/fuzzolic) by [Software Analysis and Optimization Laboratory at Sapienza University of Rome](https://github.com/season-lab)
  + In this paper, we investigate whether techniques borrowed from the fuzzing domain can be applied to check whether symbolic formulas are satisfiable in the context of concolic and hybrid fuzzing engines, providing a viable alternative to classic SMT solving techniques. We devise a new approximate solver, FUZZY-SAT, and show that it is both competitive with and complementary to state-of-the-art solvers such as Z3 with respect to handling queries generated by hybrid fuzzers [Fuzzing Symbolic Expressions
](https://arxiv.org/pdf/2102.06580.pdf)

- [aflteam](https://github.com/MelbourneFuzzingHub/aflteam) by [Thuan Pham](https://github.com/thuanpv), [Manh-Dung Nguyen](https://github.com/strongcourage) and [Ta Quang Trung](https://github.com/taquangtrung)
  + [Towards Systematic and Dynamic Task Allocation for Collaborative Parallel Fuzzing](https://thuanpv.github.io/publications/AFLTeam-ASE21-NIER.pdf) Parallel coverage-guided greybox fuzzing is the most common setup for vulnerability discovery at scale. However, so far it has received little attention from the research community compared to single-mode fuzzing, leaving open several problems particularly in its task allocation strategies. Current approaches focus on managing micro tasks, at the seed input level, and their task division algorithms are either ad-hoc or static. In our framework, we leverage research on graph partitioning and search algorithms to propose a systematic and dynamic task allocation solution that works at the macro-task level. First, we design an attributed graph to capture both the program structures (e.g., program call graph) and fuzzing information (e.g., branch coverage). Second, our graph partitioning algorithm divides the global program search space into sub-search-spaces. Finally our search algorithm prioritizes these sub-search-spaces (i.e., tasks) and explores them to maximize code coverage and number of bugs found.

- [Registered Report: Dissecting American Fuzzy Lop - A FuzzBench Evaluation](https://www.researchgate.net/publication/358931321_Registered_Report_Dissecting_American_Fuzzy_Lop_-_A_FuzzBench_Evaluation)
  + AFL is one of the most used and extended fuzzing projects, adopted by industry and academic researchers alike. While the community agrees on AFL's effectiveness at discovering new vulnerabilities and at its outstanding usability, many of its internal design choices remain untested to date. Security practitioners often clone the project "as-is" and use it as a starting point to develop new techniques, usually taking everything under the hood for granted. Instead, we believe that a careful analysis of the different parameters could help modern fuzzers to improve their performance and explain how each choice can affect the outcome of security testing, either negatively or positively. The goal of this paper is to provide a comprehensive understanding of the internal mechanisms of AFL by performing experiments and comparing different metrics used to evaluate fuzzers. This will prove the efficacy of some patterns and clarify which aspects are instead outdated. To achieve this, we set up nine unique experiments that we carried out on the popular Fuzzbench platform. Each test focuses on a different aspect of AFL, ranging from its mutation approach to the feedback encoding scheme and the scheduling methodologies. Our preliminary findings show that each design choice affects different factors of AFL. While some of these are positively correlated with the number of detected bugs or the target coverage, other features are related to usability and reliability. Most important, the outcome of our experiments will indicate which parts of AFL we should preserve in modern fuzzers.

- [Guiding Greybox Fuzzing with Mutation Testing](https://rohan.padhye.org/files/mu2-draft.pdf) by [Isabella Laybourn, Rohan Padhye and other members of Carnegie-Mellon's cmu-pasta lab](https://github.com/cmu-pasta)
  + [Mu2](https://github.com/cmu-pasta/mu2) is a greybox fuzznig procedure that agugments the code coverage feedback to save new inputs if they increase the mutation scrore across all previously generated inputs.

- [Fuzzing with Data Dependency Information](http://193.55.114.4/docs/eurosp22_mantovani.pdf) by Alessandro Mantovani, Andrea Fioraldi, Davide Balzarotti from [S3 Security group of EURECOM](https://s3.eurecom.fr/)
  + Recent advances in fuzz testing have introduced
several forms of feedback mechanisms, motivated by the
fact that for a large range of programs and libraries, edgecoverage alone is insufficient to reveal complicated bugs. Inspired by this line of research, we examined existing program representations looking for a match between expressiveness of the structure and adaptability to the context of fuzz testing. In particular, we believe that data dependency graphs (DDGs) represent a good candidate for this task, as the set of information embedded by this data structure is potentially useful to find vulnerable constructs by stressing combinations of def-use pairs that would be difficult for a traditional fuzzer to trigger. Since some portions of the dependency graph overlap with the control flow of the program, it is possible to reduce the additional instrumentation to cover only “interesting” data-flow dependencies, those that help the fuzzer to visit the code in a distinct way compared to standard methodologies.

- [Registered Report: DATAFLOW Towards a Data-Flow-Guided Fuzzer](https://www.ndss-symposium.org/wp-content/uploads/fuzzing2022_23001_paper.pdf) by [Adrian Herrera](https://github.com/adrianherrera) from [Engineering & Computer Science at ANU](https://cecs.anu.edu.au/)
  + We present [datAFLow](https://github.com/HexHive/datAFLow), a greybox fuzzer driven by lightweight data-flow profiling. Whereas control-flow edges represent the order of operations in a program, data-flow edges capture the dependencies between operations that produce data values and the operations that consume them: indeed, there may be no control dependence between those operations. As such, data-flow coverage captures behaviors not visible as control flow and intuitively discovers more or different bugs. Moreover, we establish a framework for reasoning about data-flow coverage, allowing the computational cost of exploration to be balanced with precision

- [sFuzz](https://github.com/seal9055/sfuzz) by [seal9055](https://twitter.com/seal9055)
  + This is a coverage-guided, emulation based greybox fuzzer that makes use of a custom Just-In-Time compiler to achieve near-native performance. It works by lifting RISC-V elf binaries to an intermediate representation before JIT compiling them to x86 during execution. During JIT compilation the code is instrumented to enable fuzzing-improvements such as coverage tracking, asan, cmpcov, or snapshot-based fuzzing.
  
- [LibAFL](https://github.com/AFLplusplus/LibAFL) Advanced Fuzzing Library - Slot your Fuzzer together in Rust! Scales across cores and machines. For Windows, Android, MacOS, Linux, no_std, ...
  - [LibAFL: A Framework to Build Modular and Reusable Fuzzers](https://www.s3.eurecom.fr/docs/ccs22_fioraldi.pdf) 
  
- [stateafl](https://github.com/stateafl/stateafl) by Roberto Natella
  + StateAFL is a fuzzer designed for network servers. It extends the original idea of the AFL fuzzer, which automatically evolves fuzz inputs to maximize code coverage. In addition to code coverage, StateAFL seeks to maximize protocol state coverage. The aim of this tool is to contribute towards a completely-automated solution for stateful protocol fuzzing (similarly to what AFL was able to achieve for stateless programs) and to promote a wider application of fuzzing in real-world systems. The fuzzer does not require developers to implement custom message parsers for the protocol under test. StateAFL automatically infers the current protocol state of the server. At compile-time, it instruments the target server with probes on memory allocations and network I/O operations. At run-time, it takes snapshots of long-lived data within process memory for each protocol iteration (see figure), and it applies fuzzy hashing to map the in-memory state to a unique protocol state.



-----------------

### Tutorials
- [AFL-Workshop](https://github.com/mykter/afl-training)
  + Materials of the "Fuzzing with AFL" workshop by Michael Macnair (@michael_macnair)
  
- [Fuzzing with AFL is an Art](https://moyix.blogspot.com/2016/07/fuzzing-with-afl-is-an-art.html#:~:targetText=American%20Fuzzy%20Lop%2C%20or%20AFL,vulnerabilities%20in%20high%2Dprofile%20software.)
  + an awesome AFL coverage improvement idea by [Brendan Dolan-Gavitt aka moyix](https://twitter.com/moyix) of Computer Science and Engineering Department at NYU-Poly
  
- [Software Exploit Development – Fuzzing with AFL](http://thecyberrecce.net/2017/03/20/software-exploit-development-fuzzing-with-afl/)

- [Basic usage of American Fuzzy Lop with real world examples](https://volatileminds.net/2015/06/29/basic-afl-usage.html)

- [Advanced usage of American Fuzzy Lop with real world examples](https://volatileminds.net/2015/07/01/advanced-afl-usage.html)

- [Advanced AFL usage with real-world examples -- preeny and dictionaries](https://volatileminds.net/2015/08/20/advanced-afl-usage-preeny.html)

- [Advanced AFL usage with real-world examples -- Persistent mode](https://volatileminds.net/2015/08/20/advanced-afl-usage-peristent-mode.html)

- [More advanced usage of AFL with real world examples -- Fuzzing libraries](https://volatileminds.net/2015/08/05/advanced-afl-usage-fuzzing-libraries.html)

- [Fuzzing – how to find bugs automagically using AFL](http://9livesdata.com/fuzzing-how-to-find-bugs-automagically-using-afl)

- [Effective AFL Fuzzing 1: Better Harness](https://oxhat.blogspot.com/2018/09/effective-afl-fuzzing-1-better-harness.html)

- [AFL / WinAFL Tips and Tricks](https://blog.fadyothman.com/afl-tips-tricks/)

- [Hunting For Bugs With AFL 101 - A PRIMER](https://research.aurainfosec.io/hunting-for-bugs-101/)

- [Fuzzing capstone using AFL persistent mode](https://toastedcornflakes.github.io/articles/fuzzing_capstone_with_afl.html)

- [afl-unicorn: Fuzzing Arbitrary Binary Code](https://hackernoon.com/afl-unicorn-fuzzing-arbitrary-binary-code-563ca28936bf)

- [INTRO TO AMERICAN FUZZY LOP – FUZZING WITH ASAN AND BEYOND](https://countuponsecurity.com/2018/04/24/intro-to-american-fuzzy-lop-fuzzing-with-asan-and-beyond/)

- [Guided Fuzzing with Driller](https://blog.grimm-co.com/post/guided-fuzzing-with-driller/)

- [Super Awesome Fuzzing, Part One](https://blog.f-secure.com/super-awesome-fuzzing-part-one/)

- [INTRO TO AMERICAN FUZZY LOP – FUZZING IN 5 STEPS](https://countuponsecurity.com/2018/03/07/intro-to-american-fuzzy-lop-fuzzing-in-5-steps/)

- [How to Use Fuzzing in Security Research](https://www.ixiacom.com/company/blog/how-use-fuzzing-security-research)

- [Investigating Windows Graphics Vulnerabilities: A Reverse Engineering and Fuzzing Story](https://www.ixiacom.com/company/blog/investigating-windows-graphics-vulnerabilities-reverse-engineering-and-fuzzing-story)

- [Hunting For Bugs With AFL 101 - A PRIMER](https://research.aurainfosec.io/hunting-for-bugs-101/)

- [Fuzzing arbitrary functions in ELF binaries](https://blahcat.github.io/2018/03/11/fuzzing-arbitrary-functions-in-elf-binaries/)

- [Filesystem Fuzzing with American Fuzzy Lop](https://events.static.linuxfound.org/sites/events/files/slides/AFL%20filesystem%20fuzzing%2C%20Vault%202016_0.pdf)

- [Fuzzing workflows; a fuzz job from start to finish](https://foxglovesecurity.com/2016/03/15/fuzzing-workflows-a-fuzz-job-from-start-to-finish/)

- [Finding pearls; fuzzing ClamAV](https://foxglovesecurity.com/2016/06/13/finding-pearls-fuzzing-clamav/)

- [Tutorial: Fuzzing GIMP](https://flimp.fuzzing-project.org/tutorial-fuzzing-gimp.html)

- [Fuzzing projects with american fuzzy lop (AFL)](https://0x00sec.org/t/fuzzing-projects-with-american-fuzzy-lop-afl/6498)

- [Fuzzing with AFL](https://breaking-bits.gitbook.io/breaking-bits/vulnerability-discovery/fuzzing-with-afl)

- [Starting fuzz with AFL](https://www.w0lfzhang.com/2017/11/30/Starting-fuzz-with-AFL/)

- [Fuzzing 101](https://github.com/RootUp/PHDays9/blob/master/Slides/Fuzzing-101_PHDays.pdf)
  + The prime focus of this workshop would be around the following areas: Input-based fuzzing (AFL), finding memory bugs using     ASAN with AFL integration, protocol fuzzing (HTTP, FTP, SMTP). Then we concluded the workshop by showcasing multiple bugs found during their research.
  
- [FUZZING FOR BEGINNERS](https://www.youtube.com/watch?v=O3hb6HV1ZQo&feature=youtu.be) by [Christoffer Jerkeby](https://twitter.com/Kuggofficial)
  + In this episode of "STÖK, time to learn something new". KUGG (Christoffer Jerkeby) From F-Secure shows STÖK the basics of FUZZING using American Fuzzy lop. They FUZZ a HTTP server and get two crashes, crashes that with the right exploit could give an attacker ROOT access using privilege escalation,  really interesting stuff!.   
  
- [F-Secure Labs Fuzzing C Programs Pasi & Kugg](https://www.youtube.com/watch?v=_ngq3yL0dkg) by Christoffer Jerkeby [@kuggofficial](https://twitter.com/Kuggofficial) and Pasi Saarinen [@pasi_s7](https://twitter.com/Pasi_S7)
  + A webinar covering how to get started with fuzzing, strategies software and experiences
  
- [Fuzzing the OpenSSH daemon using AFL](http://www.vegardno.net/2017/03/fuzzing-openssh-daemon-using-afl.html) by [Vegard Nossum
](https://twitter.com/vegard_no)
  + American Fuzzy Lop is a great tool. It does take a little bit of extra setup and tweaking if you want to go into advanced usage, but mostly it just works out of the box. In this post, I’ll detail some of the steps you need to get started with fuzzing the OpenSSH daemon (sshd) and show you some tricks that will help get results more quickly. The AFL home page already displays 4 OpenSSH bugs in its trophy case; these were found by Hanno Böck who used an approach similar to that outlined by Jonathan Foote on how to fuzz servers with AFL.
I take a slightly different approach, which I think is simpler: instead of intercepting system calls to fake network activity, we just run the daemon in “inetd mode”. The inet daemon is not used very much anymore on modern Linux distributions, but the short story is that it sets up the listening network socket for you and launches a new process to handle each new incoming connection. inetd then passes the network socket to the target program as stdin/stdout. Thus, when sshd is started in inet mode, it communicates with a single client over stdin/stdout, which is exactly what we need for AFL.

- [Fuzzing FastCGI With AFL-Fuzz](https://medium.com/@omaidfaizyar/fuzzing-fastcgi-an-odyssey-4ffc1c72a732) by [Omaid Faizyar](https://medium.com/@omaidfaizyar)

- [Fuzzing Image Parsing in Windows, Part One: Color Profiles](https://www.fireeye.com/blog/threat-research/2020/09/fuzzing-image-parsing-in-windows-color-profiles.html)


