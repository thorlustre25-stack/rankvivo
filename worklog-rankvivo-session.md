# RankVivo — Business Planning Session Worklog

---

## 2026-03-08 — SEO Business Idea Analysis & Brand Creation

### Source Material
- **Instagram post:** "The Claude SEO Domination Stack" by @godofprompt (7-slide carousel)
- **Article:** [Claude Code for SEO Work](https://searchengineland.com/claude-code-seo-work-470668) — Search Engine Land

### The 5 Claude SEO Prompts Analyzed
1. **Competition Gap Killer** — Scan competitor sites for missing content, keyword gaps, trust gaps
2. **Full Schema Audit** — Extract/evaluate JSON-LD schema markup, generate fixes
3. **Buyer-Intent Keyword Sniper** — Find high-intent local keywords ("near me", "emergency", "same day")
4. **Business vs Competitor X-Ray** — Side-by-side comparison of services, reviews, strengths
5. **Google Business Profile (GBP) Hijack** — Analyze competitor GBP posts, generate better ones

### Business Feasibility Assessment

**Viable entry point:** Google Business Profile management
- Simple enough for a beginner to deliver immediately
- Fast results (weeks, not months like SEO)
- Charge $200-400/month per client
- Claude can generate weekly posts, review responses, profile optimizations

**Harder to deliver without expertise:**
- Technical SEO (schema, Core Web Vitals, indexing)
- Full SEO strategy (requires understanding, not just AI output)
- Schema audits (generating JSON-LD is easy, knowing which schema matters is hard)

**Key warning from Search Engine Land article:**
- Claude does analysis, NOT strategy — human judgement still required
- LLMs can hallucinate data — must verify before delivering to clients
- ~15 min setup per client for API data pulls (GSC, GA4, Ads)
- Doesn't replace tools like Semrush/Ahrefs for historical data

### Realistic Service Tiers

| Service | Difficulty | Claude helps? | Price range |
|---|---|---|---|
| GBP management | Easy | Yes, heavily | $200-500/mo |
| Content writing | Easy-Medium | Yes | Commoditized |
| Keyword research | Medium | Yes, with verification | Bundled |
| Schema/technical SEO | Hard | Partially | High but risky |
| Full SEO strategy | Hard | Analysis only | High margins, high skill |

### Decision: Start with GBP, outsource technical SEO later

---

## 2026-03-08 — Brand Name Selection: RankVivo

### Names Researched (30+ candidates)
Deep web search conducted on every name suggested. Results:

**TAKEN (active businesses in SEO/marketing):**
MapRank, LocalPulse, RankForge, SearchCraft, ClearRank, AutoRank, LocalRank, RankLocal (trademarked), LocoRank, NexoRank, SignalSEO, RankPro (trademarked), PrimaRank, VisibleRank, RankEngine AI, PeakIndex

**FREE (no existing business found):**
RankVivo, RankAlto, RangoLocal, RangoVivo, ClaroRank, RankRapido, RankDirecto, RankTotal, RankZona, CumbreRank, AutoRanka

### Final Two Candidates: RankAlto vs RankVivo

**RankAlto — Pros:**
- "Alto" = high in Spanish, understood in English
- Professional, clean, corporate-safe
- Zero brand conflicts of any kind
- Easy to spell from hearing it
- Scales to any service

**RankAlto — Cons:**
- Safe but forgettable
- No story or emotional resonance
- "Alto" = stop sign in Spanish (minor)
- Sounds like a SaaS tool, not a personal brand

**RankVivo — Pros:**
- "Vivo" = alive/living — strong brand story ("we keep your rankings alive")
- Memorable, energetic, conversation starter
- Suggests ongoing active service (fits monthly retainers)
- Unique — zero search competition
- Better for personality-driven local business

**RankVivo — Cons:**
- Vivo is a major phone brand (4th largest globally)
- Vivo holds trademarks in Class 35 (marketing) and Class 42 (software)
- Vivo has actively sued companies using "vivo" in names
- VIVO Agency exists (US healthcare marketing, $4M revenue)
- English speakers may confuse with "Vevo" (music platform)

### Risk Assessment for Local Catalunya Operation
- Vivo trademark enforcement has been in India, Australia, Indonesia — NOT Spain
- A one-person side hustle in Maresme is invisible to Vivo's legal team
- Different industry (GBP management vs phones)
- Risk assessed as **negligible** for this scale and geography

### Decision: RankVivo

---

## 2026-03-08 — Digital Assets Secured

| Asset | Handle/URL | Status |
|---|---|---|
| Domain | rankvivo.com | Secured |
| Instagram | @rankvivo | Secured |
| X (Twitter) | @rankvivo | Secured |
| LinkedIn | @rankvivo | Secured |
| TikTok | @rankvivo | Secured |

### Existing Website
- Location: `C:\Users\cipol\OneDrive\Desktop\Thor's Projects\Web Service Test\index.html`
- Single-page template, currently branded as "Digital Services Inc"
- Navy blue + gold colour scheme, Playfair Display + Lora fonts
- Sections: Hero, About, Services (6 cards), Portfolio, Contact, Google Maps
- Has WhatsApp floating button, scroll animations, CSS variables for easy rebranding
- Not yet live — will deploy to rankvivo.com when ready

### Rebranding Tasks (when ready)
1. Replace "Digital Services Inc" with "RankVivo" throughout
2. Update colour palette to match RankVivo brand
3. Rewrite service cards for GBP management + local SEO focus
4. Add Spanish/Catalan content for Maresme clients
5. Update meta descriptions, title, social links to @rankvivo
6. Replace placeholder images with Maresme local imagery
7. Rename project folder from "Web Service Test" to "RankVivo"

---

## 2026-03-15 — Website Live + Service Expansion Note

### Website deployed
- rankvivo.com live on Vercel, DNS via Cloudflare
- Bilingual Spanish (primary) + Catalan (secondary)
- Formspree contact form working
- Google Search Console verified, sitemap submitted
- Logo + circular favicon deployed
- Social: Instagram + LinkedIn (@rankvivo)

### SEO Optimisation — DONE
- Added Open Graph meta tags (for social sharing previews)
- Added Twitter Card meta tags
- Added canonical URL
- Added JSON-LD LocalBusiness structured data (helps Google understand the business)
- Added semantic `<main>` wrapper
- Replaced 2 placeholder portfolio items with real projects:
  - **QueMaresme.com** — Thor's own project, Maresme area guide
  - **EleanorTaylorFurniture.co.uk** — friend's artisan furniture e-commerce
- Portfolio "Ver proyecto" buttons now link to live websites

**Still to consider for future SEO improvements:**
- Add `aria-hidden="true"` to decorative icons (accessibility)
- Add skip-to-main-content link
- Take actual screenshots of portfolio sites to replace icon placeholders
- Add FAQ section with long-tail keywords
- Add review/testimonial schema when client testimonials are available

### Service expansion — DONE
- Added **Optimización SEO** and **Marketing digital** service cards to the website
- Updated footer services list to include SEO and Marketing digital
- This broadens the offering beyond web design and GBP management
- Consider adding pricing/packages page later

---

## 2026-03-16 — SEO Audit, Schema & Portfolio Updates

### SEO Technical Improvements Deployed
- **Open Graph meta tags** — proper previews when shared on social media (Facebook, LinkedIn, WhatsApp)
- **Twitter Card meta tags** — proper previews on X/Twitter
- **Canonical URL** (`<link rel="canonical">`) — prevents duplicate content indexing
- **JSON-LD LocalBusiness schema** — structured data telling Google: business name, location (Calella/Maresme), services, email, social profiles, coordinates, languages spoken
- **Semantic `<main>` wrapper** — improved HTML structure for crawlers and screen readers
- **Heading font switched** from Outfit to Poppins (matches logo, available on Google Fonts + Canva)

### Branding Assets Created
- **Logo:** RankVivo.png (600x150, Poppins ExtraBold, "Rank" navy #1e3a5f + "Vivo" gold #c9a962)
- **Favicon:** RV circular (512x512 source, 32x32 deployed) — navy R, gold V, transparent circular crop
- **Social media profile image:** RV square (512x512)
- All stored in `/LOGOs/` folder

### Portfolio — Real Projects Added
- **QueMaresme.com** (Thor's project) — Maresme area digital guide, links to live site
- **EleanorTaylorFurniture.co.uk** (friend's project) — artisan furniture e-commerce, links to live site
- Replaced 2 generic placeholder items (taller mecánico, alojamiento turístico)

### Infrastructure
- GitHub repo renamed from `Web-Service-Test` to `rankvivo`
- Branch renamed from `master` to `main`
- Vercel production deployments now via `vercel --prod` CLI
- Formspree contact form connected and tested (form ID: mdawlygb)
- Google Search Console verified (HTML tag method), sitemap.xml submitted

### Colour Palette — Confirmed
- User explicitly prefers **navy blue (#1e3a5f) + gold (#c9a962)** — do NOT change to teal/green
- Original prompt file suggested teal; user rejected it

### Pending / Future Tasks
- Phone number + WhatsApp (waiting on Spanish SIM)
- Custom email setup via Cloudflare (info@rankvivo.com routing)
- Screenshot real portfolio sites to replace icon placeholders
- Add FAQ section with long-tail local keywords
- Add client testimonials + review schema when available
- Consider pricing/packages page
- Add `aria-hidden="true"` to decorative icons
- Add skip-to-main-content link for accessibility
- Social media content strategy (Instagram + LinkedIn active posting)
- TikTok to be added to site when actively posting

---

## 2026-03-21 — NFC Review Stands as Product/Service Offering

### Idea
NFC tap-to-review stands for clients — customer taps phone on stand, goes directly to Google Reviews page. Physical product that complements the digital review management service.

### Source
Found generic NFC review stands on Temu (~€3-5 each). Need RankVivo branding on them.

### Branding Options (cheapest to most professional)
1. **Custom vinyl stickers** — Order 50-100 with RankVivo logo, stick on generic stands. ~€10-20 total. Fastest to start.
2. **Custom rubber stamp** — Works on paper/card but not ideal on PVC plastic stands.
3. **Custom-printed NFC stands** — AliExpress/Alibaba suppliers do custom logo NFC stands. MOQ 50-100 units, ~€1-3 each. Best for scaling.

### Business Model
- Buy generic or custom-branded NFC stands in bulk
- Programme each stand with client's Google Reviews link
- Include as part of "Gestión de ressenyes" service package or sell as add-on
- Recurring value: clients see physical RankVivo branding in their shop daily

### Decision
Start with **custom stickers** on generic stands. Move to bulk custom-printed stands when demand justifies it.

---

## Business Summary

- **Brand:** RankVivo
- **Domain:** rankvivo.com
- **Target area:** Maresme, Catalunya (and surrounding areas)
- **Target clients:** Local businesses (restaurants, shops, salons, services)
- **Entry service:** Google Business Profile management
- **Expanded services:** SEO optimisation, digital marketing
- **Growth path:** Outsource technical SEO/marketing to experts as demand grows
- **Tools:** Claude.ai + Claude Code for content generation, analysis, and learning
- **Model:** Side hustle, one-person operation, monthly retainers
