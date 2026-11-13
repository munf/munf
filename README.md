### Hi, I'm Fajar

I build early-warning systems from Yogyakarta, Indonesia: tools that tell people what is likely to go wrong before they lose something, and that publish how often they are wrong.

**[synt](https://synt.fun): risk scores for brand-new tokens**

Every new Solana pair gets an audit score within minutes of launch, and every score is published with its track record, so you can see how often pairs at that score collapsed before. You trade from the same screen, and your own wallet signs every transaction.

- [`munf/synt`](https://github.com/munf/synt): the web terminal (React, TypeScript), the account and trading service (Rust, axum, Postgres), and an MIT-licensed recorder for the BNB Chain launchpads four.meme and Flap (Rust, tokio).
- [`munf/synt-updates`](https://github.com/munf/synt-updates): changelog, release notes and docs.
- Live demo: [preview.synt.fun](https://preview.synt.fun)

The scoring engine stays private. The data layer, which is useful to other builders, is open.

**[Synteel](https://eel.synt.fun): night alarms for eel farmers**

Indonesian eel farming depends on wild-caught glass eels, and many die in the first weeks, often at night when oxygen drops and nobody is awake. Synteel, which I co-founded with a CTO, forecasts tonight's oxygen risk and rings an alarm at the riskiest hour, turns voice and photo notes in the farmer's own language into pond records, and counts dead eels from one photo. Fixed safety rules keep the alarm working with no internet and no AI.

- [`munf/synteel-app`](https://github.com/munf/synteel-app): the farmer app (Preact, TypeScript, Hono, Node), live at [eel.synt.fun](https://eel.synt.fun).
- Next: a pond sensor kit and a small recirculating nursery with backup oxygen, tested pond against pond at a partner farm this season.

**How I work**

I build with AI coding agents. I set the goal and the limits, a builder agent writes the change, a separate reviewer agent checks it, and I decide what ships. The same setup runs daily operations for both projects, with spending caps and an approval queue.

**Before this** I studied law and worked in AI data evaluation: search, ads and safety evaluation, preference ranking and review. Grading model outputs taught me how these systems fail, which is why both projects keep a fixed safety net under the AI.

**Stack:** Rust · TypeScript · React · Preact · Node · PostgreSQL · SQLite · Solana · BNB Chain · Linux
