# Mehmet Fatih Doğan

Backend-focused developer building web and mobile products end to end: API and data model design, authentication and access control, offline-first clients that sync with a server, and the Docker deployments they run on.

Most of my current work is in **TypeScript** (Node.js, NestJS, Next.js, React) with **PostgreSQL** or **SQLite**. I have also shipped mobile clients with Capacitor and Flutter, and earlier projects in Python/Django and C#/ASP.NET Core.

[Portfolio](https://mehmetfatihdogan.com.tr/en/projects) · [Project catalog](https://github.com/users/fatihdogann/projects/2) · [Contact](https://mehmetfatihdogan.com.tr/en/contact)

## Products

Each product links to the live app and a technical showcase covering features, stack and architecture.

- **[TaskWork](https://taskwork.mehmetfatihdogan.com.tr)** — Tasks, calendar and habits that keep working offline on web, iOS and Android. One React/TypeScript core is packaged for mobile with Capacitor; optional account sync runs on Supabase Auth with PostgreSQL access policies. · [Showcase](https://github.com/fatihdogann/taskwork-showcase)
- **[Gridpen](https://gridpen.mehmetfatihdogan.com.tr)** — Tables, formulas, charts and notes on one canvas, where editing a table updates its linked chart. Documents are Yjs CRDTs stored in IndexedDB and optionally synced through a Node.js/Hono API; formulas run on a custom Excel-syntax engine. · [Showcase](https://github.com/fatihdogann/gridpen-showcase)
- **[Readflow](https://readflow.mehmetfatihdogan.com.tr)** — Local-first archive for links, text and PDFs with highlights, full-text search and summaries from your own coding-agent CLI, so no LLM API key is needed. Built on Next.js and SQLite (FTS5); a local worker and an MCP server share one job queue with ownership leases. · [Source](https://github.com/fatihdogann/readflow)
- **[Trader Defteri & Defter Terminal](https://defter.mehmetfatihdogan.com.tr)** — A trade journal with risk and discipline tracking, and a separate workspace for market data and backtesting. A Node.js/Express and PostgreSQL API serves the web and Flutter clients; the Next.js terminal runs as its own service and reads journal summaries without writing to them. · [Showcase](https://github.com/fatihdogann/trader-defteri-showcase)
- **[Kalite](https://kalite.mehmetfatihdogan.com.tr)** — Accreditation reports (MÜDEK/FEDEK) that trace program outcomes back to assessment evidence. NestJS, Prisma and PostgreSQL with reproducible calculations, Argon2id sessions and PDF/Excel evidence packages. · [Showcase](https://github.com/fatihdogann/kalite-showcase)

## Open-source tools

- **[RestoreLab](https://github.com/fatihdogann/restorelab)** — Checks whether a PostgreSQL backup actually brings an application back: it restores the backup in Docker and runs application checks separately from the restore. In the sample, both restores succeed but only one passes the access check. · [Sample report](https://mehmetfatihdogan.com.tr/assets/demos/restorelab-en)
- **[EMA Ses](https://github.com/fatihdogann/ema-ses)** — Turkish text-to-speech for macOS that works offline after setup; listen at adjustable speed and save the result as WAV. · [Screenshot](https://github.com/fatihdogann/ema-ses/blob/main/docs/ekran.png)
- **[turkce-utils](https://github.com/fatihdogann/turkce-utils)** — Turkish-aware casing, sorting, slugs and readability scores as a zero-dependency TypeScript library and CLI. · [npm](https://www.npmjs.com/package/turkce-utils)
- **[turkce-tarih](https://github.com/fatihdogann/turkce-tarih)** — Parses Turkish date expressions such as “yarın akşam 7’de” in TypeScript or from the terminal, with no dependencies. · [npm](https://www.npmjs.com/package/turkce-tarih)

## Earlier projects

The [earlier projects view](https://github.com/users/fatihdogann/projects/2/views/3) collects my first web and desktop apps, including the [Time–Money Planner](https://github.com/fatihdogann/zaman-para-planlayici) and [Contact App](https://github.com/fatihdogann/contact-app#ekran-g%C3%B6r%C3%BCnt%C3%BCleri).
