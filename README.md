### Hi, I'm Fajar

I build **[synt](https://synt.fun)** on my own from Yogyakarta, Indonesia. It is a trading terminal for new Solana pairs: every pair gets an audit score, and every score is published with its track record, so you can see how often pairs at that score collapsed before. You trade from the same screen, and your own wallet signs every transaction.

**What is public**

- [`munf/synt`](https://github.com/munf/synt): the web terminal (React, TypeScript), the account and trading service (Rust, axum, Postgres), and an MIT-licensed recorder for the BNB Chain launchpads four.meme and Flap (Rust, tokio).
- [`munf/synt-updates`](https://github.com/munf/synt-updates): changelog, release notes and docs.
- Live demo: [preview.synt.fun](https://preview.synt.fun)

The scoring engine stays private. The data layer, which is useful to other builders, is open.

**How I work**

I build with AI coding agents. I set the goal and the limits, a builder agent writes the change, a separate reviewer agent checks it, and I decide what ships. The same setup runs synt's daily operations, with spending caps and an approval queue.

**Before synt** I worked in AI data evaluation: search, ads and safety evaluation, preference ranking and review.

**Stack:** Rust · TypeScript · React · PostgreSQL · Solana · BNB Chain · Linux
