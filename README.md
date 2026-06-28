<div align="center">

```
  █████╗ ██╗    ██╗███████╗███████╗ ██████╗ ███╗   ███╗███████╗
 ██╔══██╗██║    ██║██╔════╝██╔════╝██╔═══██╗████╗ ████║██╔════╝
 ███████║██║ █╗ ██║█████╗  ███████╗██║   ██║██╔████╔██║█████╗  
 ██╔══██║██║███╗██║██╔══╝  ╚════██║██║   ██║██║╚██╔╝██║██╔══╝  
 ██║  ██║╚███╔███╔╝███████╗███████║╚██████╔╝██║ ╚═╝ ██║███████╗
 ╚═╝  ╚═╝ ╚══╝╚══╝╚══════╝╚══════╝ ╚═════╝ ╚═╝     ╚═╝╚══════╝

 ███╗   ███╗ ██████╗██████╗     ███████╗███████╗██████╗ ██╗   ██╗███████╗██████╗ ███████╗
 ████╗ ████║██╔════╝██╔══██╗    ██╔════╝██╔════╝██╔══██╗██║   ██║██╔════╝██╔══██╗██╔════╝
 ██╔████╔██║██║     ██████╔╝    ███████╗█████╗  ██████╔╝██║   ██║█████╗  ██████╔╝███████╗
 ██║╚██╔╝██║██║     ██╔═══╝     ╚════██║██╔══╝  ██╔══██╗╚██╗ ██╔╝██╔══╝  ██╔══██╗╚════██║
 ██║ ╚═╝ ██║╚██████╗██║         ███████║███████╗██║  ██║ ╚████╔╝ ███████╗██║  ██║███████║
 ╚═╝     ╚═╝ ╚═════╝╚═╝         ╚══════╝╚══════╝╚═╝  ╚═╝  ╚═══╝ ╚══════╝╚═╝  ╚═╝╚══════╝
```

**A curated universe of Model Context Protocol servers**  
*Supercharging AI assistants with real-world capabilities*

<br/>

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![License: CC0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
![MCP Servers](https://img.shields.io/badge/MCP_Servers-100%2B-blueviolet)
![Stars](https://img.shields.io/github/stars/punkpeye/awesome-mcp-servers?style=social)

<br/>

> **Model Context Protocol (MCP)** is an open standard that enables AI models to securely connect  
> with local and remote resources through a unified interface. These servers extend AI capabilities  
> with tools, data access, and real-world integrations.  
> [→ Official Spec & SDKs](https://github.com/modelcontextprotocol) · [→ MCP Documentation](https://modelcontextprotocol.io)

<br/>

[🏆 Top Picks](#-top-picks) · [🌐 Browse All](#-browse-all-servers) · [📦 Categories](#-categories) · [🚀 Getting Started](#-getting-started) · [🤝 Contributing](#-contributing)

</div>

---

## 🏆 Top Picks

> Hand-selected by the community — the most powerful, polished, and production-ready MCP servers available today.

<br/>

<table>
<tr>
<td width="50%" valign="top">

### 🥇 #1 · Filesystem MCP
**Secure, Official File System Access**

![Official](https://img.shields.io/badge/Official_Anthropic-blue?style=flat-square)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Most Downloaded](https://img.shields.io/badge/Most_Downloaded-brightgreen?style=flat-square)

The gold standard for file operations. Read, write, search, move, and manage files with surgical precision. Built and maintained by Anthropic — the most battle-tested MCP server in the ecosystem. The first server most users install.

**Highlights:** Directory traversal · Smart search · Safe write guards · Configurable root paths · Symlink support

```bash
npx -y @modelcontextprotocol/server-filesystem ~/Documents
```

[🔗 Repository](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem)

</td>
<td width="50%" valign="top">

### 🥈 #2 · GitHub MCP
**Official GitHub — Now by GitHub**

![Official](https://img.shields.io/badge/Official_GitHub-black?style=flat-square&logo=github)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Remote Available](https://img.shields.io/badge/Remote_MCP-available-purple?style=flat-square)

The go-to server for developers. GitHub rewrote and officially maintains this server in Go. Supports remote and local modes, OAuth 2.1, GitHub Projects, code scanning, CI/CD, and more. Works with VS Code, Cursor, JetBrains, and Claude Desktop.

**Highlights:** Issues & PRs · Code search · GitHub Projects · Actions · OAuth 2.1 · Remote endpoint

```bash
npx @modelcontextprotocol/server-github
```

[🔗 Repository](https://github.com/github/github-mcp-server)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🥉 #3 · MCP360
**Rising Star — All-in-One Server**

![Rising Star](https://img.shields.io/badge/Rising_Star-FFB800?style=flat-square)
![All-in-One](https://img.shields.io/badge/All--in--One-blueviolet?style=flat-square)

A single server bundling web search, file management, code execution, database access, and API integrations. A great pick if you want to reduce the number of individual servers to configure. Modular — enable only what you need.

**Highlights:** Modular toggles · Multi-model support · Single install

```bash
npx -y @mcp360/universal-gateway
```

[🔗 Repository](https://github.com/mcp360/unified-gateway-mcp)

</td>
<td width="50%" valign="top">

### 🏅 #4 · Memory MCP
**Persistent AI Memory**

![Official](https://img.shields.io/badge/Official_Anthropic-blue?style=flat-square)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

Give your AI a brain that persists across sessions. Knowledge graph storage lets Claude remember facts, entities, and relationships between conversations. Essential for any long-running workflow.

**Highlights:** Knowledge graphs · Entity relations · Cross-session recall · Fast retrieval

```bash
npx -y @modelcontextprotocol/server-memory
```

[🔗 Repository](https://github.com/modelcontextprotocol/servers/tree/main/src/memory)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏅 #5 · Firecrawl MCP
**Web Scraping & Deep Research**

![Official](https://img.shields.io/badge/Official_Firecrawl-orange?style=flat-square)
![API Key](https://img.shields.io/badge/Requires_API_Key-yellow?style=flat-square)

Turn any website into clean, LLM-ready Markdown. Handles JavaScript-heavy pages, anti-bot barriers, and dynamic content. One of the most-used community MCP servers in 2025.

**Highlights:** Scrape · Crawl · Deep research · Batch scraping · Structured extraction

```bash
npx -y firecrawl-mcp
```

[🔗 Repository](https://github.com/firecrawl/firecrawl-mcp-server)

</td>
<td width="50%" valign="top">

### 🏅 #6 · Supabase MCP
**Postgres + Auth + Storage**

![Official](https://img.shields.io/badge/Official_Supabase-3ECF8E?style=flat-square)
![Remote](https://img.shields.io/badge/Remote_MCP-available-purple?style=flat-square)

Official Supabase server covering database queries, schema migrations, Edge Functions, Auth, and Storage. OAuth-based authentication — no personal access token required.

**Highlights:** SQL queries · Schema management · Edge Functions · Auth Admin

```bash
npx -y @supabase/mcp-server-supabase
```

[🔗 Repository](https://github.com/supabase-community/supabase-mcp) · [📖 Docs](https://supabase.com/docs/guides/getting-started/mcp)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏅 #7 · Notion MCP
**Official Notion Workspace**

![Official](https://img.shields.io/badge/Official_Notion-black?style=flat-square)
![Remote](https://img.shields.io/badge/Remote_MCP-available-purple?style=flat-square)

Official server from Notion for reading and writing pages, databases, and blocks. Supports both local stdio and remote hosted transport modes. Great for teams using Notion as their knowledge base.

**Highlights:** Pages · Databases · Blocks · Search · Remote transport

```bash
npx @notionhq/notion-mcp-server
```

[🔗 Repository](https://github.com/makenotion/notion-mcp-server)

</td>
<td width="50%" valign="top">

### 🏅 #8 · Cloudflare MCP
**Official Cloudflare — Full API Access**

![Official](https://img.shields.io/badge/Official_Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Remote](https://img.shields.io/badge/Remote_MCP-available-purple?style=flat-square)

Official Cloudflare server covering Workers, KV, R2, D1, DNS, Pages, and more. Also available as a hosted remote server — just paste the URL and authorize with OAuth.

**Highlights:** Workers · R2 · KV · D1 · DNS · 2500+ API endpoints · Remote at `mcp.cloudflare.com`

```bash
# Remote — no install needed
# Add https://mcp.cloudflare.com/mcp to your MCP client
```

[🔗 Repository](https://github.com/cloudflare/mcp-server-cloudflare) · [🌐 Remote](https://mcp.cloudflare.com/mcp)

</td>
</tr>
</table>

---

## 📦 Categories

| 🗂️ | Category | Count |
|---|----------|-------|
| 🌐 | [Web & Search](#-web--search) | 12 |
| 💾 | [Databases & Storage](#-databases--storage) | 11 |
| 🗃️ | [File Systems](#-file-systems) | 7 |
| 🔧 | [Developer Tools](#-developer-tools) | 14 |
| 📡 | [APIs & Integrations](#-apis--integrations) | 13 |
| 🧠 | [AI & Memory](#-ai--memory) | 8 |
| 📊 | [Data & Analytics](#-data--analytics) | 9 |
| 🖥️ | [OS & System](#-os--system) | 7 |
| 💬 | [Communication & Productivity](#-communication--productivity) | 12 |
| 🎨 | [Media & Creative](#-media--creative) | 6 |
| ☁️ | [Cloud & DevOps](#-cloud--devops) | 9 |

---

## 🌐 Browse All Servers

---

### 🌐 Web & Search

> Bring the live web into your AI context

| Server | Description | Language |
|--------|-------------|----------|
| [**Fetch**](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch) | Fetch any webpage and convert to Markdown — official Anthropic server | TypeScript |
| [**Firecrawl**](https://github.com/firecrawl/firecrawl-mcp-server) | Scrape, crawl, and research the web; handles JS-heavy pages | TypeScript |
| [**Playwright MCP**](https://github.com/microsoft/playwright-mcp) | Microsoft's official Playwright browser automation for MCP | TypeScript |
| [**Puppeteer**](https://github.com/modelcontextprotocol/servers/tree/main/src/puppeteer) | Headless browser control — screenshots, forms, PDF generation | TypeScript |
| [**Tavily Search**](https://github.com/tavily-ai/tavily-mcp) | AI-optimized search with clean answer synthesis | TypeScript |
| [**Exa Search**](https://github.com/exa-labs/exa-mcp-server) | Neural search engine for semantic and keyword web results | TypeScript |
| [**Perplexity MCP**](https://github.com/ppl-ai/modelcontextprotocol) | Perplexity AI search with inline citations | Python |
| [**Kagi Search**](https://github.com/kagisearch/mcp) | Premium ad-free web search via Kagi API | TypeScript |
| [**SearXNG**](https://github.com/ihor-sokoliuk/mcp-searxng) | Self-hosted privacy meta-search engine | Python |
| [**Linkup MCP**](https://github.com/LinkupPlatform/python-mcp-server) | Real-time premium web search with source citations | Python |
| [**Spider MCP**](https://github.com/spider-rs/spider-mcp) | Fast, scalable web crawling and scraping | Rust/TypeScript |
| [**Wayback Machine**](https://github.com/AshDevFr/mcp-wayback-machine) | Search and retrieve archived web pages from the Internet Archive | Python |

> ⚠️ **Note:** The original Brave Search server (`modelcontextprotocol/servers`) is now **archived**. Use one of the above alternatives or the [Brave Search API](https://brave.com/search/api/) directly.

---

### 💾 Databases & Storage

> Natural language querying for any database

| Server | Description | Language |
|--------|-------------|----------|
| [**PostgreSQL**](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres) | Read-only PostgreSQL with schema introspection — official Anthropic | TypeScript |
| [**SQLite**](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite) | Lightweight SQL database operations — official Anthropic | Python |
| [**Supabase MCP**](https://github.com/supabase-community/supabase-mcp) | Official Supabase — DB, Auth, Storage, Edge Functions, OAuth | TypeScript |
| [**MongoDB MCP**](https://github.com/mongodb-js/mongodb-mcp-server) | Official MongoDB server — queries, aggregations, schema discovery | TypeScript |
| [**Redis MCP**](https://github.com/redis/mcp-redis) | Official Redis — get, set, search, stream operations | TypeScript |
| [**MySQL MCP**](https://github.com/benborla/mcp-server-mysql) | Full MySQL database access and management | PHP |
| [**Neon MCP**](https://github.com/neondatabase/mcp-server-neon) | Official Neon serverless Postgres — branch, query, migrate | TypeScript |
| [**PlanetScale MCP**](https://github.com/planetscale/database-js) | PlanetScale serverless MySQL platform | TypeScript |
| [**Turso MCP**](https://github.com/tursodatabase/turso-mcp) | Turso edge SQLite database management | TypeScript |
| [**Qdrant MCP**](https://github.com/qdrant/mcp-server-qdrant) | Vector search and semantic memory with Qdrant | Python |
| [**BigQuery MCP**](https://github.com/LucasHild/mcp-server-bigquery) | Google BigQuery data warehouse queries | Python |

---

### 🗃️ File Systems

> Intelligent file and document management

| Server | Description | Language |
|--------|-------------|----------|
| [**Filesystem**](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem) | Secure file read/write/search — official Anthropic | TypeScript |
| [**Google Drive**](https://github.com/modelcontextprotocol/servers/tree/main/src/gdrive) | Read, search, and manage Google Drive files — official Anthropic | TypeScript |
| [**S3 MCP**](https://github.com/aws-samples/mcp-server-s3) | AWS S3 bucket read/write operations | Python |
| [**Box MCP**](https://github.com/box/box-mcp-server) | Official Box cloud storage integration | TypeScript |
| [**PDF Reader MCP**](https://github.com/sylphlab/pdf-reader-mcp) | Extract text and metadata from PDF files | TypeScript |
| [**Office Docs MCP**](https://github.com/mark3labs/mcp-filesystem-server) | Read Word, Excel, and PowerPoint documents | Go |
| [**ZIP Tools**](https://github.com/QuantGeekDev/mcp-zip-tools) | Create and extract ZIP archives | TypeScript |

---

### 🔧 Developer Tools

> The AI-powered developer workbench

| Server | Description | Language |
|--------|-------------|----------|
| [**GitHub MCP**](https://github.com/github/github-mcp-server) | Official GitHub server — issues, PRs, code search, Projects, Actions | Go |
| [**Git MCP**](https://github.com/modelcontextprotocol/servers/tree/main/src/git) | Local Git repo history, diffs, commits — official Anthropic | Python |
| [**MCP360**](https://github.com/mcp360/unified-gateway-mcp) | All-in-one MCP server bundling web search, file management, code execution, database access, and API integrations | TypeScript |
| [**Atlassian MCP**](https://github.com/sooperset/mcp-atlassian) | Jira and Confluence — issues, pages, sprints | Python |
| [**Linear MCP**](https://github.com/linear/linear-mcp) | Official Linear issue tracking and project management | TypeScript |
| [**Sentry MCP**](https://github.com/getsentry/sentry-mcp) | Official Sentry — error tracking, issues, remote endpoint | Python |
| [**Docker MCP**](https://github.com/ckreiling/mcp-server-docker) | Manage containers, images, and Docker volumes | Python |
| [**Kubernetes MCP**](https://github.com/strowk/mcp-k8s-go) | K8s cluster management and pod operations | Go |
| [**Terraform MCP**](https://github.com/hashicorp/terraform-mcp-server) | Official HashiCorp Terraform registry access | Go |
| [**Vercel MCP**](https://github.com/vercel/mcp-adapter) | Official Vercel — deployments, domains, logs | TypeScript |
| [**NPM MCP**](https://github.com/jlowin/mcp-npm) | Search and inspect npm package metadata | TypeScript |
| [**Context7**](https://github.com/upstash/context7) | Up-to-date library docs and code examples directly in context | TypeScript |
| [**CodeSandbox MCP**](https://github.com/codesandbox/mcp-server) | Create and manage cloud dev environments | TypeScript |
| [**CircleCI MCP**](https://github.com/CircleCI-Public/mcp-server-circleci) | Official CircleCI CI/CD pipeline management | TypeScript |
| [**Netlify MCP**](https://github.com/netlify/netlify-mcp) | Official Netlify site deployment and management | TypeScript |

---

### 📡 APIs & Integrations

> Connect AI to every service you use

| Server | Description | Language |
|--------|-------------|----------|
| [**Stripe MCP**](https://github.com/stripe/agent-toolkit) | Official Stripe — payments, customers, subscriptions. Remote at `mcp.stripe.com` | TypeScript |
| [**Cloudflare MCP**](https://github.com/cloudflare/mcp-server-cloudflare) | Official Cloudflare — Workers, R2, KV, D1, DNS, Pages | TypeScript |
| [**Shopify MCP**](https://github.com/Shopify/dev-mcp) | Official Shopify — store data, products, orders | TypeScript |
| [**HubSpot MCP**](https://github.com/HubSpot/mcp-server-hubspot) | Official HubSpot — CRM contacts, deals, marketing tools | TypeScript |
| [**Twilio MCP**](https://github.com/twilio/twilio-mcp) | Official Twilio — SMS, voice, WhatsApp | TypeScript |
| [**Resend MCP**](https://github.com/resendlabs/mcp-resend) | Email delivery via Resend API | TypeScript |
| [**Airtable MCP**](https://github.com/felores/airtable-mcp) | Airtable base read/write/filter operations | TypeScript |
| [**Zapier MCP**](https://github.com/zapier/zapier-mcp) | Trigger 5000+ Zapier automations | TypeScript |
| [**OpenWeatherMap**](https://github.com/david-mcp/mcp-weather) | Real-time weather data and forecasts | Python |
| [**Alpha Vantage**](https://github.com/calvernaz/alphavantage) | Stock market data and financial indicators | Python |
| [**FilingFirehose**](https://filingfirehose.com/mcp) | Hosted SEC EDGAR — 8-K / 10-K / 10-Q / S-3 / 13D, forensic risk scoring, cyber-incident tracking on any US ticker | Hosted |
| [**NASA MCP**](https://github.com/ProgramComputer/NASA-MCP-server) | NASA APOD, Mars Rover, Near-Earth Objects | TypeScript |
| [**OpenAPI MCP**](https://github.com/snaggle-ai/openapi-mcp-server) | Auto-generate MCP tools from any OpenAPI spec | TypeScript |
| [**Salesforce MCP**](https://github.com/salesforce/mcp-server-salesforce) | Official Salesforce CRM and SOQL queries | TypeScript |

---

### 🧠 AI & Memory

> Give your AI a persistent brain

| Server | Description | Language |
|--------|-------------|----------|
| [**Memory**](https://github.com/modelcontextprotocol/servers/tree/main/src/memory) | Knowledge graph persistent memory — official Anthropic | TypeScript |
| [**Sequential Thinking**](https://github.com/modelcontextprotocol/servers/tree/main/src/sequentialthinking) | Dynamic reflective reasoning via thought sequences — official Anthropic | TypeScript |
| [**Mem0 MCP**](https://github.com/mem0ai/mem0-mcp) | User-level long-term AI memory layer | Python |
| [**Zep MCP**](https://github.com/getzep/zep-mcp) | Fast temporal memory for AI agents | Python |
| [**LlamaIndex MCP**](https://github.com/run-llama/mcp-llamaindex) | RAG over custom document collections | Python |
| [**Chroma MCP**](https://github.com/chroma-core/chroma-mcp) | Chroma vector DB for semantic search and memory | Python |
| [**Qdrant MCP**](https://github.com/qdrant/mcp-server-qdrant) | Qdrant vector search and hybrid memory | Python |
| [**ElevenLabs MCP**](https://github.com/elevenlabs/elevenlabs-mcp) | Official ElevenLabs — text-to-speech voice generation | TypeScript |

---

### 📊 Data & Analytics

> Turn raw data into insights

| Server | Description | Language |
|--------|-------------|----------|
| [**Grafana MCP**](https://github.com/grafana/mcp-grafana) | Official Grafana — dashboards, queries, Prometheus, Loki | Go |
| [**DuckDB MCP**](https://github.com/motherduckdb/mcp-server-motherduck) | Blazing-fast OLAP with DuckDB and MotherDuck | Python |
| [**Metabase MCP**](https://github.com/metabase/metabase-mcp) | Official Metabase — dashboards and query execution | TypeScript |
| [**Snowflake MCP**](https://github.com/Snowflake-Labs/mcp) | Official Snowflake data cloud queries and metadata | Python |
| [**Google Sheets MCP**](https://github.com/modelcontextprotocol/servers/tree/main/src/google-sheets) | Google Sheets read/write integration | TypeScript |
| [**Amplitude MCP**](https://github.com/amplitude/mcp-server-amplitude) | Official Amplitude product analytics and event tracking | TypeScript |
| [**Datadog MCP**](https://github.com/DataDog/mcp-server-datadog) | Official Datadog — monitors, logs, metrics, incidents | Python |
| [**InfluxDB MCP**](https://github.com/influxdata/influxdb-mcp-server) | Official InfluxDB time-series data management | Python |
| [**Tableau MCP**](https://github.com/tableau/mcp-server) | Official Tableau workbook and datasource access | Python |

---

### 🖥️ OS & System

> Deep system integration and automation

| Server | Description | Language |
|--------|-------------|----------|
| [**Shell MCP**](https://github.com/zilliz-os/mcp-shell-server) | Execute shell commands with configurable safety guardrails | Python |
| [**macOS Automator**](https://github.com/block/mcp-server-macos-automator) | macOS Automator workflows and AppleScript execution | Swift |
| [**System Info**](https://github.com/baryhuang/mcp-server-sysinfo) | CPU, memory, disk, and running process monitoring | Python |
| [**Cron MCP**](https://github.com/chand1012/mcp-cron) | Schedule and manage cron jobs | Go |
| [**Screenshot MCP**](https://github.com/kimtaeyoon83/mcp-screenshot) | Capture and analyze screen content | Python |
| [**Clipboard MCP**](https://github.com/andybrandt/mcp-simple-clipboard) | Read and write system clipboard | Python |
| [**Time MCP**](https://github.com/modelcontextprotocol/servers/tree/main/src/time) | Time and timezone conversion tools — official Anthropic | Python |

---

### 💬 Communication & Productivity

> AI in every inbox, channel, and workspace

| Server | Description | Language |
|--------|-------------|----------|
| [**Slack MCP**](https://github.com/modelcontextprotocol/servers/tree/main/src/slack) | Slack channels, messages, and reactions — official Anthropic | TypeScript |
| [**Gmail MCP**](https://github.com/modelcontextprotocol/servers/tree/main/src/google-mail) | Gmail compose, send, search, and label — official Anthropic | TypeScript |
| [**Google Calendar**](https://github.com/v-3/mcp-google-calendar) | Create and manage Google Calendar events | TypeScript |
| [**Notion MCP**](https://github.com/makenotion/notion-mcp-server) | Official Notion — pages, databases, blocks, search | TypeScript |
| [**Discord MCP**](https://github.com/v-3/mcp-discord) | Discord server and channel management | TypeScript |
| [**Telegram MCP**](https://github.com/kfastov/mcp-telegram) | Telegram bot messaging | Python |
| [**WhatsApp MCP**](https://github.com/lharries/whatsapp-mcp) | WhatsApp message access via local bridge | Go |
| [**Outlook MCP**](https://github.com/microsoft/mcp-server-ms-graph) | Outlook email and calendar via Microsoft Graph | TypeScript |
| [**Zoom MCP**](https://github.com/zoom/zoom-mcp-server) | Official Zoom — meeting management and transcripts | TypeScript |
| [**Obsidian MCP**](https://github.com/StevenStavrakis/obsidian-mcp) | Read and write your local Obsidian vault | TypeScript |
| [**Todoist MCP**](https://github.com/abhiz123/todoist-mcp-server) | Tasks, projects, and labels via Todoist | Python |
| [**Linear MCP**](https://github.com/linear/linear-mcp) | Official Linear issue tracking and project management | TypeScript |

---

### 🎨 Media & Creative

> Visuals, audio, and content creation

| Server | Description | Language |
|--------|-------------|----------|
| [**Figma MCP**](https://github.com/GLips/Figma-Context-MCP) | Read Figma designs, frames, and component data | TypeScript |
| [**Spotify MCP**](https://github.com/marcelmarais/spotify-mcp-server) | Control Spotify playback and search music | TypeScript |
| [**YouTube MCP**](https://github.com/kimtaeyoon83/mcp-youtube) | YouTube search, video transcripts, metadata | Python |
| [**Cloudinary MCP**](https://github.com/cloudinary/mcp-server-cloudinary) | Official Cloudinary — media upload, transform, CDN delivery | TypeScript |
| [**ElevenLabs MCP**](https://github.com/elevenlabs/elevenlabs-mcp) | Official ElevenLabs — lifelike text-to-speech generation | TypeScript |
| [**Replicate MCP**](https://github.com/replicate/replicate-mcp) | Run any AI model on Replicate (images, video, audio) | TypeScript |

---

### ☁️ Cloud & DevOps

> AI-native cloud infrastructure management

| Server | Description | Language |
|--------|-------------|----------|
| [**AWS MCP**](https://github.com/awslabs/mcp) | Official AWS — EC2, S3, Lambda, IAM, CDK, and more | TypeScript |
| [**Cloudflare MCP**](https://github.com/cloudflare/mcp-server-cloudflare) | Official Cloudflare — Workers, KV, R2, D1, DNS | TypeScript |
| [**GCP MCP**](https://github.com/googleapis/mcp-toolbox-for-databases) | Google Cloud — database toolbox for Cloud SQL, BigQuery | Python |
| [**Azure MCP**](https://github.com/Azure/azure-mcp) | Official Microsoft Azure resource management | TypeScript |
| [**Terraform MCP**](https://github.com/hashicorp/terraform-mcp-server) | Official HashiCorp Terraform — registry, modules, providers | Go |
| [**Pulumi MCP**](https://github.com/pulumi/pulumi-mcp-server) | Infrastructure as Code via Pulumi | TypeScript |
| [**Grafana MCP**](https://github.com/grafana/mcp-grafana) | Official Grafana observability — dashboards, Loki, Prometheus | Go |
| [**Datadog MCP**](https://github.com/DataDog/mcp-server-datadog) | Official Datadog — monitoring, logs, incidents | Python |
| [**Fly.io MCP**](https://github.com/superfly/mcp-server-flyio) | Fly.io app and machine deployment management | TypeScript |

---

## 🚀 Getting Started

### Prerequisites

- [Claude Desktop](https://claude.ai/download) or any MCP-compatible client (Cursor, VS Code, etc.)
- Node.js 18+ (for most TypeScript servers)
- Python 3.10+ (for Python servers)

### Basic Claude Desktop Configuration

Config file location:
- **macOS:** `~/Library/Application Support/Claude/claude_desktop_config.json`
- **Windows:** `%APPDATA%\Claude\claude_desktop_config.json`

```json
{
  "mcpServers": {
    "filesystem": {
      "command": "npx",
      "args": [
        "-y",
        "@modelcontextprotocol/server-filesystem",
        "/Users/yourname/Documents"
      ]
    },
    "github": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-github"],
      "env": {
        "GITHUB_PERSONAL_ACCESS_TOKEN": "your-token-here"
      }
    },
    "memory": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-memory"]
    }
  }
}
```

### Remote MCP Servers (No Installation Required)

Several vendors now offer hosted remote MCP servers — just paste the URL into your client:

| Service | URL |
|---------|-----|
| Stripe | `https://mcp.stripe.com` |
| Cloudflare | `https://mcp.cloudflare.com/mcp` |
| GitHub (remote) | `https://api.githubcopilot.com/mcp` |
| Supabase | Remote via OAuth (see [docs](https://supabase.com/docs/guides/getting-started/mcp)) |

---

## 🤝 Contributing

We welcome contributions! To add an MCP server:

1. **Fork** this repository
2. **Add** your server to the correct category table
3. **Verify** the repository link is live and public
4. **Submit** a Pull Request with a clear description

### Submission Checklist

- [ ] Repository is public and accessible
- [ ] README with installation instructions exists
- [ ] Server is listed in the most relevant category
- [ ] Server entry includes a short, accurate description
- [ ] Repository link is valid and points to the official source
- [ ] No duplicate entries
- [ ] Actively maintained (commit in last 6 months)

---

## 📜 License

[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](LICENSE-CC0)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE-MIT)


---

<div align="center">

**Made with ❤️ by the community**

[⬆ Back to top](#)

*If this list helped you, please give it a ⭐ star!*

</div>
