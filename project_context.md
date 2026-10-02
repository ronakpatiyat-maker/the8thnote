# The 8th Note — Website Project Context

> **How to use this file:** Keep it in the repo as `PROJECT-CONTEXT.md`. When you start a new chat with Claude, upload this file first and say "here's the context." It captures the business, the hosting setup, the site structure, the file-naming rules, and everything still left to do. Keep it updated as the site grows (especially the **Asset Registry** and **To-Do** sections).

> **Working agreement:** After **every** change, Claude updates **both** living files in the same step — `index.html` (the website) and this `PROJECT-CONTEXT.md` — so they always match. (SEO files `robots.txt` / `sitemap.xml` are set-once and rarely change.) Claude always says exactly which file(s) to re-upload.

_Last updated: 2 Oct 2026_

---

## 1. Business snapshot

- **Name:** The 8th Note
- **Person:** Ronak Patiyat — keyboardist & singer, trained at a leading Mumbai music institute.
- **Location:** VV Puram, Bengaluru (also teaches live online).
- **Phone / WhatsApp:** +91 94800 61108
- **Instagram:** business **@the8thnote__** · personal **@ronakpatiyat__**
- **YouTube:** https://youtube.com/@ronakpatiyat (membership = `/join`)
- **Three sides:**
  1. **Teaching (one-on-one)** — **piano, harmonium & vocals**, basic to advanced. 100+ Jain songs on piano, 100+ Jain stavans in voice, Bollywood piano, classical vocal foundation (sur & taal). **Students 10 years & above.** In person (VV Puram) or **live online**.
  2. **Performing** — devotional / Bhakti singing for Jain programs, Bhakthi Sandhya, poojas, paths, religious events.
  3. **Online courses** — YouTube: free + members-only at **₹49/month**.
- **Coming up:** launch in **November** (details TBD) — site has a live **countdown**.
- **Brand look:** black background, one red accent (`#E50914`), white text. Font: Archivo.

---

## 2. Hosting & how to publish a change

- **Repo:** https://github.com/ronakpatiyat-maker/the8thnote
- **Live site:** https://ronakpatiyat-maker.github.io/the8thnote/
- **Host:** GitHub Pages (Settings → Pages → Deploy from a branch → `main` → `/root`).

**Update loop:** Claude gives updated file(s) → repo **Add file → Upload files** (replaces old) → **Commit** → wait ~1 min → open site + **hard-refresh** (Ctrl+Shift+R).

---

## 3. Site map (sections top to bottom)

| # | Section | ID / anchor | What's in it |
|---|---------|-------------|--------------|
| 0 | Intro splash | `#intro` | Logo animation video, "Play with sound" + "Skip" |
| 1 | Top nav | `.top` | Logo, "Book for events" (→`#perform`), "Book a class" (→`#book`) |
| 2 | Hero | `#book` | Headline + WhatsApp / Call buttons |
| 3 | Launch teaser | `.launch` | "Launching this November" + live **countdown** `#countdown` |
| 4 | About Ronak | `#about` | Bio + photo + highlights + WhatsApp |
| 5 | Classes offered | `#classes` | Class tiles (piano, harmonium, vocals, Jain, Bollywood, online) |
| 6 | Find your class | `#pgrid`/`#result` | Interactive "pick 3" → recommends a class |
| 7 | Courses on YouTube | `#courses` | Subscribe / Join, right-to-left marquee `#ytgrid` |
| 8 | Perform / events | `#perform` | Services `#svcs`, event card `#event` |
| 9 | Why learn with us | `.stories` | 4 feature cards |
| 10 | What students say | `#reviews` | Testimonials |
| 11 | Classes & fees | `#plans`/`#batches` | In-person / Online / YouTube membership |
| 12 | FAQ | `#faqs` | 5 questions (accordion) |
| 13 | Instagram | `#instagram` | Follow CTA + tiles `#iggrid` |
| 14 | Closing | `.closing` | WhatsApp / Call buttons |
| 15 | Footer | `#fcols` | Links, contact, Instagram, address |
| — | Floating WhatsApp | `.wa-float` | Bottom-left, always visible |
| — | Scroll up | `#scrolltop` | Bottom-right, fades in on scroll |

---

## 4. Files in the repo

| File | Purpose | Notes |
|------|---------|-------|
| `index.html` | The whole website | The main file we edit |
| `logo.png.jpeg` | Nav logo | ⚠️ double extension — HTML points here |
| `favicon.svg` | Browser-tab icon | Red "8" on black |
| `favicon.png.jpeg` | (unused) | Can be deleted |
| `logo-anim.mp4` | Intro animation (3 MB) | Plays in `#intro` |
| `PROJECT-CONTEXT.md` | This file | Keep updated |
| `robots.txt` | SEO — lets Google crawl | **To create** (set-once) |
| `sitemap.xml` | SEO — lists the page | **To create** (set-once) |
| `og-image.jpg` | Social share preview (1200×630) | **To upload** — falls back to logo until then |
| `img/ronak-piano.jpg` | About-section photo | **To upload** — the red piano + mic shot |

---

## 5. Where each piece of content lives in `index.html`

Most content is in **data lists** near the top of the `<script>`. Edit the list, not the layout.

| Content | Where to edit |
|---------|---------------|
| Social share preview | `<meta property="og:...">` tags in `<head>` + `og-image.jpg` |
| Launch date (countdown) | `LAUNCH_DATE` constant |
| Nav logo image | `<img src="...">` in `.top` |
| Intro video | `<video src="logo-anim.mp4">` + `#intro` CSS/JS |
| Hero / About / Closing copy | HTML in those sections |
| About photo | `img/ronak-piano.jpg` in `#about` |
| Classes offered (tiles) | `COURSES` array |
| "Find your class" options | `WANTS` array |
| YouTube links | `CHANNEL_URL`, `MEMBERSHIP_URL`; cards in `YT` array |
| Services | `SERVICES` array |
| Event card(s) | `EVENTS` array |
| Testimonials | `REVIEWS` array |
| Fees / plans | `PLANS` array; chips in `BATCHES` |
| FAQ | `FAQS` array |
| Footer links | `FOOTER` array (`["label","url"]`) |
| Instagram | `IG_PROFILE` + `#iggrid` tiles |
| WhatsApp messages | any element with `data-wa="…message…"` (auto-linked) |
| Phone / address | Footer HTML + JSON-LD (keep in sync) |

---

## 6. File-naming convention (READ before uploading media)

We hit the `logo.png` → **`logo.png.jpeg`** double-extension bug once. Rules:
- **all lowercase**, **hyphens** not spaces, **exactly ONE extension** (check it isn't `.png.jpeg`).
- descriptive + zero-padded numbers: `section-topic-NN.ext`.
- images `.jpg`/`.png`/`.webp`, video `.mp4`.

**Folders:** `/img/` images, `/vid/` videos; root keeps `index.html`, favicon, logo, `.md`, SEO files, `og-image.jpg`.

---

## 7. How to add a new image or video

1. Name per §6. 2. Upload to `img/` or `vid/` → commit. 3. Confirm the exact name in the repo. 4. Tell Claude the section + exact path + caption. 5. Claude updates `index.html` + this file; re-upload and hard-refresh.

---

## 8. Asset Registry

| Filename | Type | Used in | Notes |
|----------|------|---------|-------|
| `logo.png.jpeg` | image | Nav logo | Brand logo |
| `favicon.svg` | image | Browser tab | Red "8" |
| `logo-anim.mp4` | video | Intro splash | 3 MB |
| `img/ronak-piano.jpg` | image | About | **To upload** |
| `og-image.jpg` | image | Social share | **To upload** (1200×630) |
| _add new rows below_ | | | |

---

## 9. Current content — real vs placeholder

**Real:** name, Ronak (trained in Mumbai), phone, VV Puram, Instagram handles, YouTube; teaches piano/harmonium/vocals one-on-one, age 10+, in person + online; 100+ Jain songs/stavans, Bollywood, classical vocals; ₹49/mo membership; devotional services; Tapasya Bhakthi event; Nov launch.

**Placeholder (replace):** testimonials (`REVIEWS` — names are "[ Your student's name ]"), fees ("On enquiry"), launch date (1 Nov placeholder), YouTube course cards, Instagram tiles (link to profile, not live posts).

---

## 10. To-Do / open questions

**Resolved so far:** ✅ harmonium ✅ age 10+ ✅ real class list ✅ About Ronak ✅ online 1-on-1 ✅ Instagram links ✅ WhatsApp/Call buttons (context-aware) ✅ scroll-up ✅ YouTube marquee (right-to-left) ✅ 5 FAQs ✅ floating WhatsApp ✅ launch countdown ✅ social-share meta tags ✅ testimonials section ✅ Instagram section ✅ removed fake teachers / Trinity-ABRSM / fake price / fake hours.

Still open:
- [ ] **Upload `img/hero-bg.jpg`** — the hero background image (poster-collage style). Hero is already wired for it; until uploaded, the gradient mosaic shows behind.
- [ ] **PERF (biggest win): compress `logo-anim.mp4`** — 3 MB is ~95% of page weight. Re-encode to <~800 KB, 720p, ~2–3s (HandBrake or an online compressor), re-upload same name.
- [ ] **PERF: resize/compress `logo.png.jpeg`** — it displays at 60px but is likely a full-size export. Export at ~180px tall, compressed.
- [ ] **SECURITY: confirm "Enforce HTTPS"** in repo Settings → Pages (should already be on for *.github.io).
- [ ] **SECURITY (needs custom domain + Cloudflare): send real HTTP security headers** — `X-Frame-Options: DENY` (clickjacking), `X-Content-Type-Options: nosniff`, `Strict-Transport-Security` (HSTS), and the CSP as a header. GitHub Pages can't send these; Cloudflare free tier can.
- [ ] **SECURITY: add honeypot + submit-timing** only if/when a real contact form is added (none exists now).
- [ ] **Set the real `LAUNCH_DATE`** (currently 1 Nov 2026 placeholder).
- [ ] **Replace placeholder testimonials** in `REVIEWS` with real student quotes + names.
- [ ] **Upload `og-image.jpg`** (1200×630) for a sharp link preview.
- [ ] **Upload `img/ronak-piano.jpg`** for the About photo.
- [ ] **Create `robots.txt` + `sitemap.xml`** (code provided) for Google.
- [ ] **Instagram live feed** — send 3–6 post links to embed, or set up a free widget (SnapWidget/LightWidget) and send the embed code.
- [ ] **Real fees** (currently "On enquiry").
- [ ] **Event** — Tapasya Bhakthi (Sept 20) is past; replace/remove.
- [ ] **YouTube course cards** — real titles + links + Free/Members.
- [ ] `favicon.png.jpeg` — unused; delete whenever.

---

## 11. Change log

1. Started from a dark-theme template ("Saptak School of Music").
2. Nav → logo image; SVG favicon.
3. Renamed to **The 8th Note** everywhere.
4. Real contact + address.
5. Added devotional/performance side.
6. "Launching this November" teaser.
7. Courses on YouTube (free + ₹49 members).
8. FAQs.
9. Delivered `favicon.svg`, `logo-anim.html`, optional `logo.svg`.
10. Fixed double-extension logo bug.
11. Intro splash + "Play with sound".
12. Wrote this context file.
13. Agreed the both-files-together working routine.
14. Big content pass from posters: harmonium, About Ronak, real class list, age 10+, Instagram, reworked fees, removed template fiction.
15. WhatsApp/Call buttons with context-aware pre-filled messages; scroll-up button.
16. FAQ → 5 best; YouTube → right-to-left infinite marquee.
17. **Added:** floating WhatsApp button, **launch countdown**, social-share meta tags (+ `og-image.jpg` slot), **testimonials** section (placeholder), **Instagram** section, and SEO files `robots.txt` + `sitemap.xml`.
18. **Performance pass (no visual/behaviour change):** made Google Fonts non-render-blocking (preload + async swap + `<noscript>`); added `decoding="async"` + `fetchpriority="high"` on the logo; removed one dead CSS rule. Confirmed the site is already lean — no JS libraries/frameworks, inline CSS/JS (already "bundled"), JS non-blocking at end of body, gradients instead of content images. **The dominant remaining weight is `logo-anim.mp4` (3 MB) — must be compressed (asset step), see To-Do.**
19. **Security hardening (code):** added a **Content-Security-Policy** meta tag (allows self + fonts.googleapis.com + fonts.gstatic.com only; keeps `'unsafe-inline'` because JS/CSS/JSON-LD are inline) and a **referrer policy** meta (`strict-origin-when-cross-origin`). Confirmed `rel="noopener"` is already on all external links. Note: clickjacking (`X-Frame-Options`/`frame-ancestors`), `X-Content-Type-Options`, and HSTS are **header-only** — they need Cloudflare (host step). No form exists, so honeypot/anti-spam is N/A until a real form is added.
20. **SEO pass (code):** tightened meta description to ~150 chars; added **FAQPage** JSON-LD (mirrors the 5 visible FAQs — keep in sync if FAQ text changes); wrapped content in a `<main>` landmark. Confirmed title, canonical, OG/Twitter, `MusicSchool`+Person JSON-LD, `lang`, alt/aria were already in place. **Did NOT split #-anchors into separate pages** (they're scroll anchors, not routes — splitting = thin content). `robots.txt` note: ignored on a `/the8thnote/` subpath; works properly only on a custom domain at root.
21. Restyled the **"Why learn with The 8th Note"** cards (`.stories`) to match a **Netflix-style** reference: single row of 4 tall cards, deep navy→purple gradient (brighter top), white bold heading, muted-grey body, and a **glossy glowing icon in the bottom-right** (piano, musical note, play, globe). Replaced the old flat glyphs (removed `.keys/.wave/.metro/.cert` CSS and the `#wave` JS). Content is the real music-class points. (→ 2-across tablet → 1 phone.)
22. **Major restructure (Netflix-style):** added a **hamburger menu** (`#hamb` → `#menu`) with 4 swappable panels — **Find your class, Services (Classes rail + Perform), About Us (Meet Ronak), Contact Us**. **Moved these off the main page into the menu**, leaving a lean landing page. Netflix-style **hero**: single **gradient "Book a class"** button that opens the menu, logo top-left, and a **background-image slot** (`img/hero-bg.jpg`, supplied later). Added wider **side margins** (`--gutter` 48px, 20px mobile). **Moved "What students say" to below "Classes & fees."** Gradient (`--grad`) used on primary CTAs.

---

## 12. Handy facts

- The site is **one file** (`index.html`); `robots.txt`/`sitemap.xml` are set-once.
- Browsers **mute** auto-playing video; sound needs a click.
- A **live Instagram feed** needs post links or a third-party widget — a static page can't pull it alone.
- GitHub is **case-sensitive** and keeps whatever extension you upload — verify names.
- After any upload, **hard-refresh**.
