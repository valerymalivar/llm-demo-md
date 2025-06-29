# Underly — The AI-Ready Web Layer  

> **One line of code turns any page into clean, structured Markdown for LLMs.**

---

## 1. Problem  
- **1.2 B websites are built for humans, not large-language models (LLMs).**  
- Users already skip Google and ask **ChatGPT / Claude / Perplexity** directly.  
- LLMs choke on messy HTML (“div soup”, ads, JS, SEO hacks) → wrong answers or ignore your site.  
- Site owners lose control over brand voice and miss emerging *AI referral* traffic.  

---

## 2. Solution  
**Underly** adds a small script (or React component) that:  
1. **Auto-converts** any page to pristine Markdown (`.md`) or JSON in real time.  
2. Publishes **`llms.txt` + `llms-full.txt`** — a machine-readable index & full dump of key docs.  
3. Surfaces **Copy / Open-in-ChatGPT** buttons for end-users.  
4. Tracks what content gets copied / queried (**analytics layer**).  

> *“AMP for LLMs”* — makes every site **agent-ready** without migration or heavy AI infra.

---

## 3. Why Now  
- AI assistants already answer **0.5 – 1 %** of web queries (BrightEdge, 2024) — forecast **≥ 10 % by 2025**.  
- Early adopters (Coinbase docs, Vercel, Anthropic) exposed entire docs via `llms.txt` and saw *+10 % sign-ups* from ChatGPT.  
- No vendor-neutral, drop-in tool exists for the other **≈ 1.19 B** sites.

---

## 4. Product Snapshot  
| Plan | Price | Included |
|------|-------|----------|
| **Try** | **$29 / mo** | 1 domain · 5 pages · UI kit |
| **Grow** | **$99 / mo** | 1 domain · 20 pages + $0.40/extra · analytics · support |
| **Scale** | Custom | Unlimited pages · SSO · adv. analytics · SLA |

*Stack:* TypeScript · React UI kit · Headless Chromium render · Markdown/JSON output · MCP-ready.

---

## 5. Market  
| Layer | Metric | Notes |
|-------|--------|-------|
| **TAM** | **1.2 B** sites | Any site “built for humans, not LLMs” |
| **SAM** | **50–100 M** doc-heavy / SEO-driven sites | SaaS docs, knowledge bases, dev portals, edu content |
| **SOM** | **1 K** early-adopter companies (2025) | Already see AI traffic; ready to pay $29–99/mo |

---

## 6. Business Model  
- **SaaS subscription** (pages tier) + overage on bulk conversions.  
- Long term: data network → sell **LLM context API** & **benchmarks** to AI platforms.

---

## 7. Traction (Launch → Week 2)  
| KPI | Value |
|-----|-------|
| Launch | **June 2025** |
| Time to first $ | **48 h** |
| Paying customers | **10** |
| MRR | **≈ $303** |
| Wait-list | **20 +** companies |
| Recognition | Featured #1 on **Lovable Shipped** leaderboard |
| VC inbound | Yes |

---

## 8. Team  
| Name | Role | Background |
|------|------|------------|
| **Valeriy Sharipov** | Founder/CEO | 2× founder · 500 Global alum · ex-AI lead for Puma & Pepsi · NVIDIA GTC speaker |
| **Core ML Eng.** | ex-Samsung AI Research | PhD, 5 y LLM fine-tuning |

---

## 9. Competition  
| Player | Focus | Gap we exploit |
|--------|-------|---------------|
| **Mintlify** | Docs hosting with built-in `llms.txt` | Works only on its platform; migration required |
| **Jina Reader API** | Dev API for scraping | Backend only; no on-site UX / analytics |
| **Firecrawl (Mendable)** | OSS crawler → Markdown | Library, not plug-and-play SaaS |
| **Browser extensions** | User-side copy helpers | Site owner gets zero control or data |

---

## 10. Moats  
1. **Best-in-class conversion engine** (edge cases, tables, code blocks).  
2. **Unique copy / LLM-usage analytics** → data flywheel.  
3. **First neutral “agent-ready” standard** & developer-friendly UI kit.  
4. Speed of shipping (≈ weekly) & thought leadership in *AIO* (AI-optimized content).  

---

## 11. Roadmap  
| Quarter | Key milestones |
|---------|----------------|
| **Q3 2025** | Ship **Scale** tier (multi-domain, SSO, SLA) · Launch WordPress & Docusaurus plugins |
| **Q4 2025** | AI usage dashboard (copy heat-maps, prompt logs) · Agency & CMS marketplace channels |
| **H1 2026** | 1 K paying sites · $1 M ARR · Public “Underly AI-context API” beta |
| **H2 2026** | Default standard for AI-ready docs · Partnerships with major LLM providers / search |

---

## Appendix A — Market Data  
- **95 %** of the web still unstructured (Underly survey, 2025).  
- AI referral traffic growing **71 % MoM** on Perplexity (Similarweb, Mar-25).  
- Estimated web-traffic loss from generative search: **15–25 %** (Insight Partners, 2024).  

## Appendix B — Underly vs. Build-Your-Own  
| Requirement | DIY | **Underly** |
|-------------|-----|-------------|
| Write & maintain `llms.txt` | Manual, ongoing | Auto-generated |
| HTML → Markdown edge cases | Custom code | Production-grade parser |
| Analytics (what AI reads) | None | Built-in |
| Time to deploy | Days–weeks | **< 1 min** |
| Cost | Eng. time + infra | $29–99/mo |

---

*Last updated : 29 Jun 2025*  
