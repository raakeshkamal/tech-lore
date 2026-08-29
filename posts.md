# Posts — the canon (individual posts worth re-reading)

## Distributed systems & data

- [The Log: What every software engineer should know about real-time data's unifying abstraction — Jay Kreps](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying) — the essay that introduced Kafka; log-structured thinking in one shot. `dist-sys` `data`
- [Notes on distributed systems for young bloods — Jeff Hodges](https://www.somethingsimilar.com/2013/01/14/notes-on-distributed-systems-for-young-bloods.html) — hard-won practical heuristics; still the best orientation doc. `dist-sys`
- [Please stop calling databases CP or AP — Martin Kleppmann](https://martin.kleppmann.com/2015/05/11/please-stop-calling-databases-cp-or-ap.html) — kills the CAP Zombie; nuance that saves designs. `dist-sys`
- [You Can't Sacrifice Partition Tolerance — Coda Hale](https://codahale.com/you-cant-sacrifice-partition-tolerance/) — CAP arithmetic done honestly. `dist-sys`
- [How Discord Scaled Elixir to 5,000,000 Concurrent Users](https://discord.com/blog/how-discord-scaled-elixir-to-5-000-000-concurrent-users) — concurrency, contention, and one brilliant fan-out fix. `dist-sys`
- [Inside the Magic Pocket — Dropbox](https://dropbox.tech/infrastructure/inside-the-magic-pocket) — exabyte-scale blob storage from first principles. `storage`
- [How Figma's multiplayer technology works](https://www.figma.com/blog/how-figmas-multiplayer-technology-works/) — conflict resolution and sync under the CRDT-ish hood. `systems`
- [Blameless PostMortems and a Just Culture — Etsy](https://www.etsy.com/codeascraft/2012/05/22/blameless-postmortems/) — the origin of blameless postmortems. `sre` `culture`

## Performance & low latency

- [Branch prediction and the performance of branches — Dan Luu](https://danluu.com/branch-prediction/) — microbenchmarks against real hardware; the perf-reasoning template. `perf` `cpp`
- [C++ Performance Checklist for Low-Latency Systems — John Farrier](https://johnfarrier.com/c-performance-checklist-for-low-latency-systems) — review-ready checklist for trading/real-time/embedded C++. `cpp` `low-latency`
- [List of 600+ Low-Latency C++ Techniques — David Spuler, Aussie AI](https://www.aussieai.com/research/low-latency) — taxonomic sweep of LL techniques, from allocation to SIMD. `cpp` `low-latency`
- [Flame Graphs — Brendan Gregg](https://www.brendangregg.com/flamegraphs.html) — the tool that changed profiling; read before any profiler session. `perf`
- [Latency Numbers Every Programmer Should Know — interactive](https://colin-scott.github.io/personal_website/research/interactive_latency.html) — the numbers, updated, clickable. `perf`
- [Optiver: Designing low-latency C++ trading systems — David Gross](https://www.optiver.com/insights/technology-blog/designing-low-latency-cpp-systems/) — writeup + talk on nanoseconds-matter C++. `cpp` `low-latency`

## Culture & shipping

- [Choose Boring Technology — Dan McKinley](https://mcfunley.com/choose-boring-technology) — innovation tokens; the single most useful engineering-decision heuristic. `culture`
- [The Next Two Years of Software Engineering — Addy Osmani](https://addyosmani.com/blog/next-two-years) — junior-dev hiring collapse vs. rebound scenarios and how to hedge both; the post behind bigboxSWE's "death of junior developers" video. `culture` `ai` *(via @bigboxSWE)*
- [New trend: extreme hours at AI startups — The Pragmatic Engineer](https://blog.pragmaticengineer.com/new-trend-extreme-hours-at-ai-startups) — 996 migrating from China to SF AI startups (Cognition et al., 80+ hr weeks); cited in bigboxSWE's "developers are exhausted". `culture` *(via @bigboxSWE)*
- [Ghostty Is Leaving GitHub — Mitchell Hashimoto](https://mitchellh.com/writing/ghostty-leaving-github) — 18 years of daily GitHub use ends over reliability decay; what platform rot does to open source. `culture` `foss` *(via @bigboxSWE)*
- [How Much Are GitHub Stars Worth to You? — The Guild](https://the-guild.dev/blog/judging-open-source-by-github-stars) — they actually bought fake GitHub stars (€8/100, premium tiers, Stripe receipts) and show how Astronomer grades them A–E; source for bigboxSWE's dark-side-of-GitHub video. `sec` `culture` *(via @bigboxSWE)*
- [AI fatigue is real and nobody talks about it — Siddhant Khare](https://siddhantkhare.com/writing/ai-fatigue-is-real) — the FOMO treadmill, tool churn, and making peace with AI as a 70%-useful first draft; the post behind bigboxSWE's anti-AI-fatigue video. `ai` `culture` *(via @bigboxSWE)*
- [How I ship projects at big tech companies — Sean Goedecke](https://www.seangoedecke.com/) — the shipping playbook behind HN's top posts of 2024-25. `culture` *(link to blog; post is 2024)*
- [Writing a tech blog people want to read — Sean Goedecke](https://www.seangoedecke.com/) — meta but practical if this repo ever goes public. `culture` `writing`

## Debugging / SRE

- Anything from [rachelbythebay.org](https://rachelbythebay.org/w/) — start with the "big list of bugs" and the errno posts. `debugging` `sre`

## Long-form / reference shelf

- [What Every Programmer Should Know About Memory — Ulrich Drepper](https://akkadia.org/drepper/cpumemory.pdf) — 114 pages of hardware memory truth; still the reference. `perf` `cpp`
- [Regular Expression Matching Can Be Simple And Fast — Russ Cox](https://swtch.com/~rsc/regexp/regexp1.html) — theory-to-practice masterpiece on automata vs backtracking. `algorithms`
- [Game Engine Black Book: DOOM — Fabien Sanglard](https://fabiensanglard.net/gebbdoom/) — free PDF; 90s shipping under 4MB constraints. `graphics` `cpp`
- [How Complex Systems Fail — Richard I. Cook](https://how.complexsystems.fail/) — 18 stark sentences; the SRE lens. `sre` `culture`
- [The Tail at Scale — Dean & Barroso](https://research.google/pubs/the-tail-at-scale/) — the paper behind tail-latency engineering. `perf` `dist-sys`

## Networking & cloud

- [Measuring Latencies Between AWS Availability Zones — Bits and Cloud](https://www.bitsand.cloud/posts/cross-az-latencies) — pinged 28 regions to find the 10 slowest AZ pairs; the post behind Ben Dicken's AZ-latency visualization. `net` `cloud`
- [How flat is replacing fat in AWS data center networks — Amazon Science](https://www.amazon.science/blog/how-flat-is-replacing-fat-in-aws-data-center-networks) — quasi-random physical wiring, 69% fewer routers; recommended on Ben's papers stream. `net` `infra`
- [Scaling PostgreSQL to power 800 million ChatGPT users — Bohan Zhang, OpenAI Engineering](https://openai.com/engineering/) — single primary + ~50 replicas, p99 in double-digit ms; Ben: "they do some pretty incredible things." `db` `dist-sys` *(slug verify)*

## Unverified — to vet

*(inbox — promote after reading, with URL)*
- Cited on-screen in @bigboxSWE videos but never named aloud — recover from video descriptions if possible: the TypeScript-fanboys takedown article ("Toxic Programming Fans"), the job-postings-by-title blog with the systems/ML-engineer graph ("The programming skill that will dominate this era", an a16z chart), and the Team PCP GitHub-hack malware analysis thread ("The time GitHub got hacked").
- Shopify Black Friday / BFCM engineering posts — Ben Dicken cites their traffic-scale stats in "Why BIGGER Servers won't save you." `scale`
- Jepsen analyses — pick 1–2 representative (e.g. MongoDB, Elasticsearch) to canonize. `dist-sys`
- Cloudflare rate-limiting / HTTP/3 deep dives — pick the best 2. `net`
- Ken Shirriff's ARM1 reverse-engineering series. `hardware`
- Herb Sutter's ISO trip reports — pick a recent one. `cpp`
- "Turning the Database Inside-Out" (Kleppmann, Strange Loop 2014) — talk; maybe lives in youtube.md instead.
- Jason Turner's "Best Practices for AI Tool Use in C++" (CppCon 2025) — if we care about AI+cpp.
