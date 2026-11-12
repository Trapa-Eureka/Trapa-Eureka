## Hi, I'm Jin (Jinho Son)

Full-stack developer in Philippines.(but from Korea. living with my family here.) 12 years of web development, including four and a half years on fintech products at Tenspace in Seoul. Since 2018 I have built and run my own products for the Philippine / Global market.

I pay the most attention to the parts that hurt users when they break: payments, payroll, access control and data that goes out of date. I build with Claude Code every day, and I review and test payment, auth and data-write code myself.

**Stack:** TypeScript · Next.js · React Native / Expo · PostgreSQL (Supabase, Neon, pgvector) · Cloudflare Workers · Python / Flask

---

### Production work (private repositories)

These products are or were live, so their code is private. Demos and read access are available on request.

- **Lite Payroll PH / Tax Assistant PH**: multi-tenant payroll and BIR tax-filing SaaS for small businesses. Payroll moves real money, so pay runs lock rows and each company's data is kept apart with Row Level Security. 7,087 tests run in CI before every deploy.
- **MeetingNote**: LLM meeting summarizer with Tagalog/Taglish speaker diarization. PayMongo can send the same payment webhook more than once, so each payment is matched to its checkout session and repeats are ignored. One payment always gives one period.
- **PHLaw**: hybrid search (pgvector + Typesense) over about 30,000 Philippine Supreme Court decisions and statutes. About 3,000 to 4,000 daily visitors during its run.
- **PH Fuel Watch**: a Cloudflare Workers cron job that reads the Department of Energy's weekly fuel-price PDFs with OCR and publishes prices for about 125 stations. Prices are marked as stale when the government data is late.

### Public repositories

- [retail-mcp](https://github.com/Trapa-Eureka/retail-mcp): sell-through and inventory BI MCP server for multi-store retail, with a reorder-suggestion agent
- [lang-ai-agent](https://github.com/Trapa-Eureka/lang-ai-agent): LangGraph agent backend with a streaming HTTP API
- [live-skill](https://github.com/Trapa-Eureka/live-skill): CLI that compiles PDF, DOCX and Markdown documents into verified Agent Skills
- [sheet_mcp](https://github.com/Trapa-Eureka/sheet_mcp): MCP server that sends notifications from a Google Sheet, for Philippine small businesses
- [SearchOps](https://github.com/Trapa-Eureka/SearchOps): Rails service that tracks search rankings and monitors API latency, errors and usage (a project for learning Ruby)
- [truck-route](https://github.com/Trapa-Eureka/truck-route): weather-aware truck routing (React + Django)

---

### Contact

[LinkedIn](https://www.linkedin.com/in/jinho-son-10a08167) · [Technical blog](https://trapa-eureka.github.io)

13(a) permanent resident in the Philippines. Open to remote or on-site work.
