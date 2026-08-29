# Blogs — sites worth following

- [Cloudflare](https://blog.cloudflare.com/) — the deepest infra/systems writing on the web: HTTP internals, DDoS, networking, hardware. `dist-sys` `net` `perf`
- [Netflix Tech Blog](https://netflixtechblog.com/) — chaos engineering, streaming at scale, cloud architecture. `dist-sys` `sre`
- [Discord Engineering](https://discord.com/blog/) — Elixir/Rust at absurd concurrency, storage, realtime. `dist-sys` `rust`
- [Shopify Engineering](https://shopify.engineering/) — Ruby at scale, performance culture, incident write-ups. `perf` `culture`
- [Stripe Blog (engineering)](https://stripe.com/blog) — API design, payments infrastructure. Also published *Increment* magazine (archived, still gold). `culture` `api`
- [GitHub Engineering](https://github.blog/engineering/) — scaling the world's biggest dev platform, MySQL battles, resilience. `dist-sys` `db`
- [Slack Engineering](https://slack.engineering/) — Go, realtime messaging infra, debugging stories. `dist-sys` `go`
- [Uber Engineering](https://www.uber.com/blog/engineering/) — data infra, ML, geospatial at planet scale. `data` `ml`
- [LinkedIn Engineering](https://engineering.linkedin.com/blog) — Kafka lineage, streaming systems. `dist-sys` `data`
- [Airbnb Engineering](https://medium.com/airbnb-engineering) — ML infra, services, data tooling. `ml` `data`
- [Dropbox Tech Blog](https://dropbox.tech/) — storage systems, sync engines, Python/Rust at scale. `dist-sys` `storage`
- [Etsy Code as Craft](https://www.etsy.com/codeascraft) — the original postmortem culture blog. `sre` `culture`
- [Datadog Engineering](https://www.datadoghq.com/blog/engineering/) — observability internals, Go/C++ perf. `perf` `observability`
- [Tailscale Blog](https://tailscale.com/blog) — networking done beautifully, WireGuard, NAT traversal deep dives. `net` `sec`
- [Fly.io Blog](https://fly.io/blog/) — virtualization, networking, dist-sys explainers with attitude. `infra` `net`
- [Oxide Computer](https://oxide.computer/blog) — building servers from scratch: firmware, RISC-V, hardware+software. `embedded` `firmware` `rust`
- [Meta Engineering](https://engineering.fb.com/) — C++ perf, data centers, PyTorch. `cpp` `infra`
- [Google Research](https://research.google/blog/) — maps/papers-to-production; *The Tail at Scale* lineage. `research` `dist-sys`
- [AWS Architecture Blog](https://aws.amazon.com/blogs/architecture/) — patterns, well-architected thinking. `cloud`
- [Grab Engineering](https://engineering.grab.com/) — SE-Asia scale, nice embedded/mobile posts too. `dist-sys` `mobile`
- [PlanetScale Blog](https://planetscale.com/blog) — Ben Dicken's interactive deep dives: [B-trees & indexes](https://planetscale.com/blog/btrees-and-database-indexes), [sharding](https://planetscale.com/blog/database-sharding), [processes vs threads](https://planetscale.com/blog/processes-and-threads), [IO devices & latency](https://planetscale.com/blog/io-devices-and-latency), [caching](https://planetscale.com/blog/caching). The visuals make internals click. `db` `perf`
- [Amazon Science](https://www.amazon.science/blog/) — AWS/Amazon research made readable; e.g. the flat-datacenter-network redesign. `research` `net`

## Trading / low latency / performance

- [Optiver Technology](https://www.optiver.com/insights/technology-blog/) — ultra-low-latency C++, FPGA, real trading-system design (see the David Gross talk). `cpp` `perf` `low-latency`
- [Jane Street](https://blog.janestreet.com/) — OCaml, quant dev culture, genuinely deep systems posts. `ocaml` `perf` `culture`
- [Ahrefs Engineering](https://ahrefs.com/blog/engineering/) — crawling infra at petabyte scale; great perf write-ups (Nix, ClickHouse). `infra` `perf`
- [Mechanical Sympathy (Martin Thompson)](https://mechanicalsympathy.blogspot.com/) — hardware/software co-design, LMAX lineage. `perf` `low-latency`
- [Easyperf (Denis Bakhvalov)](https://easyperf.net/) — CPU perf analysis, branch misses, perf tooling. The practical perf blog. `perf` `cpp`
- [Travis Downs](https://travisdowns.github.io/) — microarchitecture forensics: memory, CPU internals, uarch quirks. `perf` `cpp` *(irregular but every post is gold)*
- [John Farrier](https://johnfarrier.com/) — C++ for long-lived systems, low-latency checklists, engineering culture. `cpp` `low-latency`
- [Brendan Gregg](https://www.brendangregg.com/) — flame graphs, systems performance, the observability canon. `perf` `linux`

## C++ / language nerds

- [Herb Sutter — Sutter's Mill](https://herbsutter.com/) — ISO committee trip reports; the pulse of where C++ is going. `cpp`
- [Fluent C++ (Jonathan Boccara)](https://www.fluentcpp.com/) — expressive C++, design, weekly cadence. `cpp`
- [Arthur O'Dwyer](https://quuxplusone.github.io/blog/) — standard-library lawyer; the person to read on templates and `<type_traits>` weirdness. `cpp`
- [Modernes C++ (Rainer Grimm)](https://www.modernescpp.com/) — C++20/23/26 features, concurrency, guidelines. `cpp`
- [Andreas Fertig](https://andreasfertig.com/blog/) — templates, embedded C++, tooling (cppinsights author). `cpp` `embedded`
- [Russ Cox](https://research.swtch.com/) — Go internals, regexes, version control, dist-sys classics. `go` `algorithms`

## Embedded / low-level

- [Memfault Interrupt](https://interrupt.memfault.com/) — THE embedded software blog: firmware, RTOS, debugging, Zephyr, ARM. `embedded`
- [Ken Shirriff — righto](https://www.righto.com/) — reverse-engineering silicon: die photos, ancient CPUs, power supplies. `embedded` `hardware`
- [Fabien Sanglard](https://fabiensanglard.net/) — code reviews of id Software engines, GPU history, game internals. `graphics` `cpp`

## Individuals — general software

- [Sam Rose (samwho)](https://samwho.dev/) — interactive visualizations of algorithms & data structures (bloom filters, memory allocators); recommended by Ben Dicken on stream. `algorithms` `viz`
- [Ben Dicken (benjdd)](https://benjdd.com/) — his own site: interactive posts like [memory access patterns & performance](https://benjdd.com/memory-access-patterns-and-performance/), MySQL on a Raspberry Pi. RSS available. `db` `perf`
- [Dan Luu](https://danluu.com/) — empirical takes on hardware, hiring, and craft; the best signal-per-post ratio on the internet. `perf` `culture`
- [Julia Evans (jvns)](https://jvns.ca/) — debugging, networking, Linux internals, made joyful. RSS + Wizard Zines. `linux` `debugging`
- [Eli Bendersky](https://eli.thegreenplace.net/) — compilers, C++, Go, math; prolific for a decade+. `cpp` `compilers`
- [Rachel by the Bay](https://rachelbythebay.org/w/) — SRE war stories and root-cause analyses; a debugging education. `sre` `debugging`
- [Aphyr (Kyle Kingsbury)](https://aphyr.com/) — Jepsen distributed-systems forensics; also the Reenscryption posts. `dist-sys`
- [Simon Willison](https://simonwillison.net/) — LLMs in practice, datasets, SQLite. The AI blog for engineers. `ai`
- [antirez (Salvatore Sanfilippo)](https://antirez.com/) — Redis creator on systems, C, language design. `systems` `c`
- [Armin Ronacher](https://lucumr.pocoo.org/) — Flask creator; Python, Rust, API design, engineering opinions. `python` `rust`
- [Raymond Chen — The Old New Thing](https://devblogs.microsoft.com/oldnewthing/) — Windows internals and API archaeology since 2003. Required reading for Win32. `win32`
- [Drew Devault](https://drewdevault.com/) — Sway/sr.ht author; C, compilers, free software culture. `c` `foss`
- [Michael Stapelberg](https://michael.stapelberg.ch/) — i3 author; Linux dist-sys internals (Debian, systemd-adjacent). `linux`
- [Phil Eaton](https://notes.eatonphil.com/) — builds databases/kernels for fun; superb "build your own X" writing. `systems` `db`
- [Martin Kleppmann](https://martin.kleppmann.com/) — DDIA author; data systems, CRDTs. `dist-sys` `data`
- [Matt Might](https://mattmight.net/) — CS theory made accessible (parsers, filters, grad-school lore). `algorithms`
- [James Hague — Programming in the 21st Century](https://prog21.dadgum.com/) — anti-complexity essays; Erlang-era wisdom. `culture`
- [Sean Goedecke](https://www.seangoedecke.com/) — Staff eng at GitHub; how big-company software actually gets built. `culture` `career`
- [Mitchell Hashimoto](https://mitchellh.com/writing/) — Ghostty/Vault/Terraform author; rare but deep posts on Zig, terminals, agents, and open-source craft (see "Ghostty is leaving GitHub"). `systems` `foss` *(via @bigboxSWE)*
- [Addy Osmani](https://addyosmani.com/blog/) — Chrome perf lead; AI-era software engineering, velocity, and hiring essays. `perf` `ai` *(via @bigboxSWE)*
- [The Pragmatic Engineer (Gergely Orosz)](https://blog.pragmaticengineer.com/) — the industry-insider blog/newsletter: Big Tech realities, hiring, salaries, 996-at-startups. `culture` `career` *(via @bigboxSWE)*

## AI / ML

- [Lilian Weng](https://lilianweng.github.io/) — long-form ML/AI surveys (agents, diffusion, hallucination). `ml`
- [Hugging Face Blog](https://huggingface.co/blog) — transformers internals, training tricks. `ml`
- [Google DeepMind](https://deepmind.google/discover/blog/) — frontier research, readable summaries. `ml`

## Security / reverse engineering

- [Brian Krebs — Krebs on Security](https://krebsonsecurity.com/) — cybercrime investigations; consistently HN's top blogger. `sec`
- [Troy Hunt](https://www.troyhunt.com/) — breaches, web security, Have I Been Pwned. `sec`
- [Bruce Schneier — Schneier on Security](https://www.schneier.com/) — security thinking beyond the bits. `sec`

## Unverified — to vet

*(inbox: add candidates here; promote after a skim)*
- Aria Beingessner — https://faultlore.com/ — Rust/WASM internals, byte-stream rants. Candidate for `rust`.
- Latacora blog — https://www.latacora.com/blog/ — security engineering essays. Candidate for `sec`.
- Regehr (John Regehr) — https://blog.regehr.org/ — compilers, UB, C++ correctness. Candidate for `compilers` `cpp`.
- Tipsy? / codebrowser-related… *(placeholder)*
