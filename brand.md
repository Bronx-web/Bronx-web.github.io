# BRONX WEB — BRAND REFERENCE FILE
> Paste this into any new Claude chat for full context. Last updated: March 2026.

---

## BUSINESS

| Field | Detail |
|-------|--------|
| Business Name | Bronx Web NZ |
| Website | https://www.bronxweb.nz |
| Location | Hamilton, Waikato, New Zealand |
| Owner | Bronx |
| Phone | +64-20-4011-4632 |
| Email | bronxweb@gmail.com / hello@bronxweb.nz |
| Facebook | https://www.facebook.com/bronxweb |
| Google Business | https://share.google/KoZppt6jHDESVG7H3 |

**One-liner:** Web App + Automation for NZ tradies — More time + Less admin = better bottom line

**Tagline:** Building The Digital Edge For NZ Tradies.

**Expanding to:** Australia (future — do not market yet)

---

## LONG-TERM VISION

Bronx Web is being built as a scalable asset — not just a freelance web service.

The goal is to build something that can be sold or merged in the future. Every decision needs to consider:
- Is the codebase clean and transferable?
- Are the tools proprietary and reusable?
- Is there recurring revenue?
- Does it scale without the owner doing everything?

**The three sellable layers:**
```
1. Client base      → recurring revenue (maintenance, SEO, hosting)
2. The tools        → Quote Matrix, booking systems (white-label product)
3. The brand        → bronxweb.nz reputation in the NZ tradie market
```

**Business model (current + future):**
```
Now    → Owner builds + sells + delivers
Soon   → Owner sells + scopes, hired dev builds, profits split
Later  → Systemised, white-labelled, recurring revenue, sellable
```

**Tech direction for valuation:**
- Current builds: vanilla HTML/CSS/JS (working, don't break it)
- Client builds: hire React dev, owner project-manages and takes a cut
- Quote Matrix tools: move to React components over time
- Avoid WordPress — plugin dependencies hurt valuation
- Clean React codebase = higher sale/merger value

---

## TARGET MARKET

**Primary:** NZ trade businesses — lawn mowing, property maintenance, brick & block laying
**Secondary (pipeline):** Plumbers, electricians, vehicle service stations
**Customer profile:** Owner-operators, time-poor, not tech-savvy, 30-55 age range, want results not jargon
**Location focus:** Hamilton first, then broader Waikato, then NZ-wide
**Currency:** NZD only

---

## SERVICES & PRICING
*(All prices exclude GST)*

### Start Up — From $2,900 NZD
- 5 page custom site
- Mobile-first responsive design
- Basic online booking
- Google Business optimisation
- Basic SEO setup + Google Maps embed
- Turnaround: 2–4 weeks
- Outcome: Stronger digital footprint, 5–15+ extra leads/month

### Premium — From $4,900 NZD
- Everything in Start Up +
- 2 additional pages
- Advanced quoting/booking systems
- Stronger branding (custom icons, animations)
- Review collection strategy
- Initial local SEO setup
- 1 month free post-launch maintenance
- Outcome: 15–30+ extra leads/month

### Custom — Price on scope
- Everything in Premium +
- Multi-location, special integrations, unique features

---

## BRAND IDENTITY

| Element | Value |
|---------|-------|
| Primary colour | `#44fc17` (electric green) |
| Background | `#000000` (black) / `#464646` (dark grey) |
| Surface | `#2d2e30` |
| Text | `#f1f5f9` (light) / `#cbd5e1` (secondary) |
| Border | `#58595a` |
| Font | Poppins (700, 900 weights) |
| Secondary font | Roboto |
| Logo | BRONX — ref: bronx-fb-logo-1.png |
| Tone | Direct, no fluff, Kiwi voice, confident |
| Style | Dark mode, minimal, bold typography |

**Visual feel:** Dark garage wall meets tech startup. Not corporate. Not cute.

**The Matrix narrative:**
The brand speaks as Morpheus to the tradie who is Neo — just waking up, realising they had the power all along. The "Admin Matrix" is the trap: missed calls, manual quoting, no online presence. Bronx Web is the red pill. Every piece of content, copy, and visual reinforces this frame. Tradies aren't victims — they're capable people who just haven't had the right tools yet.

---

## CONTENT & SOCIAL MEDIA SYSTEM

**Platforms:** Facebook (primary), Google Business Profile
**Content format:** Short educational video ads with AI voiceover (Morpheus tone), result posts, GBP posts
**Posting frequency:** 3x/week Facebook, 1x/week GBP
**Best post time:** 5am (per Buffer 2026 data)
**Scheduling tool:** Meta Business Suite (free)

### Weekly Content Mix
| Day | Format | Purpose |
|-----|--------|---------|
| Monday | Educational video ad + voiceover | Reach + awareness |
| Wednesday | Before/after result post | Social proof |
| Friday | Straight Kiwi tip | Engagement |
| Weekly | Google Business post + CTA | Local SEO signal |

### Video Script Formula (under 15 seconds)
1. **Hook (0–3s):** Name the problem
2. **Educate (3–12s):** The insight — calm, certain, Morpheus energy
3. **CTA (12–15s):** Book a free call / get a quote

### Morpheus tone guide
- Calm. Certain. Never pushy.
- Speaks like someone who already knows the answer
- The tradie already has what it takes — they just need to see it
- Not corny, not salesy — just clear and real

---

## VOICE & TONE RULES

- No AI-sounding language — write like a real Kiwi
- No corporate buzzwords
- Short sentences. Direct.
- Speak to the tradie, not at them
- Use "you" not "your business"
- NZD, NZ spelling (e.g. "organise" not "organize")
- Avoid: "leverage", "synergy", "streamline", "empower", "elevate"
- Use: "more jobs", "less hassle", "book online", "stop missing calls"

---

## TECH STACK

| Tool | Use |
|------|-----|
| HTML / CSS / JS | Current builds — transitioning to React for client sites |
| GitHub Pages | Static hosting |
| Netlify | Deployment / future functions |
| Google Maps API | Quote Matrix tools |
| Gemini AI (Google Studio) | AI-powered quote generation |
| jsPDF | PDF output in quote tools |
| Calendly | Booking widget (contact page) |
| Google Apps Script | Lead capture to Google Sheets (planned) |
| Claude (claude.ai) | Content, automation, code assistance |
| Canva | Social media graphics (MCP connected to claude.ai) |
| Meta Business Suite | Facebook scheduling |

**Domain:** bronxweb.nz (custom domain via Netlify)
**Repo:** GitHub — bronxweb.nz project

---

## TOOLS BUILT

### Quote Matrix — Bricklaying (V1)
- URL: bronxweb.nz/quote-matrix-v1/
- Stack: Vanilla HTML/CSS/JS + Gemini AI + jsPDF
- Status: Live (demo)
- ⚠️ API key exposed — rotate before production

### Quote Matrix — Lawn Mowing
- URL: bronxweb.nz/quote-matrix-lawns
- Stack: Vanilla HTML/CSS/JS + Google Maps API + jsPDF
- Features: Polygon drawing tool, satellite view, grass condition selector, PDF output
- Status: Live, tested on iOS ✅
- ⚠️ Maps API key needs restricting to bronxweb.nz/*

---

## PENDING BUILD QUEUE

- [ ] Hybrid mobile/desktop UX for Lawn Quote Matrix
- [ ] Google Sheets lead capture via Apps Script
- [ ] Tradie email notification on quote submission
- [ ] Hedge trimming Quote Matrix (clone of lawn version)
- [ ] Garden cleanup Quote Matrix
- [ ] Netlify Functions for API key protection
- [ ] White-label Quote Matrix for paying clients

---

## EXISTING PAGES

| Page | URL |
|------|-----|
| Home | bronxweb.nz/index.html |
| Case Study | bronxweb.nz/case-study.html |
| Services | bronxweb.nz/services.html |
| Contact | bronxweb.nz/contact.html |
| Infographic | bronxweb.nz/info-graph.html |
| Privacy Policy | bronxweb.nz/privacy-policy.html |
| Terms of Service | bronxweb.nz/terms-of-service.html |
| Lawn Quote Matrix | bronxweb.nz/quote-matrix-lawns/ |
| Brick Quote Matrix | bronxweb.nz/quote-matrix-v1/ |

---

## SCHEMA MARKUP (already implemented)
- LocalBusiness on index.html
- Article on case-study.html + info-graph.html
- Organization on contact.html
- ItemList + FAQPage on services.html

---

## IMPORTANT CONTEXT FOR CLAUDE

- Owner is studying Level 4 IT
- Solo operator — time is limited, efficiency matters
- Comfortable with HTML/CSS/JS, learning React
- Uses Claude Code (VSCode extension) for dev work
- Uses claude.ai (this interface) for content + strategy
- Canva connected to claude.ai via MCP integration
- Do not suggest tools that add complexity without clear ROI
- Always give realistic time estimates — not optimistic ones
- Always show logic before output on anything important
- If unsure, say so — don't guess
- NZ market only right now. Australia is future.
- Building Bronx Web as a sellable/mergeable asset — every decision should reflect that
- Client builds will use hired React devs, owner project-manages and takes a cut
- WordPress is not the direction — React is the target stack for future client builds