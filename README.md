### Franklin Martinez

Software engineer in the Dominican Republic. I've spent the last three and a half years at Nubeteck building business software with TypeScript, React and .NET. Since February 2026 I work there as a Full-Stack AI Engineer, and outside of work I'm building LLM systems that get judged by benchmarks instead of demos.

[franklinmdev.me](https://franklinmdev.me) · [LinkedIn](https://www.linkedin.com/in/franklin-martinez-0a697a253/) · [franklinmdev@hotmail.com](mailto:franklinmdev@hotmail.com)

#### Projects

**[justask](https://github.com/franklinmdev/justask)**, TypeScript, [live demo](https://justask-demo.franklinmdev.workers.dev) · [on npm](https://www.npmjs.com/package/@justask/core)

Turns what a person types into an app's own state: search results, table filters, a filled record card. Code finds the candidates, a model picks one per question with a probability for every option, and a field it isn't sure of stays empty for the person to fill. Every change to how it asks goes through an eval round with rules fixed before the first call.

**[docmatch](https://github.com/franklinmdev/docmatch)**, Python, in progress

Invoice reconciliation for accounts payable. Vision models read the invoice, deterministic code checks the totals and matches it against the purchase order and the receiving record, and anything that doesn't add up goes to a person for review. Extraction, matching, entity resolution and the review pipeline are done, each with its number in a benchmark table that links the commit that produced it, and a CI gate fails any pull request that lowers F1. Right now Gemini 3.1 Flash-Lite reaches 0.615 field F1 at $0.002 per document, against 0.556 at $0.011 for Azure's prebuilt invoice model.

**[dgii-ts](https://github.com/franklinmdev/dgii-ts)**, TypeScript, [on npm](https://www.npmjs.com/package/dgii-ts)

Library for working with the DGII, the Dominican tax authority. It validates RNC, cédula, NCF and e-NCF numbers offline, and looks up taxpayers by scraping DGII's web pages with retries and a circuit breaker, because DGII has no public API and shut down its SOAP service in January 2025. It also ships an agent skill, so coding agents learn the library with `npx skills add franklinmdev/dgii-ts --skill dgii-ts`.

**[DomiProp](https://domiprop.com.do)**, TypeScript, private repo

Rental management for Dominican landlords: expense tracking, the monthly 606 purchase report, lease contracts under Ley 85-25, and reminders before tax deadlines. Next.js, NestJS, Prisma and PostgreSQL.

#### Tools

- **Product work:** TypeScript, React, Next.js, Node.js, NestJS, ASP.NET, PostgreSQL, SQL Server, Cloudflare Workers
- **AI work:** Python, Pydantic, pytest, Gemini API, Azure Document Intelligence, Claude Code and MCP

#### Recent courses

- Associate Python Developer, DataCamp, 2026
- query.gg and react.gg, ui.dev, 2025 and 2026
- The Ultimate Next.js 15 Course, JavaScript Mastery, 2025

#### Outside work

I run [Arkhelon](https://www.youtube.com/@arkhelon), a YouTube channel that tells the world's oldest stories: myths, monsters and legendary history. The production pipeline behind it is mine too, in Python and Remotion: every claim in a script links its source, every name the narrator says has a checked pronunciation, and each episode stops before it spends past its budget on paid models.
