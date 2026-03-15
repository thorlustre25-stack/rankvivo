# RankVivo — Claude Code Update Brief

## What This Is

This is a prompt file for Claude Code. It brings Claude Code up to speed on the business context and what needs changing in `index.html` — the RankVivo company website template.

---

## Business Context

**Company name:** RankVivo  
**Website:** rankvivo.com  
**Location:** Calella / Maresme area, Catalonia, Spain  
**Target market:** Small local businesses in the Calella/Maresme area with little or no online presence  
**Languages relevant to the market:** Catalan (primary), Spanish, English, French (tourism area)

### What RankVivo Does

RankVivo is a web services business offering two main tracks:

1. **Static HTML/CSS websites** — hosted on Vercel (free tier), suited for simple businesses like dentists, lawyers, and tradespeople
2. **WordPress websites** — hosted on SiteGround or similar, for businesses needing dynamic content like restaurants and salons

**Core pricing model:**
- Website builds: approximately €400–500
- Monthly maintenance packages: tiered, covering hosting, security, Search Engine Optimisation (SEO), and Google Business Profile management
- "Build and hand-off" option available: one-time fee, client self-manages hosting

**Additional service being developed:**
- Artificial Intelligence (AI) chatbot widgets as a recurring revenue add-on (~€30–60/month per client), using FastBots platform

---

## What Needs Changing in index.html

The current file is a generic template called "Digital Services Inc". It needs to be updated to reflect RankVivo. Below are all the required changes, section by section.

### 1. Meta / Head

- `<title>`: Change to `RankVivo | Disseny Web i Presència Digital per a Negocis Locals` (Catalan)
- `<meta name="description">`: Update to reflect RankVivo's actual offering in Catalan or English
- The language of the page content should be **Catalan** (`lang="ca"` on the `<html>` tag)

### 2. Branding / Logo

- All instances of `Digital<span>Services</span>` → change to `Rank<span>Vivo</span>`
- Update CSS variable `--primary-color` — consider a fresh palette that is not the current generic deep blue. The brand should feel modern, local, trustworthy, and slightly energetic. Suggested: try a warm teal or a confident green that differentiates from generic corporate blue.

### 3. Navigation Links

Keep the same section anchors (`#home`, `#about`, `#services`, `#portfolio`, `#contact`) but translate labels to **Catalan**:
- Home → Inici
- About → Sobre nosaltres
- Services → Serveis
- Portfolio → Projectes
- Contact → Contacte

### 4. Hero Section

- **Headline:** Replace "Transform Your Online Presence" with something in Catalan, e.g. `El teu negoci mereix una presència digital professional`
- **Subheadline:** Catalan copy explaining RankVivo helps local businesses in the Maresme area get found online with professional websites and Google Business Profile management
- **Primary button:** `Parla amb nosaltres` (Talk to us) → links to `#contact`
- **Secondary button:** `Els nostres serveis` (Our services) → links to `#services`

### 5. About Section

- **Heading:** `Sobre RankVivo`
- **Body copy (Catalan):** Explain that RankVivo is a local digital services company helping small businesses in the Maresme area build their online presence. Emphasis on: local knowledge, affordable pricing, and practical results.
- **Mission statement:** Something like `Ajudem els negocis locals del Maresme a competir en línia amb webs professionals i gestió de Google Business Profile.`
- **Feature cards — update text to Catalan:**
  - "Personalized Service" → `Servei personalitzat` — We get to know each client and their business before building anything
  - "Results-Driven" → `Orientats a resultats` — More visibility on Google, more calls, more clients
  - "Affordable Excellence" → `Qualitat a preu just` — Professional quality at prices that make sense for small businesses
- Replace the `--font-body` and `--font-heading` with something more distinctive than Poppins/Inter. Suggestions to evaluate: Outfit + Lora, or Sora + Source Serif 4. Update the Google Fonts link accordingly.

### 6. Services Section

- **Section title (Catalan):** `Els nostres serveis`
- **Subtitle (Catalan):** `Tot el que necessita el teu negoci per destacar a internet.`
- Update the 6 service cards with Catalan titles and descriptions:

| Icon | Title (Catalan) | Description (Catalan) |
|------|-----------------|----------------------|
| fa-laptop-code | Disseny i desenvolupament web | Webs modernes, ràpides i adaptades a tots els dispositius. Disseny professional que reflecteix la identitat del teu negoci. |
| fa-sync-alt | Renovació de webs | Transforma una web antiga en una eina moderna i eficaç. Mantenim la teva identitat mentre millorem tot el que no funciona. |
| fab fa-google | Gestió de Google Business Profile | Configuració i gestió del teu perfil a Google perquè els clients et trobin fàcilment quan busquen els teus serveis. |
| fa-star | Gestió de ressenyes | Responem a les ressenyes dels teus clients de manera professional, generant confiança i millorant la teva reputació en línia. |
| fa-map-marker-alt | Optimització a Google Maps | Millorem la teva visibilitat a Google Maps perquè apareixis abans que la competència quan algú et busca al Maresme. |
| fa-headset | Suport i manteniment | El teu web sempre actualitzat, segur i funcionant. Estem disponibles quan ens necessites. |

### 7. Portfolio Section

- **Section title (Catalan):** `Els nostres projectes`
- **Subtitle (Catalan):** `Alguns exemples del nostre treball recent.`
- The placeholder images and project names should reflect realistic local business types for the Maresme area:
  - Restaurant local (Restaurant website & Google Business Setup)
  - Clínica dental (Dental clinic revamp & Maps optimisation)
  - Perruqueria (Hair salon — complete digital presence)
  - Assessoria (Law/accounting firm — professional website)
  - Taller mecànic (Mechanic/auto repair — Google Business & review management)
  - Allotjament turístic (Tourist accommodation — website + booking integration note)
- Replace `via.placeholder.com` URLs with a local placeholder service or use CSS background colours instead — the `via.placeholder.com` CDN (Content Delivery Network) can be unreliable
- Portfolio overlay button text: `Veure projecte`

### 8. Contact Section

- **Section title (Catalan):** `Contacta'ns`
- **Subtitle (Catalan):** `Parlem del teu negoci. La primera consulta és gratuïta.`
- **Form heading:** `Envia'ns un missatge`
- **Form labels (Catalan):**
  - Full Name → `Nom complet`
  - Email Address → `Correu electrònic`
  - Phone Number → `Telèfon`
  - Your Message → `El teu missatge`
  - Placeholder for message → `Explica'ns el teu projecte...`
  - Submit button → `Enviar missatge`
- **Contact info heading:** `Informació de contacte`
- **Contact info body (Catalan):** `Tens algun dubte? Contacta'ns per qualsevol d'aquests canals.`
- **TODO items to fill in:**
  - Email: update to actual RankVivo email
  - Phone: update to actual phone number (Spanish format, e.g. `+34 6XX XXX XXX`)
  - Address: update to Calella or Maresme area
  - Google Maps embed: update to actual location
  - WhatsApp number: update to actual number (format for Spain: `34` + 9-digit number)
- **Social links:** Keep Instagram, LinkedIn, Facebook — remove TikTok unless actively used. Update all URLs to actual profiles.
- **Contact info labels (Catalan):**
  - Email → `Correu electrònic`
  - Phone → `Telèfon`
  - Location → `Ubicació`

### 9. Footer

- Replace all "Digital Services Inc" references with **RankVivo**
- Update copyright: `© 2025 RankVivo. Tots els drets reservats.`
- **Quick Links column title (Catalan):** `Enllaços`
- **Services column title (Catalan):** `Serveis`
- All link labels → translate to Catalan (same as nav and services above)
- Footer brand description (Catalan): `Ajudem negocis locals del Maresme a créixer en línia amb webs professionals i gestió de Google Business Profile.`

### 10. WhatsApp Button

- Update `href` to actual WhatsApp number: `https://wa.me/34XXXXXXXXX`

### 11. JavaScript — Contact Form

- The `alert()` on form submit → replace with a proper inline success message in Catalan: `Gràcies pel teu missatge! Et contactarem aviat.`
- Consider connecting to Formspree or similar (leave as a TODO comment if not doing now)

### 12. General Code Quality

- Fix the `lang` attribute on `<html>` tag: should be `lang="ca"` for Catalan
- Add `hreflang` meta if multilingual versions are planned later
- Ensure all `aria-label` attributes are also updated to Catalan for accessibility

---

## Things NOT to Change

- The overall page structure and section order — it works well
- The responsive CSS (Cascading Style Sheets) breakpoints — the mobile/tablet logic is solid
- The Intersection Observer scroll animation logic — keep as-is
- The hamburger menu JavaScript — keep as-is
- Font Awesome icon library — keep as-is

---

## Priority Order

If doing this incrementally, suggested order:

1. Branding (logo text, page title, meta description, `lang` attribute)
2. Navigation labels → Catalan
3. Hero copy → Catalan
4. Services section → Catalan
5. About section → Catalan
6. Contact details (fill in real info)
7. Portfolio placeholders (update descriptions to local business types)
8. Footer copy → Catalan
9. Colour palette refresh (optional but recommended)
10. Font update (optional but recommended)

---

## Notes for Claude Code

- The file is a single-file static HTML page — all CSS (Cascading Style Sheets) and JavaScript is inline
- Hosted on Vercel — no build step, deploy directly
- Do not introduce external dependencies beyond what is already there (Google Fonts and Font Awesome are fine)
- Keep all changes within the single `index.html` file unless explicitly asked to split
- When updating colours, update only the CSS variables in `:root` — do not hardcode colours elsewhere
