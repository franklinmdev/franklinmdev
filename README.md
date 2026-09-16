### Franklin Martinez

Software engineer in the Dominican Republic. I've spent the last three and a half years at Nubeteck building business software with TypeScript, React and .NET. Since February 2026 I work there as a Full-Stack AI Engineer, and outside of work I'm building LLM systems that get judged by benchmarks instead of demos.

[franklinmdev.me](https://franklinmdev.me) · [LinkedIn](https://www.linkedin.com/in/franklin-martinez-0a697a253/) · [franklinmdev@hotmail.com](mailto:franklinmdev@hotmail.com)

#### Projects

**[docmatch](https://github.com/franklinmdev/docmatch)**, Python, in progress

Invoice reconciliation for accounts payable. Vision models read the invoice, deterministic code checks the totals and matches it against the purchase order and the receiving record, and anything that doesn't add up goes to a person for review. Each extraction backend is scored on a fixed set of 100 labeled documents, and every row in the benchmark table links the commit that produced it. Right now Gemini 3.1 Flash-Lite reaches 0.615 field F1 at $0.002 per document, against 0.556 at $0.011 for Azure's prebuilt invoice model.

**[dgii-ts](https://github.com/franklinmdev/dgii-ts)**, TypeScript, [on npm](https://www.npmjs.com/package/dgii-ts)

Library for working with the DGII, the Dominican tax authority. It validates RNC, cédula, NCF and e-NCF numbers offline, and looks up taxpayers by scraping DGII's web pages with retries and a circuit breaker, because DGII has no public API and shut down its SOAP service in January 2025.

**[DomiProp](https://domiprop.com.do)**, TypeScript, private repo

Rental management for Dominican landlords: expense tracking, the monthly 606 purchase report, lease contracts under Ley 85-25, and reminders before tax deadlines. Next.js, NestJS, Prisma and PostgreSQL.

#### Tools

- **Product work:** TypeScript, React, Next.js, Node.js, NestJS, ASP.NET, PostgreSQL, SQL Server
- **AI work:** Python, Pydantic, pytest, Gemini API, Azure Document Intelligence, Claude Code and MCP

#### Recent courses

- Associate Python Developer, DataCamp, 2026
- query.gg and react.gg, ui.dev, 2025 and 2026
- The Ultimate Next.js 15 Course, JavaScript Mastery, 2025
