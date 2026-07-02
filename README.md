## Hey, i'm Mayank 

3rd year CS undergrad at MAIT, Delhi. I like building backend systems.

Mostly work with **Java + Spring Boot**, and I've been going deeper into **design**, **security** and **architecture** of distributed systems, database internals, and recently post-quantum cryptography (because apparently RSA won't survive forever).

Currently looking for **SDE internships** where I can work on real infrastructure problems.

---

### Proof of work — open source contributions

I contribute to a few established Java projects. These are merged PRs, not drive-by typo fixes:

**traccar/traccar** (7.5k ★) — GPS tracking platform
- `merged` Implemented user email attribution in audit logs; batch fetching to fix N+1 query overhead. — [#5719](https://github.com/traccar/traccar/pull/5719)

**JabRef/jabref** (4.3k ★) — reference manager
- `merged` Fixed linked-file substring search bugs by preserving wildcard chars; refactored web labels to standardized i18n keys. — [#14561](https://github.com/JabRef/jabref/pull/14561)

**ical4j/ical4j** (1k ★) — iCalendar parsing library
- `open` Fixed yearly recurrence generation breaking when DTSTART is in UTC format. — [#893](https://github.com/ical4j/ical4j/pull/893)
- `merged` Fixed UTC offset bug in Period.toInterval for OffsetDateTime. — [#882](https://github.com/ical4j/ical4j/pull/882)
- `open` Added TEXT_VALUE handling for String parameters in StructuredData. — [#898](https://github.com/ical4j/ical4j/pull/898)

**CodeVoyager3/MediChain** — hackathon team project (CodeVeda 2.0, 3rd place at ThoughtWorks)
- `merged` Built blockchain service: minting, access granting, and insurer verification endpoints. — [#1](https://github.com/CodeVoyager3/MediChain/pull/1)
- `merged` Implemented PostgreSQL caching layer, QR waiting room logic, and dashboard endpoints. — [#2](https://github.com/CodeVoyager3/MediChain/pull/2)
---

### Things I've built

**[CoreLedgerEngine](https://github.com/mayank1008-tech/CoreLedgerEngine)** — a financial banking ledger with double-entry bookkeeping, SHA-256 hash chain for tamper detection, Redis backed rate limiting across Nginx load balanced instances, and optimistic locking for concurrent transfers. 90% test coverage with JUnit5/Mockito. Dockerized with CI/CD via GitHub Actions.
`Java · Spring Boot 3 · PostgreSQL · Redis · Docker · Nginx`

**[CryptoRatchet](https://github.com/mayank1008-tech/CryptoRatchet)** — simulated a Harvest Now, Decrypt Later attack over a 3-node TCP topology. Migrated a live session from RSA to ML-KEM-768 mid stream using AtomicReference hot swap without dropping connections or hitting race conditions.
`Java · ML-KEM-768 (Kyber) · HKDF · Raw TCP sockets · Concurrency`

**[MediChain](https://github.com/CodeVoyager3/MediChain)** — zero-trust healthcare platform built at CodeVeda 2.0 hackathon (placed 3rd at ThoughtWorks, Gurugram). I built the backend + blockchain architecture end-to-end: Web3 wallet auth, Solidity access control on Polygon Amoy, three layer fraud verification engine (rule based + Gemini AI + blockchain audit).
`Java · Spring Boot · Solidity · Polygon · IPFS · React`

---

### Competitive programming

Not world class, but I grind consistently😁:

- **[LeetCode](https://leetcode.com/u/mank_1008/)** — 1637 rating, 375+ problems solved
- **Codeforces** — Pupil (1233)

---

### Tech I use regularly

```
languages       java, python, c++, sql
backend         spring boot 3, spring security, spring data jpa, REST APIs
databases       postgresql, redis, mysql
infra/tools     docker, nginx, github actions, maven, git, linux
testing         junit5, mockito
exploring       system design, distributed systems, security, architecture
```

---

### find me

- **email** — mj.mayank98@gmail.com
- **linkedin** — [mayank-jain-78a6b6321](https://linkedin.com/in/mayank-jain-78a6b6321)
