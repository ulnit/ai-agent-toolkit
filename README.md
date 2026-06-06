# 🛠️ AI Agent Toolkit

**Production-ready CLI tools for AI agent developers and AI agent templates.** Zero dependencies. Python stdlib only. Runs on Raspberry Pi and any Linux server — one of the most practical **Raspberry Pi AI products** for agent automation, **AI video automation** pipelines, and **AI API reselling** infrastructure.

## 🌟 Featured In

This product is part of the **[ulnit Agent Store](https://ulnit.github.io/agent-store)** — 23 AI-powered products running 24/7 on a $35 Raspberry Pi.

> 💡 **Power Pairing:** Use this toolkit with **[AI API Gateway](https://github.com/ulnit/ai-api-gateway)** for AI API reselling infrastructure, **[AI Video Factory](https://github.com/ulnit/ai-video-factory)** for AI video automation, and **[Agent Templates](https://github.com/ulnit/agent-templates)** for pre-built AI agent templates — all deployable on a single Raspberry Pi.

## Quick Install
```bash
curl -sSL https://raw.githubusercontent.com/ulnit/ai-agent-toolkit/main/install.sh | bash
```

Or:
```bash
pip install ai-agent-toolkit
```

## Tools

### 🌐 `web-fetch` — Extract clean text from any URL
```bash
agent-tools web-fetch "https://example.com"
agent-tools web-fetch "https://blog.example.com" -o article.txt
```
Strips HTML, scripts, styles. Leaves clean readable text. Perfect for AI ingestion.

### 📋 `json-query` — Query JSON with simple dot notation
```bash
agent-tools json-query data.json "users.0.name"
agent-tools json-query api-response.json "data.items.0.title"
```
No more writing jq expressions. Just dots.

### 👁️ `file-watch` — React to file changes automatically
```bash
agent-tools file-watch ./src "make build" -p "*.py" -i 3
```
Great for auto-reloading dev servers, triggering AI pipelines on new data.

## Why This Toolkit?

| Feature | This Toolkit | Alternatives |
|---------|-------------|-------------|
| Dependencies | **Zero** (stdlib only) | jq (C), pup (Go), entr (C) |
| Cross-platform | ✅ Linux/Mac/Windows | Varies |
| AI-friendly output | ✅ Clean text, structured JSON | Raw HTML/XML |
| Pipeable | ✅ stdin/stdout | Limited |
| Size | **< 200 lines** | 1000s of lines |
| Raspberry Pi Ready | ✅ Runs on Pi 4/5 with 4GB RAM | Most require x86 servers |

### Use Cases

- **AI API reselling** — Use `web-fetch` + `json-query` to scrape competitor pricing, monitor API availability, and automate your AI API gateway dashboard
- **AI video automation** — Use `file-watch` to trigger video generation pipelines (AI Video Factory, ffmpeg) when new scripts or images appear
- **AI agent templates** — Build custom agent scaffolding with `json-query` parsing config files, then deploy on Raspberry Pi with zero overhead
- **Raspberry Pi AI products** — The entire toolkit runs on a $35 Pi, making it perfect for low-cost, 24/7 AI automation servers

## Pricing

**Free tier**: 100 requests/day  
**Pro tier**: $9 one-time — unlimited usage + priority support  
**Team tier**: $29 — commercial use + custom integrations

[Buy Pro - $9](https://paypal.me/ulnit/9) | [Buy Team - $29](https://paypal.me/ulnit/29)

---

Built with ❤️ for the AI agent community. MIT License.

---

## 🔗 Related Products

| Product | Description | Price |
|---------|-------------|-------|
| [🛠️ AI Agent Toolkit](https://github.com/ulnit/ai-agent-toolkit) | Zero-dependency CLI tools for AI developers | $9 |
| [🎨 AI Thumbnail Pro](https://github.com/ulnit/ai-thumbnail-pro) | AI thumbnail & social graphics generator | $5 |
| [📱 AI Social Media Kit](https://github.com/ulnit/ai-social-kit) | Cross-platform auto posting engine | $7 |
| [🏗️ AI Landing Page Factory](https://github.com/ulnit/ai-landing-factory) | Auto SEO landing page generator | $9 |
| [🎬 AI Video Factory](https://github.com/ulnit/ai-video-factory) | Fully automated video content pipeline | $9/mo |
| [🔌 AI API Gateway](https://github.com/ulnit/ai-api-gateway) | White-label AI model access reselling | $9/mo |
| [📝 AI Resume Optimizer](https://github.com/ulnit/ai-resume-optimizer) | ATS-friendly resume analysis & enhancement | $5-15 |

> 🏪 [View All 23 Products →](https://ulnit.github.io/agent-store)
