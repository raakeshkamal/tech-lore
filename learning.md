# Learning resources — meta-indexes & free course material

The meta shelf: awesome-lists for learning, university courses with fully free materials, free books and hands-on curricula — one per topic, mapped to the other files' sections. **Provenance: swept + URL-verified 2026-08-31 (GitHub API + HTTP), but content not yet skim-vetted** — entries still owe the usual read-before-promotion pass. The Security/RE shelf got a second deep sweep (URL-verified via live search; same skim-vet debt). Cross-links: courses with YouTube channels belong here *and* in `youtube.md`; books on this shelf that are "canon readings" may migrate to `papers.md`.

## Meta — lists of lists (all of CS)

- [awesome-courses (prakhar1989)](https://github.com/prakhar1989/awesome-courses) — ~70k★; the canonical index of university CS courses with free lectures/notes/assignments, by subject. `meta`
- [OSSU Computer Science](https://github.com/ossu/computer-science) — ~208k★; a complete free self-taught CS degree path with community study groups. `meta` *(via gh sweep)*
- [CS Self-Learning Guide (csdiy.wiki)](https://csdiy.wiki/en) — ~75k★; per-course self-study walkthroughs (what's public, what the labs feel like) for the famous open courses. `meta`
- [Teach Yourself CS](https://teachyourselfcs.com/) — nine subjects, one best-book + best-project each; the opinionated version of the above. `meta` `culture`
- [Build Your Own X](https://github.com/codecrafters-io/build-your-own-x) — ~544k★; step-by-step guides to recreating git, redis, compilers, OSes, databases from scratch. `meta` `systems`
- [Project-Based Learning](https://github.com/practical-tutorials/project-based-learning) — ~281k★; programming tutorials organized by the thing you build. `meta`
- [Free Programming Books (EbookFoundation)](https://github.com/EbookFoundation/free-programming-books) — ~395k★; the index of freely available programming books, every language. `meta`
- [Every Programmer Should Know](https://github.com/mtdvio/every-programmer-should-know) — ~100k★; mostly-technical concepts every software dev should know (latency, consistency, hashing, …). `meta` `culture`

## C++

- [awesome-cpp (fffaraz)](https://github.com/fffaraz/awesome-cpp) — ~73k★; the everything-index: C/C++ libraries, frameworks, resources. `cpp`
- [LearnCpp](https://www.learncpp.com/) — the free full-length C++ course site; the structured alternative to "learned C++ from Stack Overflow". `cpp`
- [C++ Best Practices (Jason Turner)](https://github.com/cpp-best-practices/cppbestpractices) — free collaborative online book of C++ best practices; rules you can review PRs against. `cpp`
- [Modern C++ Features (Anthony Calandra)](https://github.com/AnthonyCalandra/modern-cpp-features) — ~22k★; cheatsheet of C++11→C++23 language/library features. `cpp`

## Systems / performance / low latency

- [MIT 6.172 Performance Engineering of Software Systems](https://ocw.mit.edu/courses/6-172-performance-engineering-of-software-systems-fall-2018/) — full lectures, slides, and assignments free on OCW: bit hacks, caching, cache-oblivious algorithms, parallelism. `perf` `cpp`
- [perf-ninja (Denis Bakhvalov)](https://github.com/dendibakh/perf-ninja) — hands-on homework-style course on low-level performance analysis and tuning; by the Easyperf author (see `blogs.md`). `perf` `cpp`
- [awesome-quant (wilsonfreitas)](https://github.com/wilsonfreitas/awesome-quant) — ~29k★; quant-finance libraries & learning resources across languages; the trading-side cousin of the low-latency shelf. `low-latency`

## OS / networking / compilers

- [OSTEP — Operating Systems: Three Easy Pieces](https://pages.cs.wisc.edu/~remzi/OSTEP/) — the free OS book (virtualization/concurrency/persistence) + homework projects; the default OS course. `os` `c`
- [MIT 6.1810 (xv6)](https://pdos.csail.mit.edu/6.1810/) — build/extend a real small Unix kernel (xv6); lectures, book, and labs all public. `os` `c`
- [Writing an OS in Rust (phil-opp)](https://github.com/phil-opp/blog_os) — ~18k★; blog series building a bare-metal OS in Rust, Freestanding → async. `os` `rust`
- [CS:APP Labs](https://csapp.cs.cmu.edu/3e/labs.html) — bomb lab, attack lab, malloc lab; the self-study kits that turn *Computer Systems* from a book into a workout. `systems` `c`
- [Stanford CS144](https://cs144.github.io/) — computer networking with public labs: you build a complete TCP, then a router. `net` `c++`
- [Beej's Guides](https://beej.us/guide/) — free classic guides to network programming and Unix IPC; the on-ramp to sockets. `c` `net`
- [Cornell CS6120 — Advanced Compilers](https://www.cs.cornell.edu/courses/cs6120/2025fa/self-guided) — Adrian Sampson's self-guided advanced compilers course: video lectures + student-written lesson blog. `compilers`
- [awesome-compilers (aalhour)](https://github.com/aalhour/awesome-compilers) — ~10k★; compilers/interpreters/runtimes resources, courses and papers. `compilers`
- [Essentials of Compilation (Jeremy Siek)](https://github.com/IUCompilerCourse/Essentials-of-Compilation) — free book: build an incremental compiler, Racket and Python editions. `compilers`

## Databases / distributed systems

- [awesome-database-learning (PingCAP)](https://github.com/pingcap/awesome-database-learning) — ~11k★; the learning-materials index for database internals: courses, papers, talks, blog series. `db`
- [PingCAP Talent Plan](https://github.com/pingcap/talent-plan) — ~11k★; open training courses: write a distributed KV store in Rust (mini-tikv), a Rust course. `db` `dist-sys` `rust`
- [CMU 15-445 (Intro to Database Systems)](https://15445.courses.cs.cmu.edu/) — Andy Pavlo's course; every semester's lectures free on YouTube, projects public. `db`
- [BusTub](https://github.com/cmu-db/bustub) — ~5k★; the educational DBMS you build 15-445's projects inside (buffer pool, B+ tree, executors, concurrency). `db` `c++`
- [CMU 15-721 (Advanced Database Systems)](https://15721.courses.cs.cmu.edu/spring2024/) — OLAP-engine internals: vectorization, compilation, join algorithms, one lecture per real system (Dremel, Snowflake, DuckDB…). `db` `perf`
- [Berkeley CS186](https://cs186berkeley.net/) — full DB course public: lectures + projects building a relational DB in Java (B+ trees, joins, optimization, recovery, 2PC/Paxos). `db`
- [MIT 6.5840 (Distributed Systems)](https://pdos.csail.mit.edu/6.824/) — the Raft-course; labs (MapReduce, Raft, KV) are public — the canonical dist-sys build-it course. `dist-sys` `go`
- [awesome-distributed-systems (theanalyst)](https://github.com/theanalyst/awesome-distributed-systems) — ~12k★; curated dist-sys learning index (books, papers, courses, talks). `dist-sys`
- [Distributed Systems for Fun and Profit (mixu)](https://book.mixu.net/distsys/) — free short ebook: replication, partitioning, consistency — reads the way the papers feel. `dist-sys`
- [DDIA References (Alex Petrov)](https://github.com/ept/ddia-references) — ~7k★; chapter-by-chapter literature list for *Designing Data-Intensive Applications*, by its co-author. `dist-sys` `db`
- [Let's Build a Simple Database (cstack)](https://github.com/cstack/db_tutorial) — ~10k★; write a SQLite clone in C, blog-series style. `db` `c`
- [PostgreSQL 14 Internals (Egor Rogov)](https://postgrespro.com/community/books/internals) — free 600+ page PDF on Postgres internals: MVCC, WAL, locks, indexes. `db`
- [The Internals of PostgreSQL (Hironobu Suzuki)](https://interdb.jp/) — free online book chapters: buffer manager, WAL, query processing, with figures. `db`
- [Use The Index, Luke](https://use-the-index-luke.com/) — free online book on SQL indexing and tuning; the book for "why isn't my query using the index". `db` `perf`

## Embedded / firmware

- [Embedded Systems — Shape The World (Valvano & Yerraballi)](https://users.ece.utexas.edu/~valvano/Volume1/E-Book) — UT Austin's free embedded course as a full online book (Cortex-M, from ports to FSMs); edX ancestor. `embedded`
- [Bootlin training materials](https://bootlin.com/docs/) — free PDF slide decks for kernel, drivers, Yocto, Buildroot, ARM, u-boot — vendor-grade training, freely licensed. `embedded-linux` `kernel`
- [awesome-zephyr-rtos (Golioth)](https://github.com/golioth/awesome-zephyr-rtos) — curated Zephyr projects & resources; pairs with Nordic DevAcademy (above in `embedded-robotics.md`). `rtos` `embedded`
- [The Embedded Rust Book](https://github.com/rust-embedded/book) — free book on bare-metal Rust firmware (no_std, HALs, peripherals); sister to awesome-embedded-rust. `embedded` `rust`
- [Wokwi](https://wokwi.com/) — free browser simulator for ESP32/STM32/RP2040/Arduino; test firmware without hardware. `embedded` `hardware`

## Robotics

- [Modern Robotics (Lynch & Park)](https://hades.mech.northwestern.edu/index.php/Modern_Robotics) — free preprint PDF of the standard modern-robotics textbook + full video lectures + Coursera specialization. `robotics` `control`
- [MIT 6.4210 — Robotic Manipulation (Tedrake)](https://manipulation.csail.mit.edu/) — every lecture/assignment free as runnable Drake notebooks; the manipulation course. `robotics` `control`
- [Hugging Face Learn — Robotics Course](https://huggingface.co/learn) — free LeRobot-based robotics course alongside their LLM/RL/Agents courses. `robotics` `ml`
- [awesome-robotics (kiloreux)](https://github.com/kiloreux/awesome-robotics) — ~7k★; broad robotics resources (courses, software, papers); complement to ahundt's list in `embedded-robotics.md`. `robotics`

## AI / ML

- [Neural Networks: Zero to Hero (Karpathy)](https://github.com/karpathy/nn-zero-to-hero) — ~24k★; build backprop through a transformer from scratch in code; the best intuition-for-free in ML. `ml`
- [fast.ai — Practical Deep Learning](https://course.fast.ai/) — free course + free book (`fastai/fastbook`, ~25k★ notebooks); top-down "train first, theorize later". `ml`
- [Hugging Face Learn](https://huggingface.co/learn) — free course catalog: LLM course, Deep RL, Agents, Diffusion, CV, Audio, smol-course. `ml` `ai`
- [Stanford CS336 — Language Modeling from Scratch](https://cs336.stanford.edu/) — lectures free on YouTube, assignments public: tokenizer→transformer→scaling→RLHF, from-scratch rules (no numpy in A1). `ml` `ai`
- [Dive into Deep Learning (d2l.ai)](https://d2l.ai/) — free interactive textbook where every section is a runnable notebook; math+figures+code. `ml`
- [The Little Book of Deep Learning (Fleuret)](https://fleuret.org/francois/lbdl.html) — free (CC) short DL book, updated v1.3 2026, designed to read on a phone. `ml`
- [CS231n Notes](https://cs231n.github.io/) — Stanford's free ConvNet/vision course notes + assignments; still the cleanest derivation set for backprop/CNNs. `ml`
- [Made With ML](https://madewithml.com/) — free applied ML/MLOps course: design → develop → deploy → iterate. `ml` `mlops`

## Security / reverse engineering

- [pwn.college (ASU)](https://pwn.college/) — free hands-on cybersecurity education platform: 1000+ challenges across shellcode, RE, memory corruption, kernel; powers ASU's actual curriculum. `sec`
- [OpenSecurityTraining2](https://ost2.fyi/) — free deep-dives: x86-64 architecture, debuggers (Ghidra/Simics), C++ reversing, TPM, SPI — "world's deepest cybersecurity training, free is a bonus". `sec` `re`
- [awesome-ctf (apsdehal)](https://github.com/apsdehal/awesome-ctf) — ~12k★; CTF frameworks, tools, resources. `sec`
- [Nightmare (guyinatuxedo)](https://guyinatuxedo.github.io/) — intro binary-exploitation/RE course built from 90+ CTF challenges, laid out linearly by technique (stack overflows → format strings → shellcoding → heap → RE), each with a full hand-holding writeup; all open-source tooling ([repo](https://github.com/guyinatuxedo/nightmare), ~3k★). `sec` `re`
- [awesome-reverse-engineering (wtsxDev)](https://github.com/wtsxDev/reverse-engineering) — ~10k★; RE resources across platforms. `sec` `re`
- [awesome-malware-analysis (rshipp)](https://github.com/rshipp/awesome-malware-analysis) — ~14k★; malware analysis tools, papers, resources. `sec`
- [OverTheWire Wargames](https://overthewire.org/wargames/) — free SSH wargames (Bandit et al.); the classic Linux/CLI security on-ramp. `sec` `linux`
- [CryptoHack](https://cryptohack.org/) — free crypto challenges: learn modern cryptography by breaking it. `sec`
- [picoCTF](https://picoctf.org/) — CMU's free year-round beginner CTF with a full learning platform. `sec`
- [RPISEC — Modern Binary Exploitation](https://github.com/RPISEC/MBE) — ~6k★; full university course (lectures, labs, Warzone VM) from x86 RE through defeating canaries/DEP/ASLR/RELRO; student-run, entirely free. `sec` `course`
- [RPISEC — Malware Analysis](https://github.com/RPISEC/Malware) — the sister course: static/dynamic malware analysis, packing, deobfuscation, forensics, with lab VM. `sec` `malware` `course`
- [CTF Field Guide (Trail of Bits)](https://trailofbits.github.io/ctf/) — free self-guided course distilling vuln discovery, exploitation, tooling and tradecraft into CTF-shaped workouts. `sec` `meta`
- [Azeria Labs — ARM Assembly Basics](https://azeria-labs.com/writing-arm-assembly-part-1/) — the canonical free ARM RE/exploit-dev tutorial series (7 parts); matured into the *Blue Fox* book (paid). `sec` `re` `arm`
- [OWASP MASTG](https://mas.owasp.org/MASTG/) — ~13k★; the free mobile bible: iOS/Android internals, static/dynamic analysis, tampering and anti-RE resilience testing. `sec` `mobile` `re`
- [Corelan](https://www.corelan.be/) — two decades of free Windows exploit-dev tutorials (stack → SEH → egghunters → ROP/DEP → heap), now getting Win11-x64 video re-dos. `sec` `exploitation` `windows`
- [Malware Unicorn — RE101/RE102](https://malwareunicorn.org/workshops/re101.html) — free hands-on Windows malware RE workshops: lab setup → triage → static/dynamic → anti-RE, packing, VM evasion. `sec` `malware`
- [PMAT labs (HuskyHacks)](https://github.com/HuskyHacks/PMAT-labs) — free-forever labs for Practical Malware Analysis & Triage (course video preview free on YouTube); the friendliest structured on-ramp to malware triage. `sec` `malware`
- [Sam Bowne — CNIT 126 Practical Malware Analysis](https://samsclass.info/126/126_S25.shtml) — City College of SF's full malware course: slides, videos and hands-on projects built on the *Practical Malware Analysis* book, all free. `sec` `malware` `course`
- [Exploit Education (Andrew Griffiths)](https://exploit.education/) — the VM lineage that trained a generation: Nebula (Linux privesc) → Protostar/Phoenix (stack, format strings, heap; x86/ARM/aarch64) → Fusion (mitigation bypass). `sec` `exploitation`
- [ROP Emporium](https://ropemporium.com/) — eight focused challenges (ret2win → ret2csu) teaching return-oriented chaining on x86/ARM/MIPS; the ROP drill yard. `sec` `exploitation`
- [pwnable.kr](http://pwnable.kr/) / [pwnable.tw](https://pwnable.tw/) — the classic free pwn wargames: kr for approachable reps, tw for serious ROP/heap gauntlets. `sec`
- [Microcorruption](https://microcorruption.com/) — embedded-security CTF: debug MSP430 smart-lock firmware and break the lock; the best assembly intro disguised as a puzzle game. `sec` `embedded` `re`
- [crackmes.one](https://crackmes.one/) — ~4.7k user-submitted crackmes with difficulty ratings and writeups; infinite keygen-me reps. `sec` `re`
- [Malware-Traffic-Analysis.net](https://www.malware-traffic-analysis.net/training-exercises.html) — pcap exercises from real infections (Emotet, Qakbot, IcedID…) plus Wireshark tutorials; the free network-forensics gym. `sec` `malware` `dfir`
- [vx-underground](https://vx-underground.org/) — the largest public malware sample & paper collection; research-grade corpus (detonate only in lab VMs). `sec` `malware`
- [DFIR Diva — free/affordable malware-RE training index](https://training.dfirdiva.com/listing-category/malware-analysis-and-re) — kept-current meta-list of courses and workshops; restock this shelf from it. `sec` `meta`

## Electronics / hardware

- [awesome-electronics (kitspace)](https://github.com/kitspace/awesome-electronics) — ~8k★; resources for electronic engineers & hobbyists: courses, books, podcasts, tools. `hardware`
- [All About Circuits — Textbook](https://www.allaboutcircuits.com/textbook/) — free full electronics textbook series (DC/AC → semiconductors → digital). `hardware`
- [awesome-fpga (Vitorian)](https://github.com/Vitorian/awesome-fpga) — FPGA learning resources; for when the day-job scope grows FPGA-shaped. `fpga` `hardware`

## Papers-reading meta (cross-link to `papers.md`)

- [Papers We Love](https://github.com/papers-we-love/papers-we-love) — ~109k★; the canonical repo of classic CS papers + chapter meetups; the missing prior-art for our papers shelf. `meta` `papers`
- [The Morning Paper (Adrian Colyer)](https://blog.acolyer.org/) — short daily-ish paper summaries from a decade of CS research; RSS available. `meta` `papers`

## Unverified — to vet

*(inbox — found but not URL/API-verified yet, or needs a scope decision)*
- HFTrader/awesome-programming-resources — includes a low-latency trading reading list (Nasdaq OUCH / CME MDP 3.0 specs, Bucher's *Insights into Performance*); vet depth + placement vs `blogs.md` trading section. `low-latency`
- 0burak/imperial_hft — low-latency C++ techniques repo (disruptor pattern, lock-free); small, vet quality. `cpp` `low-latency`
- drom/awesome-riscv — RISC-V resources; add if RISC-V scope grows. `hardware` `embedded`
- conanhujinming/comments-for-awesome-courses — 名校公开课评价网: reviews of open university courses (Chinese). `meta`
- CS:APP labs URL (`csapp.cs.cmu.edu/3e/labs.html`) — verify the self-study kit pages still carry all labs.
- "Essentials of Compilation" repo URL (IUCompilerCourse) — pin canonical edition (Racket vs Python) before promoting.
- Embedded Online Conference (free annual event) — confirm it still runs & where. `embedded`
- Nancy Leveson's STAMP/STPA free course material (MIT) — safety engineering adjacent to the Barr Group entry. `safety`
- MIT 6.S081 vs 6.1810 numbering — confirm the xv6 course URL stays canonical across semesters.
- decide: HF "Robotics Course" entry vs `embedded-robotics.md` LeRobot entry — dedupe on next pass.
- begin.re — beginner RE challenge site; verify it's still alive before promoting. `sec` `re`
- RE4B / challenges.re (Dennis Yurichev) — free "Reverse Engineering for Beginners" book + challenges; pin the canonical download URL (beginners.re). `sec` `re`
- 0xMR-robot's "Ultimate Resource List for Malware Analysis & RE" — meta-list candidate; skim for entries we're missing. `sec` `meta`
- Roppers Academy — free security-fundamentals curriculum; vet depth vs OverTheWire/pwn.college. `sec`
- HackSys Extreme Vulnerable Driver (HEVD) — deliberately-vulnerable Windows kernel driver for kernel-exploit practice. `sec` `windows`
- 8ksec.io — ARM/mobile exploit-dev courses; vet free vs paid. `sec` `arm`
- Guided Hacking — game-hacking/RE learning platform; vet quality. `sec` `re`
