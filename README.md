# tech-lore

A personal, opinionated index of **technical blogs, individual posts, and YouTube channels/videos** worth keeping around — biased toward systems, C++, performance, and embedded, but with room for everything good.

We don't try to be exhaustive. The exhaustive lists already exist (see Prior art). This repo is the *filtered* version: entries here earn their place by being genuinely good.

## Layout

| File | What goes in it |
|---|---|
| `blogs.md` | Blog *sites* — company engineering blogs + individual blogs |
| `posts.md` | Individual *posts/talks* worth re-reading — the canon |
| `papers.md` | Papers & books — the reading shelf (seeded from Ben Dicken's picks + canon) |
| `embedded-robotics.md` | The day-job shelf — firmware, RTOS, embedded Linux, hardware, robotics |
| `youtube.md` | Channels + specific must-watch videos |

## Entry format

```
- [Name](URL) — one-liner: what it covers and why it earns a spot. [tags]
```

- One line per entry. If the one-liner doesn't sell it, the entry isn't ready.
- Tag with topic(s): `cpp` `perf` `dist-sys` `embedded` `rust` `ai` `sec` `culture`
- RSS available? Note it — feeds feed the pipeline.

## Maintenance workflow

1. **Inbox → Unverified**: anything new goes into the `## Unverified — to vet` section of the relevant file.
2. **Vet**: read/skim the thing. Only promote entries that survive a skim. Delete ruthlessly — this is a repository of *interesting*, not *everything*.
3. **Promote**: move to the right section with a real one-liner.
4. **Yearly pass**: check for dead links and dead blogs (the graveyard is real — many company blogs move or die). `kilimchoi/engineering-blogs` does this at scale; we do it for our ~100 entries.
5. **OPML**: when `blogs.md` stabilizes, generate an OPML file for feed import (kilimchoi has a Ruby generator to copy from).

## Prior art (don't duplicate — mine)

Blog lists:
- [kilimchoi/engineering-blogs](https://github.com/kilimchoi/engineering-blogs) — the canonical list, 38.5k★. Companies + individuals + tech, with a 500+-feed `engineering_blogs.opml`.
- [ashishps1/awesome-engineering-articles](https://github.com/ashishps1/awesome-engineering-articles) — 300+ *individual articles* from top companies, topic-tagged. Closest to our `posts.md`.
- [crispgm/awesome-engineering-blogs](https://github.com/crispgm/awesome-engineering-blogs) — 300★, cleaner/smaller.
- [upgundecha/awesome-engineering](https://github.com/upgundecha/awesome-engineering) — blogs + handbooks + OSS repos per company.
- [sumodirjo/engineering-blogs](https://github.com/sumodirjo/engineering-blogs) — startups + enterprise.
- [penberg/awesome-low-latency](https://github.com/penberg/awesome-low-latency) — 1.3k★, patterns + papers + blogs for low latency. Core for our perf section.
- [tuan3w/awesome-tech-rss](https://github.com/tuan3w/awesome-tech-rss) — RSS-first.

YouTube lists:

Domain-specific (embedded & robotics):
- [nhivp/Awesome-Embedded](https://github.com/nhivp/Awesome-Embedded) · [embedded-boston/awesome-embedded-systems](https://github.com/embedded-boston/awesome-embedded-systems) · [fkromer/awesome-embedded-linux](https://github.com/fkromer/awesome-embedded-linux) · [rust-embedded/awesome-embedded-rust](https://github.com/rust-embedded/awesome-embedded-rust)
- [ahundt/awesome-robotics](https://github.com/ahundt/awesome-robotics) · [Tinker-Twins/Robotics-Resources](https://github.com/Tinker-Twins/Robotics-Resources) · [natnew/awesome-physical-ai](https://github.com/natnew/awesome-physical-ai)

General YouTube lists:
- [JoseDeFreitas/awesome-youtubers](https://github.com/JoseDeFreitas/awesome-youtubers) — tech teaching channels, playlist-level detail.
- [ErikCH/DevYouTubeList](https://github.com/ErikCH/DevYouTubeList) — huge, dev channels by language/topic.
- [epoyraz/Awesome-Youtube-Channels](https://github.com/epoyraz/Awesome-Youtube-Channels) — language/conference channels (CppCon, Meeting C++, CCC…).
- [PrejudiceNeutrino/YouTube_Channels](https://github.com/PrejudiceNeutrino/YouTube_Channels) — broad CS/eng/electronics channel index.
- [lucasviola/awesome-tech-videos](https://github.com/lucasviola/awesome-tech-videos) — individual talks/videos.
