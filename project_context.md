# The 8th Note — Website Project Context

> **How to use this file:** Keep it in the repo as `PROJECT-CONTEXT.md`. When you start a new chat with Claude, upload this file first and say "here's the context." It captures the business, the hosting setup, the site structure, the file-naming rules, and everything still left to do. Keep it updated as the site grows (especially the **Asset Registry** and **To-Do** sections).

> **Working agreement:** After **every** change, Claude updates **both** files in the same step — `index.html` (the website) and this `PROJECT-CONTEXT.md` (change log, to-do, asset registry) — so they always match. Only these two living files are maintained; no extra files are spun up. Claude always says exactly which file(s) to re-upload.

_Last updated: 2 Oct 2026_

---

## 1. Business snapshot

- **Name:** The 8th Note
- **Person:** Ronak Patiyat — keyboardist & singer, trained at a leading Mumbai music institute.
- **Location:** VV Puram, Bengaluru (also teaches live online).
- **Phone / WhatsApp:** +91 94800 61108
- **Instagram:** business **@the8thnote__** · personal **@ronakpatiyat__**
- **YouTube:** https://youtube.com/@ronakpatiyat (membership = `/join`)
- **What the business does (three sides):**
  1. **Teaching (one-on-one)** — **piano, harmonium & vocals**, basic to advanced. Includes 100+ Jain songs on piano, 100+ Jain stavans in voice, Bollywood piano, and a classical vocal foundation (sur & taal). **Students 10 years & above.** In person (VV Puram) or **live online 1-on-1**.
  2. **Performing** — devotional / Bhakti singing for Jain programs, Bhakthi Sandhya, poojas, paths and religious events.
  3. **Online courses** — YouTube: some free, full courses members-only at **₹49/month**.
- **Coming up:** "something big" launching in **November** (details TBD).
- **Brand look:** black background, one red accent (`#E50914`), white text. Font: Archivo.

---

## 2. Hosting & how to publish a change

- **Repo:** https://github.com/ronakpatiyat-maker/the8thnote
- **Live site:** https://ronakpatiyat-maker.github.io/the8thnote/
- **Host:** GitHub Pages (Settings → Pages → Deploy from a branch → `main` → `/root`).

**The update loop (every change):**
1. Claude gives you an updated `index.html` (and this file when it changes).
2. In the repo: **Add file → Upload files →** drag it in (replaces the old one) **→ Commit changes**.
3. Wait ~1 minute.
4. Open the site and **hard-refresh** (Ctrl+Shift+R / Cmd+Shift+R) to clear the cache.

---

## 3. Site map (sections top to bottom)

| # | Section | ID / anchor | What's in it |
|---|---------|-------------|--------------|
| 0 | Intro splash | `#intro` | Logo animation video, "Play with sound" + "Skip" |
| 1 | Top nav | `.top` | Logo, "Book for events" (→`#perform`), "Book a class" (→`#book`) |
| 2 | Hero | `#book` (form) | "Piano, harmonium & vocals — with Ronak Patiyat" + phone capture |
| 3 | Launch teaser | `.launch` | "Launching this November" |
| 4 | About Ronak | `#about` | Bio + photo + highlights + WhatsApp button |
| 5 | Classes offered | `#classes` | Scrollable class tiles (piano, harmonium, vocals, Jain, Bollywood, online) |
| 6 | Find your class | `#pgrid`/`#result` | Interactive "pick 3" tool → recommends a class |
| 7 | Courses on YouTube | `#courses` | Subscribe / Join buttons, infinite left-to-right marquee of course cards `#ytgrid` |
| 8 | Perform / events | `#perform` | Services `#svcs`, event card `#event`, WhatsApp CTA |
| 9 | Why learn with us | `.stories` | 4 feature cards |
| 10 | Classes & fees | `#plans`/`#batches` | In-person / Online / YouTube membership |
| 11 | FAQ | `#faqs` | 5 questions (accordion) |
| 12 | Closing | `.closing` | Final "book a class" form |
| 13 | Footer | `#fcols` | Link columns, contact, Instagram, address |

---

## 4. Files currently in the repo

| File | Purpose | Notes |
|------|---------|-------|
| `index.html` | The whole website | The only file we edit for content/layout |
| `logo.png.jpeg` | Nav logo image | ⚠️ double extension — HTML points here |
| `favicon.svg` | Browser-tab icon | Red "8" on black |
| `favicon.png.jpeg` | (unused) | Can be deleted; favicon runs off the SVG |
| `logo-anim.mp4` | Intro animation (3 MB) | Plays in `#intro` splash |
| `PROJECT-CONTEXT.md` | This file | Keep updated |
| `img/ronak-piano.jpg` | **To upload** | Photo for the About section (the red piano + mic shot) |

---

## 5. Where each piece of content lives in `index.html`

Most content is in **data lists (arrays)** near the top of the `<script>`. Edit the list, not the layout.

| Content | Where to edit |
|---------|---------------|
| Nav logo image | `<img src="...">` inside `.top` |
| Intro video | `<video src="logo-anim.mp4">` + `#intro` CSS/JS |
| Hero headline / subline | HTML inside `.hero` |
| Launch teaser text | HTML inside `.launch` |
| About Ronak (bio, photo, bullets) | HTML inside `#about` (photo = `img/ronak-piano.jpg`) |
| Classes offered (tiles) | `COURSES` array |
| "Find your class" options | `WANTS` array |
| YouTube Subscribe / Join links | `CHANNEL_URL`, `MEMBERSHIP_URL` |
| YouTube course cards | `YT` array (`free: true/false`, each `url`) |
| Services ("What I bring") | `SERVICES` array |
| Event card(s) | `EVENTS` array |
| Fees / plans | `PLANS` array; chips in `BATCHES` |
| FAQ | `FAQS` array |
| Footer link columns | `FOOTER` array — each item is `["label","url"]` |
| Phone / address / Instagram | Footer HTML **and** the JSON-LD block (keep in sync) |

---

## 6. File-naming convention (READ before uploading media)

We hit the `logo.png` → **`logo.png.jpeg`** double-extension bug once. To avoid it forever:

- **all lowercase**
- **hyphens** between words, **never spaces**
- **exactly ONE extension** — check it isn't `.png.jpeg` or `.mp4.mp4` before committing
- **descriptive + numbered:** `section-topic-NN.ext` with zero-padded numbers (`01`, `02`, …)
- images: `.jpg` / `.png` / `.webp` · video: `.mp4`

**Folders going forward:**
```
/        → index.html, favicon.svg, logo files, this .md
/img/    → all images   (e.g. img/gallery-01.jpg)
/vid/    → all videos   (e.g. vid/performance-01.mp4)
```

**Examples:** `img/ronak-piano.jpg` · `img/event-tapasya-01.jpg` · `img/gallery-01.jpg` · `vid/performance-01.mp4`

---

## 7. How to add a new image or video

1. **Name the file** per §6 (lowercase, hyphens, one extension).
2. **Upload** to `img/` or `vid/` → Commit.
3. **Confirm the exact name** in the repo (watch for double extensions).
4. **Tell Claude:** which section + exact path + caption.
5. Claude updates `index.html` + this file; you re-upload them and hard-refresh.

> Many sections are data-driven, so adding one item = **one new line + one uploaded file**.

---

## 8. Asset Registry (keep this updated)

| Filename | Type | Used in | Caption / notes |
|----------|------|---------|-----------------|
| `logo.png.jpeg` | image | Nav logo | Brand logo |
| `favicon.svg` | image | Browser tab | Red "8" on black |
| `logo-anim.mp4` | video | Intro splash | 3 MB, plays on load |
| `img/ronak-piano.jpg` | image | About section | **To upload** — the red piano + mic photo |
| _add new rows below_ | | | |

---

## 9. Current content — real vs placeholder

**Confirmed real (from posters & messages):**
- Name, person (Ronak Patiyat), trained at a leading Mumbai institute.
- Phone/WhatsApp +91 94800 61108; VV Puram, Bengaluru; Instagram @the8thnote__ and @ronakpatiyat__; YouTube @ronakpatiyat.
- Teaches **piano, harmonium, vocals**, one-on-one, **age 10+**, in person **and** online.
- Repertoire: 100+ Jain songs (piano), 100+ Jain stavans (voice), Bollywood piano, classical vocals (sur & taal).
- YouTube membership: ₹49/month.
- Devotional services + event: Tapasya Bhakthi, Sri S.S. Jain Sangh, Xaviers Layout.
- Launch: something new in November.

**Still to confirm / fill in:** see To-Do.

---

## 10. To-Do / open questions

**Resolved this round:** ✅ added harmonium ✅ age set to 10+ ✅ real class list ✅ Ronak bio/About section ✅ online 1-on-1 ✅ Instagram links ✅ removed fake teachers, Trinity/ABRSM exams, invented ₹2,400 price & "free first class", fake hours ✅ forms replaced with WhatsApp/Call buttons (context-aware messages) ✅ scroll-up button added.

Still open:
- [ ] **Fees** — shown as "On enquiry" (no real numbers given). Send actual in-person & online fees to display them, or keep "on enquiry."
- [ ] **Upload** `img/ronak-piano.jpg` so the About photo appears (section already wired for it).
- [ ] **Event date** — Tapasya Bhakthi (Sept 20) is in the past. Replace with the next event, make it a list, or remove.
- [ ] **November launch** — replace the vague teaser with the real announcement when ready.
- [ ] **YouTube course cards** — 6 sample titles; links fall back to channel/join until real video links are added. Send real titles + links + Free/Members.
- [ ] **Hours** — currently "by appointment." Set specific hours if you want them shown.
- [ ] **Optional:** upload the posters (classes / online / launch) as images if you want them shown as graphics too.
- [ ] `favicon.png.jpeg` — unused; delete whenever.

---

## 11. Change log

1. Started from a dark-theme template ("Saptak School of Music").
2. Nav text → **logo image**; added **SVG favicon**.
3. Renamed business to **The 8th Note** everywhere.
4. Real **contact** (Ronak, +91 94800 61108) and **address** (VV Puram).
5. Added the **devotional/performance** side (services, event, WhatsApp).
6. Added **"Launching this November"** teaser.
7. Added **Courses on YouTube** (free + ₹49 members), wired to the real channel.
8. Added FAQs.
9. Delivered `favicon.svg`, `logo-anim.html`, optional `logo.svg`.
10. Fixed the double-extension logo bug (`logo.png` → `logo.png.jpeg`).
11. Added the **intro splash** playing `logo-anim.mp4`, with "Play with sound" + "Skip".
12. Wrote this context file.
13. Agreed the **working routine**: both files updated together after every change.
14. **Big content pass from the real posters:** added **harmonium**; replaced fake teachers with an **About Ronak** section; replaced the course catalogue with the **real class list** (Jain songs/stavans, Bollywood piano, classical vocals, online 1-on-1); set **age 10+**; added **Instagram** links; reworked **fees** to in-person / online / YouTube membership; refreshed **FAQ** (now 10); removed Trinity/ABRSM, the invented ₹2,400 price, "free first class" and fake hours.
15. **Contact + polish:** replaced the dead lead-capture forms with **Message on WhatsApp / Call now** buttons; every "reach out" button now opens WhatsApp with a **context-specific pre-filled message** (book a class, ask about a specific class, fees for a specific plan, book for an event, ask about the Tapasya Bhakthi show). Added a **"Scroll up"** button (vertical text + arrow, right edge, fades in on scroll).
16. Trimmed **FAQ to the 5 best**; made **Courses on YouTube** an **infinite left-to-right marquee** (single line, pauses on hover, cards duplicated for a seamless loop).

---

## 12. Handy facts for future chats

- The site is **one file** (`index.html`).
- Browsers **mute** auto-playing video; sound needs a click. Not fixable.
- GitHub is **case-sensitive** and keeps whatever extension the upload has — verify names after uploading.
- After any upload, **hard-refresh** to beat the cache.
