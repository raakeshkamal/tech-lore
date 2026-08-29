# Papers & Books — the reading shelf

Seed sources: Ben Dicken's stream ["My favorite database papers"](https://www.youtube.com/watch?v=JQCUE1rTsIk) + his Database Internals book club + the HN canon. Papers are where blogs steal their ideas from; read the originals at least once.

## Books

- [Systems Performance — Brendan Gregg](https://www.brendangregg.com/sysperfbook.html) — THE systems performance book; Ben Dicken's "Make computers FAST" series is literally a walkthrough of chapter 1. `perf` `linux`
- [Designing Data-Intensive Applications — Martin Kleppmann](https://dataintensive.net/) — the modern dist-sys/database bible; Ben did a read-along of ch. 1–2. `dist-sys` `db`
- [Database Internals — Alex Petrov](https://www.databass.dev/) — deep dive into storage engines + distributed databases; Ben Dicken's book club reads this one cover to cover. `db` `storage`
- [The Art of Computer Systems Performance Analysis — Raj Jain](https://www.rajjain.com/) — how to benchmark honestly; the statistics behind perf work. `perf` *(canon; heavy)*

## Distributed systems & consensus papers

- [The Log: ...real-time data's unifying abstraction — Jay Kreps (2011)](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying) — also in posts.md; the on-ramp paper. `dist-sys`
- [Raft: In Search of an Understandable Consensus Algorithm — Ongaro & Ousterhout (2014)](https://raft.github.io/raft.pdf) — "the ICONIC consensus algorithm" (Ben's words); readability was the design goal. `dist-sys`
- [Paxos Made Live — Burrows (Google, 2006)](https://static.googleusercontent.com/media/research.google.com/en//archive/paxos_made_live.pdf) — theory vs production reality; the reason Raft exists. `dist-sys`
- [Dynamo — DeCandia et al. (Amazon, SOSP 2007)](https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf) — eventually-consistent KV stores; behind every "DynamoDB" is this paper. `dist-sys`
- [Bigtable — Chang et al. (Google, OSDI 2006)](https://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf) — wide-column store; LSM-lineage ancestor. `storage`
- [The Google File System — Ghemawat et al. (SOSP 2003)](https://static.googleusercontent.com/media/research.google.com/en//archive/gfs-sosp2003.pdf) — component failures are the norm, not the exception. `dist-sys`
- [MapReduce — Dean & Ghemawat (OSDI 2004)](https://static.googleusercontent.com/media/research.google.com/en//archive/mapreduce-osdi04.pdf) — the compute-on-data pattern that started a decade. `dist-sys`
- [Spanner — Corbett et al. (Google, OSDI 2012)](https://static.googleusercontent.com/media/research.google.com/en//archive/spanner-osdi2012.pdf) — globally consistent with TrueTime; the CAP-discipline proof. `dist-sys` `db`
- [Amazon Aurora: Design Considerations (SIGMOD 2017)](https://www.allthingsdistributed.com/files/p1041-verbitski.pdf) — "the log is the database." `db` `storage`
- [FoundationDB — Zhou et al. (SIGMOD 2021)](https://www.foundationdb.org/files/fdb-paper.pdf) — simulation-tested distributed DB; a testing-culture landmark. `dist-sys` `testing`
- [Calvin: Fast Distributed Transactions (SIGMOD 2012)](http://cs-www.cs.yale.edu/homes/dna/papers/calvin-sigmod12.pdf) — deterministic transactions; the FaunaDB lineage. `dist-sys` `db`

## Databases / storage engines papers

- [Architecture of a Database System — Hellerstein, Stonebraker, Hamilton (2007)](https://dsf.berkeley.edu/papers/fntdb07-architecture.pdf) — the anatomy map of every RDBMS; read before any internals book. `db`
- [Access Path Selection in a Relational DBMS — Selinger et al. (IBM, 1979)](https://www.eecs.harvard.edu/~mdb/cs265/papers/selinger-79.pdf) — cost-based query optimization is born here. `db`
- [OLTP Through the Looking Glass — Stonebraker et al. (SIGMOD 2008)](https://dsf.berkeley.edu/papers/sigmod08-lookingglass.pdf) — H-Store; "the DBMS is 90% overhead for OLTP." `db` `perf`
- [The Five-Minute Rule — Gray & Putzolu (1987)](https://www.hpl.hp.com/techreports/tandem/TR-86.1.pdf) — memory vs disk economics; still the right way to think about caching. `perf` `storage`
- [Life Beyond Distributed Transactions — Helland (CIDR 2007)](https://www.ics.uci.edu/~cs223/papers/cidr07p5.pdf) — activities and entities; the sanest answer to "how do I scale without 2PC." `dist-sys`
- [Harvest, Yield, and Scalable Tolerant Systems — Brewer (2000)](https://people.eecs.berkeley.edu/~brewer/cs262b/harvest-yield.pdf) — the nuanced CAP thinking behind "please stop calling databases CP or AP." `dist-sys`

## Performance / networking papers & essays

- [The Tail at Scale — Dean & Barroso (CACM 2013)](https://research.google/pubs/the-tail-at-scale/) — also in posts.md; p99 thinking. `perf` `dist-sys`
- [End-to-End Arguments in System Design — Saltzer, Reed, Clark (1984)](https://web.mit.edu/Saltzer/www/publications/endtoend/endtoend.pdf) — where to put the smarts; 40 years of system-design fights settled by this. `systems`
- [How flat is replacing fat in AWS data center networks — Amazon Science (2025)](https://www.amazon.science/blog/how-flat-is-replacing-fat-in-aws-data-center-networks) — quasi-random (RNG) physical network topology; 69% fewer routers, resilient to link failures. Blog + arXiv paper. `net` `perf`
- [Out of the Tar Pit — Moseley & Marks (2006)](https://curtclifton.net/papers/MoseleyMarks06a.pdf) — accidental vs essential complexity; the most-referenced unread paper in software. `design` `culture`
- [How to Read a Paper — Keshav (SIGCOMM CCR 2007)](http://ccr.sigcomm.org/online/files/p83-keshavA.pdf) — the three-pass method; makes this whole shelf tractable. `meta`

## Ben Dicken's picks (from "My favorite database papers" stream)

The on-screen list is in the stream itself (JQCUE1rTsIk); the ones captured above that he leaned on: **Raft/Paxos, The Log, LSM/LevelDB lineage, Spanner, Dynamo, Aurora-style log-as-database, OpenAI's Postgres scaling story**. Re-watch and pull the remaining screen titles → move them up into the sections above.

## Unverified — to vet

*(inbox)*
- Megastore, Percolator, F1 — the Google trio; find clean PDF links before canonizing.
- Socrates: The New SQL Server in the Cloud (SIGMOD 2019).
- H-Store / Hekaton — main-memory engine papers.
- "The Part-Time Parliament" — historical completeness only.
- Stonebraker's "One Size Fits All" (CIDR 2005) — the column-store manifesto.
- USENIX OSDI/SOSP best-paper playlists — an annual mining ritual.
