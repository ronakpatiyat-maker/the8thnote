# The 8th Note — Website Project Context

> **What this file is for:** (1) the full project record for Claude — upload it with `music.html` (and `index.html` if the main site is changing) at the start of any new chat and say "here's the context"; (2) Ronak's own reference — §0 lists every section that has been built and where to find it.

> **Ronak's rule (27 Oct):** keep everything in the HTML file. No zip files, no separate .js files. Claude delivers `music.html` (and `index.html` when the main site changes) as single files to upload. All songs, contexts, sets, stutis, anchoring lines **and the lyric images** are inside `music.html`.

> **Nothing gets lost:** `music.html` is the master copy of the songbook — every song, context, stuti, anchoring line and lyric image is inside it. Keep the latest one on GitHub and a copy on your phone/laptop. In a new chat, give Claude that `music.html` + this file; Claude takes everything back out of it before making changes.

> **Working agreement:** After **every** change, Claude updates the changed file (`music.html` and/or `index.html`) **and** this `project_context.md` in the same step, so they always match. Claude always says exactly which file(s) to upload and which to delete.

_Last updated: 7 Nov 2026 — songbook: 195 songs · 32 contexts (Navkar + C1–C32, no C19) · 18 stutis · 2 anchoring topics · 8 lyrics images · PIN 2006_

---

## 0. Quick reference — what has been built (for Ronak)

**Main website — `index.html`** · https://the8thnote.in (domain bought 7 Nov from GoDaddy; old address https://ronakpatiyat-maker.github.io/the8thnote/ forwards to it once connected)
| Part | What it does |
|---|---|
| Intro splash | Logo animation once per visit, with sound button |
| Top menu | About us · Services · logo · **Events** · Contact us — each opens a full-screen panel |
| Music panel (private) | Opened only from the **round ♪ button** at bottom-left (above the bell and WhatsApp) — not in the menu. Starts with the **Songbook** card: type PIN 2006 → opens the songbook. Below: "Coming soon" + countdown, Instagram / YouTube buttons |
| Services panel | **LEARN WITH THE8THNOTE** · *Classes we offer* (YouTube teaser panel + equal course cards with *View more*) · contact form (*Let's bring your vision into reality*) → WhatsApp |
| Events panel | *Looking for a singer with devotion & passion?* (red) · *Book The 8th Note for your Bhakthi event*: photo, 4 event types, quote line, event card, *Enquire on WhatsApp* |
| About / Contact panels | Bio and photo; phone, WhatsApp, Instagram, address + map |
| Home page | Hero, YouTube courses, Why learn with us, Instagram reels, testimonials (sample), FAQ, footer |
| Floating buttons | Bottom-left, top to bottom: **♪ Music** (private songbook), launch bell, WhatsApp; scroll-to-top on the right |

**Songbook — `music.html`** · https://the8thnote.in/music.html · **PIN 2006** · reached from the website's Music panel (PIN) or this link
| Part | Where | What it does | Now |
|---|---|---|---|
| PIN screen | opens first | 4-digit keypad; 🔒 in the top bar locks again | PIN 2006 |
| Context panel | left side; 📖 book button bottom-left opens/closes it | One list: All songs · Stuti · Navkar · Anchoring (+ topics) · then C1 General Bhakthi → C32 Aarti in number order (table below) | 32 contexts |
| All songs | panel, first item | Every song by serial number | 195 songs |
| Stuti | panel | 18 boxes, drag or ↑/↓ to set your order, tick *Sing*, ▶ Start = full screen white on black | 16 with text, 2 waiting |
| Navkar | panel | Navkar songs | no list yet (1 suggested) |
| Anchoring | panel | Your lines to speak between songs; topics show as titles, tap to open. A topic linked to a song also shows on top of that song | Aadi sparsh, Tirth Raksha |
| Contexts | panel | Your list in your order → *Suggested — to review* → *General Bhakthi — also fits* | see §12 |
| Aarti | panel, last | Jay Jay Aarti, Mangal Divo (text), Gurudev Aarti (waiting) | 3 |
| Songs tab | top bar | Song list, search, Scale filter, + General Bhakthi switch | — |
| Index tab | top bar | All songs 1–9, A–Z or by context, with each song's contexts | — |
| Song view | tap a song | Your lyrics image (or typed text), key/tempo/notes, A−/A+ zoom, swipe to next, screen stays on | 8 images, 6 typed |
| Setlist | top-right button | Add songs, reorder, name the event, 13 ready-made sets, share on WhatsApp, *Begin with stuti* | saved on that device |
| Direct links | — | `music.html?song=12` opens song 12 · `?tab=stuti` · `?tab=anchor` · `?tab=index` | — |

**Context numbers** — use these instead of typing the name (e.g. "add 180 to C23"). Set by Ronak on 7 Nov; the panel shows the contexts in this order. Navkar has no number (it sits with Stuti and Anchoring at the top). C19 is empty (Palitana 5 Chaityavandan was removed on 7 Nov) — the other numbers did not move. A new context gets the next number (C33 …), placed before Aarti.
| | | | | | | | |
|---|---|---|---|---|---|---|---|
| C1 General Bhakthi | C2 Slow Mashup | C3 Adinath Bhagwan | C4 Neminath Bhagwan | C5 Fast Dance Number | C6 Bhaav Bhakthi | C7 Tapasya Bhakthi | C8 Gujarati Songs |
| C9 Marvadi Songs | C10 All Pooja | C11 Chetya Vandan Stavan | C12 Classical Songs | C13 Diksha | C14 Girnar | C15 Grah Pravesh | C16 Mahaveer Swamy Bhagwan |
| C17 Nakoda Bherav | C18 Palitana | C19 — (removed 7 Nov) | C20 Parshwanath Bhagwan | C21 Prachin Stavan | C22 Pratishta / Dhwaja | C23 Rajendra Suriji | C24 Rishto ki Dor |
| C25 Sahebji | C26 Sangh | C27 Sankeshwar | C28 Shanti Suriji | C29 Shantinath Bhagwan | C30 Utsah Songs | C31 Simandhar Swamy Bhagwan | C32 Aarti |

> Change-log entries 90–97 (6–7 Nov) use the **old** numbers (old C1 = Navkar, C2 = Adinath … C33 = Simandhar). The lists themselves are correct; only the labels changed.

**Rules that apply everywhere in the songbook**
- **Ronak's rule (7 Nov, website):** the courses Ronak sends are kept up to date in **Services → Classes & fees** (posters `COURSES`, fee cards `PLANS`); old courses he drops are removed.
- **Ronak's rule (7 Nov):** whenever a song is added to any context, Claude also adds it to **C1 General Bhakthi** — unless Ronak says that song should not go there.
- Song numbers never change; new songs get the next number (next = 196).
- General Bhakthi (#4, #5, #6, #10, #14, #18, #19, #36, #39, #54, #92, #93, #96, #99, #180) shows under every context **except** Navkar, Chetya Vandan Stavan, Diksha, Grah Pravesh, Prachin Stavan, Rishto ki Dor, Sahebji, Tapasya Bhakthi, Aarti. #6 never shows under Bhaav Bhakthi.
- Lyrics come only as your images (white-on-black template, one per song, with the song number). Typed text only for old stavans, stutis, aartis and anchoring.
- Things saved only on one device: setlist, stuti order and ticks, zoom size, last tab. Everything else is inside `music.html`.

**Last check (3 Nov; repo reviewed 5 Nov):** 194 songs, numbers 1–194 with no gaps or repeats; all 32 contexts point only to real songs; all 13 sets valid; all 8 lyrics images built in; 18 stutis; 2 anchoring topics; PIN 2006. Nothing missing.

---

## 1. Business snapshot

- **Name:** The 8th Note
- **Person:** Ronak Patiyat — keyboardist & singer, trained at a leading Mumbai music institute.
- **Location:** VV Puram, Bengaluru (also teaches live online). Map pin: "Aagam Esturi".
- **Phone / WhatsApp:** +91 94800 61108
- **Instagram:** business **@the8thnote__** · personal **@ronakpatiyat__**
- **YouTube:** https://youtube.com/@ronakpatiyat (membership = `/join`)
- **Three sides:**
  1. **Teaching (one-on-one)** — piano, harmonium & vocals, basic to advanced. 100+ Jain songs on piano, 100+ Jain stavans in voice, Bollywood piano, classical vocal foundation (sur & taal). **Students 10 & above.** In person (VV Puram) or live online.
  2. **Performing** — devotional / Bhakti singing for Jain programs, Bhakthi Sandhya, poojas, paths, religious events.
  3. **Online courses** — YouTube: free + members-only at **₹49/month**.
- **Coming up:** music launch in **November** — live countdown in the Music panel and the bell popup.
- **Brand look (7 Nov): only red, black and white.** Black background, red accent (`#E50914`), deep-red→red gradient (`--grad`: #7A0109 → #B20710 → #E50914) on primary buttons, white text. No purple, pink, blue, green or gold anywhere in the design (only exception: the WhatsApp button keeps WhatsApp green). Photos keep their own colours. Font: Archivo (Events panel also uses Anton for SINGER / banners and Great Vibes script for *With Devotion & Passion* and *Patiyat*, as on the poster).

---

## 2. Hosting & how to publish a change

- **Repo:** https://github.com/ronakpatiyat-maker/the8thnote
- **Live site:** https://ronakpatiyat-maker.github.io/the8thnote/
- **Host:** GitHub Pages (Settings → Pages → Deploy from a branch → `main` → `/root`).

**Update loop:** Claude gives updated file(s) → repo **Add file → Upload files** (files going into `img/`: open the `img` folder first, then upload) → **Commit** → wait ~1 min → open site + **hard-refresh** (Ctrl+Shift+R).
**Deleting a file:** open it in the repo → **⋯ menu → Delete file** → Commit.

---

## 3. Site structure

### Top navigation (`.top`)
`[ About us · Services ]  LOGO  [ Events · Contact us ]` — each link opens the **menu overlay**. Logo = home (scroll to top). On phones it becomes two rows (logo, then links).

### Menu overlay (`#menu`) — 4 panels
| Panel | ID | Contents |
|-------|----|----------|
| Music (private) | `#panel-music`, opened by `.music-float` (♪, bottom-left) | **Songbook card first** (PIN box → opens `music.html` already unlocked), then "Coming soon", 8-bar scale graphic, countdown, Instagram/YouTube buttons |
| Services | `#panel-services` | Only **Classes & fees** (tab bar removed 8 Nov): YouTube teaser panel + course cards from `CLASS_LIST` in `#panel-fees`, detail view `#crsD` |
| Events | `#panel-events` | Moved out of Services on 8 Nov: heading, photo, `#svcs` (4 event types), quote line, `#event` card, *Enquire on WhatsApp* |
| About | `#panel-about` | Meet Ronak (photo + bio + highlights), Our story, What you can learn (`#pillars`), Book/Contact buttons |
| Contact us | `#panel-contact` | Phone, WhatsApp, Instagram, address pills + Google Map |

Any element with `data-open="music|services|classes|find|fees|events|about|contact"` opens that panel/tab.

### Songbook page (`music.html` — one self-contained file)
Ronak's **personal page for events**, locked with **PIN 2006** (change it in the `PIN` line near the top of `music.html`; stays unlocked until the tab closes or 🔒 is tapped). No explanatory text. Not indexed by Google (`noindex`), not in the sitemap. Opened from the website's **Music panel** (Songbook card asks for the PIN, then opens it unlocked) or by its link. Anyone with the link who reads the page source can see the PIN and the lyric images — it keeps casual visitors out, it is not real privacy.

**One file:** songs, contexts, stutis, lyric images, logo and icon are all built into `music.html`. Upload only that file (next to `index.html`). Opens at `ronakpatiyat-maker.github.io/the8thnote/music.html`. Claude edits `songs.js` / `contexts.js` / `stuti.js` / `anchor.js` and builds them in (one build script; `music.html` is what you upload).

**How the data is organised:**
1. Every song has a permanent **serial number** (1–195). New songs get the next number; numbers never change.
2. **Scale (Sa)** is the first filter (`scale`, e.g. `["F","E"]`; Ronak's exact chart note in `key`). Few songs have one yet.
3. **Contexts** = lists of serial numbers (CONTEXTS block). Each has a number **C1–C32** (`no`, Navkar has none), shown in the panel next to its name and in the list header; the panel is sorted by it. A song can be in many. `songs` = Ronak's list, in his order; `suggest` = Claude's suggestions, shown under *Suggested — to review*; `exclude` = never show this song here; `noGeneral` = don't show General Bhakthi here; `pin:"first"/"last"` and `after:"X"` set the panel position. Full list in §12.
4. **General Bhakthi** = Ronak's 15 songs (#6, #14, #92, #4, #39, #5, #18, #54, #19, #10, #180, #99, #93, #96, #36). They show under every context as *General Bhakthi — also fits* (switch *+ General Bhakthi*), except in the contexts listed in §12.
5. **Lyrics** come only as Ronak's images (white-on-black template, one per song, shown as-is, `img/songs/song-NNN.jpg` built in). Typed text only for old stavans (#27, #96, #97, #98) and aartis (#192, #193).
6. Titles are in Devanagari with the English name underneath; search works in both. Bhagwan names are one (Aadinath = Rushabhdev / Rushabhji / Aadeshwar / Dada etc., `ALIASES` in `music.html`).

**Screen:**
- **Left context panel**, always there on every tab, one continuous list: All songs · ॐ Stuti · नमो Navkar · 🎤 Anchoring (+ its topics) · C1 General Bhakthi · C2 Slow Mashup · C3 Adinath Bhagwan … C31 Simandhar Swamy Bhagwan · C32 Aarti (diya icon).
- **Songs** tab: one song per line (number · title · English name · scale · +). Filter row: Scale · + General Bhakthi · Clear. Search.
- **Index** tab: by number, A–Z or by context; each song shows its contexts. Every song has its own link: `music.html?song=12`.
- **Song view**: lyrics image or typed text (refrain lines in red), key / tempo / notes, zoom A−/A+, previous / next, swipe, keeps the screen awake.
- **Setlist** (saved on that device): add, reorder, name the event, ready-made sets, send on WhatsApp, *Begin with stuti*.
- **Anchoring** (🎤, in the panel after Navkar; data in the ANCHOR block, `anchor.js` when building): Ronak's own lines to speak between songs. Topics are listed by title only (also as sub-items under *Anchoring* in the panel); tap a topic to open its lines, tap again to close. A line can name the song it leads into (`song: 12`) — then it also shows in an orange box on top of that song, and its box has a button to open the song. Link: `music.html?tab=anchor`.
- **Stuti**: 18 boxes in one column, drag ⠿ or ↑/↓ to reorder (saved on that device; *Reset order*). *Start* plays them full-screen, white on black. 2 still *Text to come* (Jain gunona sindhuna, Pal pal mere har rom mein) and are skipped.

### Main page (top to bottom)
| # | Section | ID | What's in it |
|---|---------|----|--------------|
| 0 | Intro splash | `#intro` | Logo animation, "Play with sound" + "Skip". Shows once per browser session |
| 1 | Hero | `.hero` | Background `img/hero-bg.jpg`, headline, value line, "Book a class" (→ Classes & fees) |
| 2 | Courses on YouTube | `#courses` | Subscribe / Join, right-to-left marquee `#ytgrid` |
| 3 | Why learn with us | `.stories` | 4 Netflix-style cards |
| 4 | Instagram | `#instagram` | Real Instagram reel embeds (`REELS`) in a scroll row `#reel-track` |
| 5 | What students say | `#reviews` | 5-card marquee (**sample** quotes) |
| 6 | FAQ | `#faqs` | 5 questions; each answer has a button into the menu |
| 7 | Closing | `.closing` | Book a class + Call now |
| 8 | Footer | `footer` | Socials · nav · contact, divider, bottom line |
| — | Floating WhatsApp | `.wa-float` | Bottom-left |
| — | Launch bell | `#notifBtn` → `#notifPop` | Above WhatsApp; popup with countdown |
| — | Scroll up | `#scrolltop` | Bottom-right, appears after scrolling |

---

## 4. Files in the repo

| File | Purpose | Notes |
|------|---------|-------|
| `index.html` | The whole website | Main file we edit |
| `project_context.md` | This file | Keep updated |
| `logo.png.jpeg` | Nav + menu logo | ⚠️ double extension, but HTML points here — leave it |
| `favicon.svg` | Browser-tab icon | Red "8" |
| `logo-anim.mp4` | Intro animation | Compressed 27 Oct: 2.8 MB → 0.24 MB |
| `og-image.jpg` | Link preview (1200×630) | Made 27 Oct from the hero poster |
| `music.html` | **The whole songbook in one file** — page + songs + contexts + sets + stutis + anchoring + Ronak's lyrics images (~1.8 MB) | Re-uploaded after every songbook change |
| `robots.txt`, `sitemap.xml` | SEO | Set-once |
| `img/hero-bg.jpg` | Hero background | Made 27 Oct from `hero-bg.png` |
| `img/events-stage.png` | Source of the Events stage photo | Built into `index.html` since 8 Nov (no upload needed) |
| `img/events-poster.jpg` | Not shown (removed 8 Nov) | Ronak's "Looking for a singer" poster, 1024×1536 (8 Nov) |
| `img/about-ronak-01.jpeg` | Old events photo | No longer shown since 8 Nov (kept for now) |
| `img/about-ronak-02.jpeg` | About photo | |
| `img/class-01 … 08.jpeg` | Class posters | In `COURSES` order |

**To delete from the repo (checked 5 Nov — unused duplicates, nothing points to them):** root `about-ronak-01.jpeg`, root `about-ronak-02.jpeg`, root `class-01.jpeg`, root `class-02.jpeg`, root `class-03.jpeg`, root `hero-bg.png`, `favicon.png.jpeg`, and `img/about-ronak-02` (empty file, no extension). Never upload `songs.js`, `contexts.js`, `stuti.js`, `anchor.js` or `img/songs/` — they are inside `music.html`.

---

## 5. Where each piece of content lives (`index.html` and `music.html`)

Most content is in **data lists** near the top of the main `<script>`. Edit the list, not the layout.

| Content | Where to edit |
|---------|---------------|
| Social share preview | `<meta property="og:…">` / `twitter:` tags + `og-image.jpg` |
| Launch date (countdown) | `LAUNCH_DATE` constant |
| Hero background | `.hero-bg` CSS → `img/hero-bg.jpg` |
| Hero / About / Closing copy | HTML in those sections |
| About photo | `img/about-ronak-02.jpeg` in `#panel-about` |
| Events photo | `img/about-ronak-01.jpeg` in the "For events" tab |
| Class posters | `COURSES` array (`img:` field) |
| About "What you can learn" | `PILLARS` array (`STEPS` is defined but not currently shown) |
| YouTube | `CHANNEL_URL`, `MEMBERSHIP_URL`; cards in `YT` |
| Event services | `SERVICES` array |
| Event card(s) | `EVENTS` array |
| Testimonials | `REVIEWS` array |
| Fees | `PLANS` array; chips in `BATCHES` |
| FAQ | `FAQS` array **and** the FAQPage JSON-LD in `<head>`-area script (keep in sync) |
| Instagram | `REELS` array (reel URLs) |
| WhatsApp messages | any element with `data-wa="…message…"` |
| Phone / address | Footer, Contact panel, JSON-LD (keep in sync) |
| **Songs** | `music.html` → block *SONG LIBRARY + SETS* (`SONGS`, `SETS`) |
| **Contexts** | `music.html` → block *CONTEXTS* (`CONTEXT_GROUPS`, `CONTEXTS`) |
| **Stuti** | `music.html` → block *STUTI* (`STUTI_GROUPS`, `STUTI`) |
| **Anchoring** | `music.html` → block *ANCHORING LINES* (`ANCHOR`: `id`, `title`, optional `song`, `text`; a line starting `> ` is highlighted) |
| Lyric pictures | `music.html` → block *LYRIC PAGE PICTURES* (`IMGS`, built in — Claude rebuilds it) |
| Context position | `music.html` → CONTEXTS: `no` sets the order (C1, C2 …); `pin:"first"` = Navkar at the top, `pin:"last"` = Aarti at the bottom |
| Courses (Classes & fees) | `index.html` → `CLASS_LIST`: `state` ("on" = highlighted, Now enrolling / "soon" = YouTube teaser cover with countdown / "shadow" = greyed Coming-soon card with `icon`: notes, mic, guitar, drum), `t` name, `line`, `img`, `pos` (photo focus), `learn` (What you'll learn), `info` (the same 8 detail rows for every course: Mode, Format, Schedule, Duration, Timings, Tracking, Areas, Fees; + Launch for YouTube) |
| Songbook PIN | **two places, change both together:** `music.html` → `var PIN="2006"` and `index.html` → `var PIN="2006"` in the *Songbook entry* script at the bottom |
| Songbook filter groups / chip order | `music.html` → `FACETS` |

---

## 6. File-naming convention (READ before uploading media)

- **all lowercase**, **hyphens** not spaces, **exactly ONE extension** (not `.png.jpeg`).
- descriptive + zero-padded numbers: `section-topic-NN.ext`.
- images `.jpg`/`.jpeg`/`.png`/`.webp`, video `.mp4`.
- **Put images inside `img/`** — uploading to the root by mistake is what broke the hero and events photo before 27 Oct.
- Keep photos under ~200 KB (≈1000–1200 px on the long side). Send big ones to Claude to compress.

---

## 7. How to add a new image or video

1. Name per §6. 2. Open the `img/` folder in the repo → upload → commit. 3. Confirm the exact name. 4. Tell Claude the section + path. 5. Claude updates `index.html` + this file.

---

## 8. Current content — real vs placeholder

**Real:** name, Ronak's bio, phone, VV Puram + map, Instagram handles + 6 reel links, YouTube links, class list + posters, ₹49/mo membership, devotional services, hero poster, Nov launch.

**Songbook status (6 Nov):** 195 songs. Lyrics images: 8 (#9, 19, 34, 35, 43, 92, 94, 99). Typed text: 6 (#27, 96, 97, 98 old stavans; #192, 193 aartis). 27 placeholder songs (names only, ⏳ in §13). Scale set for 7 songs (#1, 3, 4, 6, 24, 39, 44). 26 contexts hold Ronak's own lists; Navkar, Slow Mashup, Girnar, Sankeshwar and Sangh are still waiting for his list.

**Placeholder (replace):** testimonials (sample names/quotes), fees ("On enquiry"), `LAUNCH_DATE` (1 Nov 2026), YouTube course cards (titles invented, links go to channel/join), event card (Tapasya Bhakthi, 20 Sept — already past).

---

## 9. To-Do / open questions

**Urgent**
- [ ] **Confirm the launch date** — countdown passed zero on **1 Nov 2026**; the Music panel now shows both "Coming soon / Launching this November" and "It's here — the music has launched!". What launches, and on which platform (YouTube / Spotify / Instagram)? After launch, the Music panel should show the release instead of "Coming soon".
- [ ] **Event card** — Tapasya Bhakthi (20 Sept) is past. Replace with the next event, or switch to "Past performances".

**Songbook**
- [ ] Lyrics images from Ronak (white-on-black template, with the song number). 8 done: #9, 19, 34, 35, 43, 92, 94, 99.
- [ ] **Scale for every song** — Ronak sends serial number → scale (e.g. `12 – F`, `13 – E / D#`).
- [ ] Lists still to come: Navkar, Slow Mashup, Girnar, Sankeshwar, Sangh.
- [ ] Link anchoring topics to songs, if any should show on top of a song.
- [ ] Review the remaining suggestions in each context.
- [ ] More anchoring lines from Ronak (title + text, and the song number each leads into, if any).
- [ ] Gurudev Aarti (#194) text; stuti text for *Jain gunona sindhuna* and *Pal pal mere har rom mein*.
- [ ] 27 placeholder songs (⏳ in §13) need lyrics images.
- [ ] Decide if `music.html` should stay on public GitHub (PIN only hides the screen) or be kept on Ronak's devices only.

**Content**
- [ ] Real testimonials in `REVIEWS`.
- [ ] Real fees (or keep "On enquiry").
- [ ] Real YouTube course cards — titles, links, Free/Members.
- [ ] Hero image has its own big "PASSIONATE for music?" text baked in, which sits under the site's HTML headline. Decide: keep the poster text and drop/shrink the HTML headline, or use a text-free version of the photo.

**Repo clean-up**
- [ ] Delete the duplicate / unused files listed in §4.

**Host / security (later)**
- [ ] Confirm "Enforce HTTPS" in Settings → Pages.
- [ ] Connect the8thnote.in (DNS at GoDaddy + GitHub Pages custom domain), then Enforce HTTPS.
- [ ] Optional later: Cloudflare in front of the domain for real security headers (X-Frame-Options, nosniff, HSTS, CSP header). `robots.txt` only works properly on a root domain.
- [ ] Honeypot + submit timing only if a real form is ever added.

---

## 10. Change log

1–13. Template → The 8th Note: logo, favicon, contact, devotional side, launch teaser, YouTube courses, FAQ, intro splash, this file, both-files routine.
14. Big content pass from posters; removed template fiction.
15. Context-aware WhatsApp/Call buttons; scroll-up button.
16. FAQ → 5; YouTube right-to-left marquee.
17. Floating WhatsApp, countdown, share meta tags, testimonials, Instagram, `robots.txt` + `sitemap.xml`.
18. Performance pass (non-blocking fonts, logo hints).
19. Security: CSP meta + referrer policy.
20. SEO: meta description, FAQPage JSON-LD, `<main>`.
21. Netflix-style "Why learn" cards.
22. Netflix-style restructure: content moved into a menu overlay; lean landing page; hero image slot.
23. Clean footer rebuild.
24. Instagram reels (now real Instagram embeds via `embed.js`; CSP allows instagram.com / cdninstagram / fbcdn).
25. Bigger nav logo; logo in menu header.
26. Launch teaser → bell button + popup.
27. Removed hero microcopy; "Courses" link in footer.
28. Testimonials → 5-card marquee (sample content).
29. (Between 2 Oct and 27 Oct) Split nav `Music · Services | LOGO | About · Contact`; menu panels Music / Services (Classes, Find your class wizard, Fees, For events) / About / Contact with map; class posters `img/class-01…08`; About and events photos; real reel links.
30. **27 Oct fix pass:**
    - **Hero background was not showing** — file was uploaded as root `hero-bg.png`, code wanted `img/hero-bg.jpg`. Converted + compressed (1.2 MB → 143 KB) to `img/hero-bg.jpg`; added a preload so it appears faster.
    - **Events photo was broken** — `about-ronak-01.jpeg` was in the root, code wanted `img/`. Compressed (319 → 81 KB) into `img/`.
    - **Intro video compressed** 2.8 MB → 0.24 MB, same look and length.
    - `class-06` / `class-07` compressed (499/643 KB → 64/72 KB).
    - Created `og-image.jpg` (1200×630) from the hero poster; removed the second, wrong-sized `og:image` (logo) tag.
    - Removed dead CSS for the old `.tile` / `#rail` layout.
    - `sitemap.xml` lastmod → 2026-10-27.
    - Rewrote this file to match the real site.

31. **Bhakti songbook:** new page `music.html` + song library `songs.js`. Filters by language, occasion/place, Bhagwan, tirth, day/parv; "general songs fit anywhere" toggle; search; shareable filter links; setlist with WhatsApp share; full-screen event mode with big text, swipe and screen-awake. Linked from the Music panel (card) and the footer ("Songbook"). 10 sample songs for now.
32. **Songbook filled from `Ronak_Music_List.docx`:** 44 lyric page images extracted, cropped and compressed into `img/songs/`; 97 songs in `songs.js` (38 with pages + 59 names from Ronak's lists), tagged by language / Bhagwan / tirth / occasion / day / style; Ronak's *Jain Bhakthi Chart* keys, tempos, loop and beat notes attached to each song; 13 ready-made sets from his lists. `music.html` now shows page images with zoom, a Style filter, 'Only songs with lyrics', ready-made sets, multi-language songs, and groups results into 'Made for this' vs 'General songs'.

33. **Bhagwan aliases:** Rushabhdev/Rushabhji/Aadeshwar = Aadinath (and Veer = Mahaveer, Nem = Neminath, Parasnath = Parshvanath) in search; chips and tags show both names.

34. **Stuti section:** `stuti.js` (16 stutis) + Stuti tab and full-screen white-on-black stuti mode in `music.html`; 'Begin with stuti' option before event mode; Music-panel card now says 'Stuti & Bhakti songbook'.

35. Added stutis 17 *Kaise karu main vandana* and 18 *Vandana re dada vandana re*; replaced the faded *Pal pal mere* crop with the sharp one from the Mangalacharan page.

36. **Stuti organised + de-duplicated:** stutis grouped into 6 sections in opening order, each card shows language (Sanskrit / Prakrit / Gujarati / Hindi) and Ronak's key note where there is one; *Tick/Untick group* buttons. Removed song s001 *Mangalacharan* from the Songs list — it was the same page as stutis 10, 11, 14, 16, 17, 18; its key note moved to the *Vandana re* stuti and it was dropped from 3 sets.

37. **Serial numbers, Index, Scale, contexts.js:** every song numbered 1–96; new **Index** tab (by number / A–Z) with title links and per-song links `music.html?song=N`; **Scale (Sa)** filter as the first layer (7 songs set from Ronak's chart: Navkar F#/F, He Trishla F/E, Akhiyan E/D#, Bhakti ki hai raat F/E, O Palanhare F, Hai yeh pawan bhoomi E, Taro mahima E); tags moved out of songs into `contexts.js` as serial-number lists (22 contexts; Tapasya, Fast, Garba marked reviewed as they come from Ronak's chart; the rest are suggestions); sets stored by serial number too.

38. **One file:** at Ronak's request, `songs.js`, `contexts.js`, `stuti.js` and all 47 lyric/stuti pictures were built into `music.html` (pictures re-compressed to ~3 MB, file ~4.2 MB). Only `music.html` needs uploading for the songbook from now on.

39. **Compact personal layout:** removed the songbook intro text and heading; logo, Stuti/Songs/Index tabs, search and Setlist in one top bar; filters are now one row of dropdown buttons (Scale · Language · Occasion · Bhagwan · Tirth · Day · Style) plus *General songs* / *Lyrics only* switches — the button shows what's picked; on phones the options open as a bottom sheet. Song cards: whole card opens the song, small + adds to setlist, context names as one text line. Higher-contrast text everywhere. Logo and tab icon built into the file so it looks right even when opened from a downloaded copy.

40. **PIN + final contexts:** songbook locked with PIN 2006 (keypad screen, 🔒 button to re-lock). Replaced all earlier tags with Ronak's 28 contexts (A–Z). Filters are now just **Scale** and **Context**. Pre-filled 17 contexts from earlier tagging as suggestions (dashed); Tapasya Bhakthi from his chart (solid); 10 empty, waiting for his lists: Bhaav Bhakthi, Chetya Vandan Stavan, Classical Songs, Nakoda Bherav, Rajendra Suriji, Rishto ki Dor, Sahebji, Sangh, Shanti Suriji, Shantinath Bhagwan. General = the General Bhakthi list (53 songs so far).

41. **Typed lyrics (old stavans only):** from Ronak's 108-song text file, typed in clean Devanagari the songs by old poets (1500s–1700s): #27 Akhiyan harkhan lagi (Gyanvimal — replaces its picture), new #97 Chintamani mari chinta chur (Samaysundar), #98 Parshwajinanda Vamaji ke nanda (Mohanvijay), #99 Maro mujro lyo ne raj (Ramvijay, Shantinath). Tagged Prachin Stavan + Bhagwan/tirth (suggestions). Claude does not type modern songs' lyrics; those stay as Ronak's page pictures. Removed #5 Jeni kiki kali chhe from Prachin Stavan (it's a recent song that mentions Udayratna).

42. **Lyrics import + all 108 book songs:** added the *Lyrics file* panel (load .txt, back up, restore, remove) and per-song ✎ editing, all stored on the device only. Linked all 108 songs of Ronak's songbook by book number: 40 matched existing songs, 68 added as new songs #100–#167 (titles in Devanagari + English, language, suggested contexts). Book #47 has no heading in the file — it shares #77's text (both = song #17). Repairing the PDF text gets most lines right; some words stay glued together and can be fixed with ✎.

43. **Songs layout — context panel + list:** left panel lists *All songs* + the 28 contexts A–Z with counts (— = no list yet); one context at a time; the panel minimises (‹ button) and comes back with *☰ Contexts*; remembered on that device. On phones the panel slides in from the left and closes after picking. Songs show as a single top-to-bottom list, one song per line (number · title · English name · scale · +). The Context dropdown was removed (the panel replaces it). Phone header tightened to stay on one line down to 360px.

44. **Ronak's context lists recorded:** 23 contexts now hold his own lists in his order (solid); 25 new placeholder songs #168–#192 for songs not yet in the library (lyrics to come); #70 renamed *Maro bhedo laga dijo paar*. Claude's earlier suggestions kept per context as `suggest` and shown after his list under *Suggested — to review* (dropped for Gujarati/Marvadi Songs). Full record in §12.

45. **Full revision (27 Oct evening):** merged duplicate *Tara dere* into *Tara derethi bolavjo*; renumbered all songs 1–191 with no gaps (old numbers changed for #91 onwards); Ronak's Marvadi list songs set to Marwadi. **Removed every lyric picture** (36 song pages + 4 stuti crops) — only typed text kept; 4 stutis now show *Text to come* and are skipped in stuti mode. General Bhakthi no longer includes songs Ronak placed in his own lists (30 left, all suggestions). Palitana = Ronak's list (#120, #91, #18, #5); #98 Maro mujro added to Shantinath; new context **Palitana 5 Chaityavandan** (list to come) → 29 contexts. Index gained a **By context** view and shows each song's contexts. Full record in §12–13.

46. **General Bhakthi = Ronak's list:** #6 Bhakthi ki hai raat, #14 Uncha ambar thi, #92 Tara sharne aavyo chu, #4 Akhiyan harkan lagi, #39 Hai yeh pawan bhoomi. Only these 5 show under every context; Claude's 29 earlier picks stay inside General Bhakthi as suggestions only.

47. **First lyrics image added:** #99 तूं मने भगवान — Ronak's white-on-black template image, shown as it is (`img/songs/song-099.jpg`, built into music.html). New images: one per song, named by song number.

48. **Context panel always there:** the left context panel is now part of the whole songbook page (Stuti, Songs and Index tabs) and is open every time the page opens. ☰ in the top bar opens/closes it; ‹ in the panel minimises it. Picking a context from any tab opens the Songs tab with that list. On phones it opens as a drawer at start and closes after a pick (the small logo is hidden on phones to keep the header on one line). *All songs* now lists in plain number order.

49. **Stuti: one column, Ronak's own order:** the 18 stutis are now 18 boxes stacked one under another (no side-by-side, no group headings). Each box has a ⠿ drag handle (mouse or finger) and ↑ / ↓ buttons; the order is saved on that device and *Start* / *Begin with stuti* play in that order. *Reset order* puts them back to the original order.

50. **Stuti first, Aarti last:** *Stuti* is now item 1 in the context panel (ॐ icon) and opens the 18 stuti boxes — the Stuti tab in the top bar was removed (tabs are now Songs · Index). *Aarti* added as the last context (diya icon, pinned below the A–Z list) with 3 placeholders: #192 Jay Jay Aarti, #193 Mangal Divo, #194 Gurudev Aarti (lyrics to come). Aarti shows only its own songs (no General Bhakthi). 30 contexts + Stuti; 194 songs.

51. **Floating book button:** a round book button fixed at the bottom-left of the songbook opens / closes the context panel (white when the panel is open); hidden while locked or when a song, stuti mode, setlist or lyrics panel is open. The ☰ in the top bar was removed. The panel now slides and fades smoothly (desktop: the column animates; phone: drawer slides, backdrop fades). The small logo is back in the phone header.

52. **Lyrics-file import removed:** lyrics come only as Ronak's images (or the few typed old stavans / stutis). Removed the *Lyrics only* switch, the *Lyrics file* button and its panel (load / back up / restore), and the ✎ text editor. Filter row is now: Scale · + General Bhakthi · Clear. (`lyrics-import.js` is no longer used.)

53. **8 lyrics images added (30 Oct):** #19 Musafari, #9 Hu chhu tamaro, #92 Tara sharne aavyo chhu, #99 Tu mane Bhagwan (replaced with the new version), #43 Aa mara Maharajji, #34 Tu khub mane, #94 Taro ne maro, #35 Tara mast gulabi gaal — shown exactly as Ronak made them (`img/songs/song-NNN.jpg`, built into music.html, now ~1.8 MB).

54. **Context fixes (30 Oct):** #6 Bhakthi ki hai raat no longer shows under Bhaav Bhakthi (new per-context `exclude` rule — a General Bhakthi song can be kept out of a specific context). #31 Ant chhe anant nahi moved from suggestion into Ronak's Diksha list (now 6 songs).

55. **Adinath Bhagwan:** Ronak confirmed suggestions #13 Siddhachal giri namo namah, #26 Siddhachal na vasi, #29 Dada Aadeshwarji, #37 Rushabhji nand dayal re — added to his list (now 9 songs).

56. **Adinath Bhagwan:** Ronak confirmed #42 Aangan utsav bani, #65 Albelo Aadeshwar, #69 Dhulewa nagri — added (now 12 songs).

57. **Adinath Bhagwan:** added #39 Hai yeh pawan bhoomi (now 13 songs). #92 Tara sharne aavyo chu was already in General Bhakthi.

58. **Mashup context added:** placed right after Adinath Bhagwan (new `after` rule, not A–Z). No list from Ronak yet; 10 suggestions: #7 Mashup, #8 Fast mashup, #165 Mashup 2, #166 Kulpak mashup, #85 Adinath medley, #3, #4, #6, #9, #53 (the combined songs). 31 contexts + Stuti.

59. **Stuti 7 — Vandana re dada vandana re:** text added (given by Ronak); moved to position 7 in the default stuti order. 3 stutis still *Text to come*: Kaise karu main vandana, Jain gunona sindhuna, Pal pal mere har rom mein.

60. **Aarti text added:** #192 जय जय आरती (Aadi Jinanda, Mulchand) and #193 मंगल दीवो (Divo re divo, Dipal) — traditional aartis, text from Ronak, refrain lines in red. #194 Gurudev Aarti still to come.

61. **Stuti 2 — Kaise karu main vandana:** text added (from Ronak) and moved to position 2 in the default order. 2 stutis still *Text to come*: Jain gunona sindhuna, Pal pal mere har rom mein.

62. **Navkar context added:** pinned right after Stuti (above All songs) with a नमो icon (new `pin:"first"`). No General Bhakthi inside it. No list from Ronak yet; suggestion: #1 Nirvikar Navkar. 32 contexts + Stuti.

63. **Adinath Bhagwan:** #10 Keva pyara lage mara dada added at the top (now 14 songs).

64. **Adinath Bhagwan:** #99 Tu mane Bhagwan added (now 15 songs).

65. **Adinath Bhagwan:** #36 Shu karu dada added (now 16 songs).

66. **Adinath Bhagwan:** added #35 Tara mast gulabi gaal, #143 Aavjo man mandiriye (Sundar aa dehrama), #145 Mitha Aadinath (Mithi Paldi gam) (now 19 songs).

67. **All titles in Devanagari:** the 88 songs that only had an English name now have a Devanagari title (English kept underneath, search works with both). Spellings approved by Ronak (30 Oct): #70 म्हारो भेरू लगा दीजो पार, #71 हे शत्रुंजय कुंडना, #168 वीर मेरे पथ, #173 करके तपस्या तप को तपाया, #182 मेरुशिखर न्हवरावे.

68. **Adinath Bhagwan:** added #117, #140, #94, #47, #22 (now 24 songs).

69. **Sahebji: no General Bhakthi** — General Bhakthi songs (#4, #6, #14, #39, #92 and any added later) no longer show under Sahebji (new `noGeneral` rule). Sahebji shows only Ronak's 5 songs.

70. **Grah Pravesh: no General Bhakthi** (same rule as Sahebji).

71. **Palitana:** Ronak confirmed #9, #13, #20, #23, #26, #42, #65 from the suggestions (now 11 songs). Still suggested: #4, #8, #71, #85, #140, #151.

72. **No General Bhakthi** also under Rishto ki Dor, Diksha, Tapasya Bhakthi, Prachin Stavan, Chetya Vandan Stavan. Contexts that skip General Bhakthi now: these 5 + Sahebji, Grah Pravesh (and Navkar, Aarti, which never had it).

73. **Notes brought up to date:** §3 songbook description, §9 songbook to-dos, §12–13 regenerated from the data.

74. **Phone layout tidied (30 Oct):** song list rows denser (smaller text and tags, *No lyrics* tag hidden on phones — about twice as many songs per screen); Index tab the same; smaller filter buttons; book button hides while the context drawer is open (it was covering the last contexts); song view shows the lyrics image almost edge to edge, without the tag chips; *Source* line removed from the song view (all screens); PIN keys are now round.

75. **One header line per list:** removed the repeated context heading above Ronak's songs and the *of 194* count (Songs and Index). The line now reads e.g. *Bhaav Bhakthi · 5 songs + 4 General Bhakthi*; an empty context reads *no list yet*. *Suggested* and *General Bhakthi — also fits* headings stay as dividers.

76. **Anchoring added:** new item *Anchoring* (🎤) in the context panel, right after Navkar. Holds Ronak's anchoring lines as boxes (title + text); a line linked to a song number also shows on top of that song. Empty for now — lines to come from Ronak. New data block ANCHOR (`anchor.js`, built into music.html).

77. **Anchoring — Aadi sparsh** (from Ronak): first anchoring box, 5 short paragraphs ending with the sankalp line *"मेरा कर्तव्य, मेरी धरोहर।"* highlighted in gold (lines starting `> ` in the ANCHOR text are highlighted). Not linked to a song.

78. **Anchoring shows topics only:** the Anchoring page lists topic titles (Aadi sparsh, Tirth Raksha); lines open only when the topic is tapped. Each topic is also listed under *Anchoring* in the context panel — tapping it opens that topic directly.

79. **Anchoring — Tirth Raksha** (from Ronak): second topic, 12 numbered lines (Chickpet temple, Aadi-sparsh, bringing children), each on its own so they're easy to pick from on stage.

80. **Panel as one list:** Stuti, Navkar and Anchoring are no longer a separate block above All songs — the list now starts with *All songs*, then Stuti, Navkar, Anchoring (with its topics), then Adinath Bhagwan and the other contexts, with no dividers between them.

81. **Full check + notes rewrite (3 Nov):** checked everything inside `music.html` — nothing missing (see §0 *Last check*). Added §0 quick reference (every built section, where it is, what's in it); updated header, file list, where-to-edit table (Anchoring, PIN), songbook status.

82. **Rajendra Suriji:** added #24 O Palanhare, #39 Hai yeh pawan bhoomi, #180 O guru sa (Ronak's list now 8: #138, 6, 92, 95, 24, 86, 39, 180 — #6, 92, 95, 86 were already in it).

83. **3 songs into more contexts (3 Nov):** #5 Jeni kiki kali chhe and #18 Rushabhji bolave chhe → General Bhakthi (already in Palitana and Adinath Bhagwan). #54 Aaj anand ang ang jagyo → Utsah Songs (was a suggestion), Adinath Bhagwan, General Bhakthi, Grah Pravesh, Mahaveer Swamy Bhagwan, Rajendra Suriji, Tapasya Bhakthi (already in Dance Number and Pratishta / Dhwaja). General Bhakthi now 8 songs, so these 3 also show under every context that takes General Bhakthi.

84. **#19 Musafari** added to Bhaav Bhakthi, Diksha, General Bhakthi, Gujarati Songs, Sahebji (already in Classical Songs). General Bhakthi now 9 songs.

85. **#10 Keva pyara lage mara dada** added to Bhaav Bhakthi, General Bhakthi (was a suggestion), Grah Pravesh, Palitana (already in Adinath Bhagwan). Neminath and Parshwanath already have their own versions (#167, #149) — #10 added there too on 7 Nov (entry 94). General Bhakthi now 10 songs.

86. **#188 Zamane mein kab kahan** added to Parshwanath Bhagwan (already in All songs and Nakoda Bherav). Still a placeholder — lyrics image to come.

87. **Repo review (5 Nov):** on GitHub, `music.html` was the 30 Oct version and `project_context.md` the 27 Oct version. The 27 Oct fixes had never been uploaded: `img/hero-bg.jpg` was missing (hero background blank — confirmed 404), `img/about-ronak-01.jpeg` and `og-image.jpg` missing, intro video still 2.8 MB, class-06/07 posters uncompressed, a second wrong `og:image` (logo). Delivered the full upload set: `index.html` (the live one + only these fixes: wrong og:image removed, hero preload; still **no** link to the songbook), `music.html`, `project_context.md`, `sitemap.xml` (lastmod 2026-11-05), `og-image.jpg`, `logo-anim.mp4` (0.24 MB), and into `img/`: `hero-bg.jpg`, `about-ronak-01.jpeg`, `class-06.jpeg`, `class-07.jpeg`. Tested the merged site locally: no missing files.

88. **Songbook connected to the website (5 Nov):** the Music panel now starts with a *Stuti & Bhakti Songbook* card with a PIN box. Correct PIN (2006) opens `music.html` straight in, already unlocked for that tab; wrong PIN shakes and says *Wrong PIN*. Everything else in the Music panel unchanged, below it. PIN now lives in both files.

89. **#180 O guru sa thaaro chelo banu main** added to General Bhakthi, Shanti Suriji, Tapasya Bhakthi, Shantinath Bhagwan, Parshwanath Bhagwan, Nakoda Bherav, Marvadi Songs, Grah Pravesh, All Pooja (already in All songs, Rajendra Suriji, Sahebji). Still a placeholder — lyrics image to come. General Bhakthi now 11 songs.

90. **Context numbers C1–C32:** every context has a permanent number (`no` in CONTEXTS), shown in grey before its name in the panel (after the name for Navkar and Aarti, which have icons), in gold in the list header (e.g. *C9 Diksha*), and in the Index *By context* view. Numbered in today's panel order; new contexts get the next number. Ronak can now write "add 180 to C23". Table in §0; §12–13 use the numbers.

91. **New context C33 Simandhar Swamy Bhagwan** — always at the end of the list, just before Aarti (new field `place:"end"`). **New song #195** सुणो चंदाजी सीमंधर परमातम पासे — Suno Chandaji Simandhar parmatam pase (Gujarati, lyrics to come), in All songs and C33. General Bhakthi shows under C33 too (11 songs).

92. **#99 Tu mane Bhagwan** (lyrics image) added to C4, C5, C10 General Bhakthi, C11, C12, C13, C14, C16, C18, C20, C21, C25, C27, C29, C30, C33 (already in C2). General Bhakthi now 12 songs.

93. **#93 Rome rome hu taaro** added to C2, C5, C10 General Bhakthi, C11, C18, C20, C21, C25, C27, C29, C33 (already in C13). General Bhakthi now 13 songs.

94. **#10 Keva pyara lage mara dada** added to C11, C13, C17 Neminath, C20 Parshwanath, C27, C29 Shantinath (already in C2, C5, C10, C12, C18). C17/C20/C29 also keep their own versions (#167, #149, #181).

95. **#96 Chintamani mari chinta chur (Aani mann shuddh aastha)** — the stavan itself, typed text — added to C6, C10 General Bhakthi, C12, C30 (already in C20, C27). Not the mashup #3 He Trishla na jaya × Aani shuddh mann aastha. General Bhakthi now 14 songs.

96. **#36 Shu karu dada** added to the same contexts as #93 Rome rome hu taaro: C5, C10 General Bhakthi, C11, C18, C20, C21, C25, C27, C29, C33 (already in C2, C13). General Bhakthi now 15 songs.

97. **#5 Jeni kiki kali chhe** added to C13 Gujarati Songs, C21 Prachin Stavan (already in C2, C10, C18).

98. **Contexts renumbered and reordered by Ronak (7 Nov):** C1 General Bhakthi, C2 Mashup, C3 Adinath Bhagwan, C4 Neminath Bhagwan, C5 Dance Number, C6 Bhaav Bhakthi, C7 Tapasya Bhakthi, C8 Gujarati Songs, C9 Marvadi Songs, C10 All Pooja; the rest A–Z as C11–C30, then C31 Simandhar Swamy Bhagwan, C32 Aarti (last). Navkar has no number and stays at the top with Stuti and Anchoring. The panel now follows the numbers (`after` / `place` fields removed). No song lists changed.

99. **Renamed:** C2 Mashup → **Slow Mashup**, C5 Dance Number → **Fast Dance Number** (same songs).

100. **C19 Palitana 5 Chaityavandan removed** (it had no songs). Other context numbers unchanged, so C19 is now unused.

101. **Standing rule:** every song Ronak adds to a context from now on also goes into C1 General Bhakthi, unless he names it as an exception. (Not applied backwards to older songs unless he asks.)

102. **Domain the8thnote.in (GoDaddy, 7 Nov):** added `CNAME` file (`the8thnote.in`); all links in `index.html` (canonical, og:url, og:image, JSON-LD) and `sitemap.xml` now use https://the8thnote.in/; `robots.txt` points to the new sitemap and asks search engines to skip `music.html`. GoDaddy DNS: 4 A records `@` → 185.199.108.153 / .109.153 / .110.153 / .111.153, CNAME `www` → ronakpatiyat-maker.github.io; remove GoDaddy's default parked A record / forwarding. GitHub → Settings → Pages → Custom domain `the8thnote.in` → Save → tick Enforce HTTPS once available.

103. **Services simplified (7 Nov):** *Find your class* (3-question wizard) removed completely — tab, code, styles. *Classes* and *Fees* merged into one tab **Classes & fees**: class posters, then the fee cards below. Services now has 2 tabs: Classes & fees · For events. Every "Book a class" button opens Classes & fees; links to fees scroll down to the fee cards. FAQ #1 now points to Classes & fees.

104. **Classes & fees = Ronak's real courses (7 Nov).** The 8 class posters and the 3 fee cards are replaced by course cards from `CLASS_LIST`: (1) YouTube teaser — *greyed, Coming soon*; (2) Offline Jain singing classes; (3) Online Jain singing classes; (4) Offline piano classes — all three highlighted, *Now enrolling*. Each has *View more* (stavans, twice a week × 40 min, group / 1-on-1, timings, areas VV Puram · Shankarpuram · Kumara Park · Basavanagudi · Chamarajpet, lesson tracking, fees on WhatsApp) and *Enquire on WhatsApp* with the course name filled in. Photos reused: class-05 (YouTube), class-06 (offline singing), class-07 (online singing), class-03 (piano). More courses to come from Ronak.

105. **Course cards show only the name (7 Nov):** each card is photo + Now enrolling / Coming soon + course name + *View more*. All details moved into a detail view that opens on *View more* or the photo (pop-up on computer, slide-up sheet on phone; × / Esc / tap outside closes). 2 cards per row on phones.

106. **YouTube teaser = Coming-soon cover (7 Nov):** the card now has an animated cover (brand gradient, YouTube play button, sparkles, light sweep) saying **COMING SOON · Launching this New Year · N days to go** (counts down to 1 Jan 2027, IST). View more opens the same cover large, with a *Subscribe on YouTube — get notified* button (`CHANNEL_URL`). Card class renamed `cs-soon` (the Music panel's `.soon` style was adding padding).

107. **Standard detail view (7 Nov):** every course's detail box is now the same size (560 × 760 on computer, 92% of the screen on phone; content scrolls inside) and the same layout: photo/cover → name → short line → *What you'll learn* → *Course details* tiles with icons, always in the order Mode · Format · Schedule · Duration · Timings · Tracking · Areas · Fees (the YouTube teaser has no details) → Enquire / Subscribe button. Missing values show "To be announced" or "—". Piano *Format* set to "Personalised" — Ronak to confirm group / 1-on-1.

108. **Colours: red, black, white only (7 Nov):** removed every purple / pink (and the blue, green, gold, orange tints) from the website: brand gradient is now deep red → red; all coloured placeholders, icon gradients, glows and the YouTube coming-soon cover are red / black / white. 50 colour values changed. WhatsApp green kept.

109. **YouTube teaser only (7 Nov):** what is launching on YouTube is not disclosed anywhere on the site. The card is just the real YouTube logo (red, white play button) on a black-and-red cover with the animation, **COMING SOON · Launching this New Year · N days to go**, titled *Something new is coming*. View more shows the same cover large, one line ("Something exciting is coming to our YouTube channel…"), "Stay tuned — the countdown is on." and *Subscribe on YouTube — get notified*. No course details.

110. **Contact → Contact us (7 Nov):** top menu, menu panel, About button and footer link now say *Contact us*. In the Contact us panel the VV Puram address and the Google map are removed; in their place a box with a pin icon: **Location yet to be finalised** · Bengaluru · address will be shared soon. Footer address now *Bengaluru · location yet to be finalised*. VV Puram still appears in: page description (Google), About bullet, Why-learn card, "Learn" step, FAQ answer, and as a class area in the course details — waiting for Ronak's decision.

111. **Contact us tidy-up (7 Nov):** removed the "Ronak Patiyat" label; added a second Instagram button **@ronakpatiyat__** (instagram.com/ronakpatiyat__) under @the8thnote__; "Get in Touch" is now plain white (was a cream/grey shine) and all button text is pure white; button backgrounds black → deep red (no brown).

112. **Contact us order (7 Nov):** @the8thnote__ → @ronakpatiyat__ → *Contact: 94800 61108* (tap to call) → *Chat on WhatsApp*.

113. **Contact us polish (7 Nov):** every button now has one standard layout — icon in a red-tinted square · small grey label in capitals (INSTAGRAM / CONTACT) · value in bold white · › arrow. Underline removed from WhatsApp; *Chat on WhatsApp* is the main button (solid red gradient with glow, WhatsApp icon). Phone shown as +91 94800 61108 under the label CONTACT. Title spacing and the location heading tightened slightly.

114. **Contact us (7 Nov):** location line now *Bengaluru · address will be shared soon* ("classes also live online" removed); *Chat on WhatsApp* is a lighter red (#E8323A → #FF5E63) with a softer glow.

115. **Chat on WhatsApp back to the darker red** (brand gradient `--grad`, deep red → red) — Ronak preferred it over the lighter red.

116. **Menu order + bolder (7 Nov):** top menu now **About us · Services | LOGO | Music · Contact us** (same order in the menu panel; footer: Home · About us · Services · Music · Courses · Contact us). "About" renamed *About us*. Menu text weight 900 (extra bold). On phones the four links sit in one evenly spaced row under the logo (no more crowding at 360 px).

117. **Homepage poster red shades — tried and cancelled (8 Nov).** Hero stays as before; Ronak will update the poster later.

118. **Menu titles bigger (8 Nov):** About us · Services | LOGO | Music · Contact us, extra bold (900), size up from 15 px to ~17–19 px on computer, 15 px on tablet, 14 px on phone (12.5 px on very small phones) — all four still fit one row.

119. **About us (8 Nov):** removed the small *About* label above the heading; *Meet Ronak Patiyat* is now red (red gradient, like *With Us* in Contact us); the 5 red tick marks are gone — the 5 points are now plain white lines separated by thin dividers.

120. **Spelling:** piano course song now written *Parmatma thirangase* (as Ronak writes it).

121. **Course 5 added (8 Nov): Online piano classes** — highlighted, Now enrolling. Learn: 100+ Jain stavans on piano, basic music theory, explore raags, songs like Nemras, Parmatma thirangase, O Palanhare. Live online · Personalised · twice a week · 40 min · after 10:00 am · anywhere · personalised lesson tracking · fees on WhatsApp. Photo: class-02 (at the keyboard).

122. **Course 6 added (8 Nov): Offline Bollywood piano classes** — highlighted, Now enrolling. Learn: A to Z music theory, chords, arpeggios, 40+ Bollywood songs. In person · Personalised · twice a week · 40 min · after 5:30 pm · VV Puram, Shankarpuram, Kumara Park, Basavanagudi, Chamarajpet · personalised lesson tracking · fees on WhatsApp. Photo: class-04. Now 6 cards (2 full rows of 3 on computer).

123. **Course 7 added (8 Nov): Online Bollywood piano classes** — highlighted, Now enrolling. Learn: A to Z music theory, chords, arpeggios, 40+ Bollywood songs. Live online · Personalised · twice a week · 40 min · after 10:00 am · anywhere · personalised lesson tracking · fees on WhatsApp. Photo: class-05.

124. **Courses 8–11 added in shadow (8 Nov):** Hindustani classical vocals (music-notes icon), Bollywood singing classes (mic), Guitar classes (guitar), Drumming classes (drum). New card style `state:"shadow"`: greyed striped cover with a grey icon and a grey *Coming soon* tag, name in grey; View more opens the standard-size box with the icon, *Coming soon*, one line ("This course is being planned…") and *Notify me on WhatsApp* (message names the course). No photos needed. Total 11 cards: 1 teaser, 6 enrolling, 4 shadow.

125. **Course layout (8 Nov):** the YouTube teaser is now one big full-width panel at the top (large logo, COMING SOON, countdown; name and View more on one line below). All other 10 courses are cards of exactly the same size: 5 per row on computer (2 rows: 6 enrolling, then 4 coming soon), 3 per row on tablet, 2 per row on phone. Intro line now "Singing and piano with Ronak…".

126. **Events in the menu, Music made private (8 Nov):** top menu now **About us · Services | LOGO | Events · Contact us** (also in the menu panel and footer). *For events* moved out of Services into its own **Events** panel (Services keeps only Classes & fees; tab bar removed). *Music* is no longer in the menu: it opens from a new round **♪ button** at bottom-left, stacked above the launch bell and WhatsApp (dark circle, white note). The bell popup's *Go to Music* still opens it.

127. **Services heading (8 Nov):** the panel now opens with a big heading **LEARN WITH THE8THNOTE** ("LEARN WITH" white, "THE8THNOTE" red), replacing the old *Classes & fees* title; intro line and courses below unchanged.

128. **"Classes we offer" (8 Nov):** subheading above the course cards in Services (bold white, with a red line fading to the right).

129. **Services:** removed the intro sentence ("Singing and piano with Ronak…"); the panel goes straight from LEARN WITH THE8THNOTE to *Classes we offer*.

130. **"Classes we offer" highlighted (8 Nov):** now a full-width bar lined up exactly with the course grid — red bar on the left, red glow fading to the right, white bold capitals with letter-spacing.

131. **YouTube teaser smaller (8 Nov):** panel height cut from ~380 px to ~220 px on computer (~266 px with its name line; ~240 px on phone), smaller logo and text. Still full width, still animated, countdown kept; the course cards now show on the first screen.

132. **Let's connect form (8 Nov):** at the bottom of Services, under a *LET'S CONNECT* bar: heading *Let's bring your vision into reality*, small-caps note *your contact details will not be published*, fields Name · Contact details · Course (dropdown of all courses, coming-soon ones marked, plus "Not sure yet") · Message, and a **Chat on WhatsApp** button. Name and contact are required (red outline + message if missing). The button opens WhatsApp to +91 94800 61108 with the details typed in ("Hi Ronak, I'd like to connect. Name… Contact… Course… Message…"); nothing is stored on the website. Code: `#lcForm` in `index.html`.

133. **Services tidy (8 Nov):** removed the *Fees: enquire on WhatsApp* line under the courses, the *LET'S CONNECT* bar above the form, and the *Not sure yet* course option. The form now follows the course cards directly.

134. **Form: required fields marked (8 Nov):** *Name* and *Contact details* labels now carry a red ✱; WhatsApp won't open until both are filled (missing box gets a red outline + message).

135. **Form course list (8 Nov):** courses 8–11 (Hindustani classical vocals, Bollywood singing, Guitar, Drumming) stay in the dropdown but greyed out as "— coming soon" and cannot be picked; only the 6 open courses can be chosen.

136. **Form course list = open courses only (8 Nov):** removed *Choose a course* and the 4 coming-soon courses from the dropdown; it lists only the 6 courses open for enrolment (first one shown by default).

137. **Form course list (8 Nov, final):** no *Choose a course*; the 6 open courses first, then courses 8–11 greyed out as "— coming soon" (cannot be picked).

138. **Form course box (8 Nov):** shows *Choose a course* (grey) until a course is picked, but *Choose a course* is not in the list itself; list = 6 open courses + courses 8–11 greyed "— coming soon". Course stays optional.

139. **Course dropdown restyled (8 Nov):** the phone's plain list is replaced by the site's own dropdown (`#lcDD`), same font and alignment as the rest of the form: *Choose a course* in grey until picked; list in two groups — **OPEN FOR ENROLMENT** (the 6 courses, bold white, red highlight on hover, red tick on the chosen one) and **COMING SOON** (courses 8–11 in grey with a *Coming soon* tag, not clickable). Works with keyboard (arrows, Enter, Esc). Fills in automatically from `CLASS_LIST`.

140. **Form labels highlighted (8 Nov):** NAME, CONTACT DETAILS, COURSE, MESSAGE now bold white capitals (bigger, ~15 px) with a short red bar before each; the red ✱ on Name and Contact is bigger too.

141. **Links at the bottom of every panel (8 Nov):** under About us, Services, Events, Contact us and Music there is now one strip (`.mp-foot`): **ABOUT US · SERVICES · EVENTS · CONTACT US** (the one you're on is red and underlined; tapping another switches panel) and two buttons **Instagram @the8thnote__** and **YouTube** (@ronakpatiyat). Same width as the panel content; on phones the 4 links sit 2 × 2 with the two buttons side by side below.

142. **Bottom strip, classic centred layout (8 Nov):** a thin line fading to red in the middle, then centred **ABOUT US | SERVICES | EVENTS | CONTACT US** (thin dividers, current one red), then three outline buttons **@the8thnote__ · @ronakpatiyat__ · YouTube**, then **📍 BENGALURU, INDIA** in small spaced capitals. Phone: links 2 × 2, the two Instagram buttons side by side, YouTube full width below.

143. **BENGALURU, INDIA brighter (8 Nov):** now white, bolder and slightly bigger (was light grey); red pin a little bigger.

144. **BENGALURU, INDIA toned down (8 Nov):** medium grey (#B8B8B8), small (12 px), red pin — between the first light grey and the white version.

145. **Bottom strip sizes (8 Nov):** the 4 section links are bigger (~18 px computer, 15 px phone); the 3 account buttons (@the8thnote__, @ronakpatiyat__, YouTube) are smaller (12 px text, 34 px tall).

146. **Location font (8 Nov):** *Bengaluru, India* in the bottom strip is now an elegant italic serif — **Cormorant Garamond** italic (Google Fonts, added to the font link), normal capitals, medium grey, ~17 px; red pin kept. Rest of the site stays Archivo.

147. **Location font back to standard (8 Nov):** *Bengaluru, India* in the site font (Archivo), normal letters, regular weight, 13.5 px, medium grey; Cormorant Garamond removed again.

148. **Events heading (8 Nov):** Events panel now opens with **Looking for a singer with devotion & passion?** (big, red) and under it **Book The 8th Note for your Bhakthi event** (white); the short line about Ronak, photo and event types follow as before.

149. **Events red line, full wording (8 Nov):** now *Looking for a singer with devotion & passion for your Bhakthi events?* (big, red), then *Book The 8th Note for your Bhakthi event* (white).

150. **Events poster (8 Nov):** Ronak's poster ("Looking for a SINGER with Devotion & Passion — FOR BHAKTHI EVENTS", What I bring, Ronak Patiyat, contact 9480061108) replaces the old events photo. Saved as **`img/events-poster.jpg`** (1024 × 1536, JPEG quality 90, 265 KB — full size, not cropped). Shown whole and centred, up to 560 px wide on computer, full width on phone.

151. **Events stage photo (8 Nov):** Ronak's live-on-stage photo added right below the poster, full width, not cropped. Saved as **`img/events-stage.jpg`** — the original file, unchanged (1280 × 852, 105 KB).

152. **Events stage photo updated (8 Nov):** replaced with Ronak's PNG version of the same photo, used as-is — **`img/events-stage.png`** (1280 × 852, 724 KB). `events-stage.jpg` is no longer used.

153. **Events poster removed (8 Nov):** the "Looking for a SINGER" poster is no longer shown; Events now has the headings, then the stage photo (`img/events-stage.png`). `img/events-poster.jpg` is unused — no need to upload it.

154. **Events photo built into index.html (8 Nov):** the stage photo is now inside `index.html` itself (as data), so it shows even when the file is opened on its own or before `img/` is uploaded. index.html ≈ 1.1 MB. `img/events-stage.png` no longer needs uploading.

155. **Events = the poster, rebuilt as a web page (8 Nov):** computer: stage photo on the left, text on the right; phone: photo on top. Text exactly as on Ronak's poster: LOOKING FOR A (small, spaced, lines either side) · **SINGER** (huge red, condensed font *Anton*, speckle) · *With Devotion & Passion* (script font *Great Vibes*, white) · ◆ ornament · **FOR BHAKTHI EVENTS** on a red brush banner · quote "Classical training & **spiritual** connection to make your event divine and **memorable**." (only those two words red) · — WHAT I BRING — with red icons and a red line: Jain & Spiritual Programs, Bhakthi Sandhya, Pooja, Path & Religious Events, All Bhakthi Occasions · **Ronak** (big red) *Patiyat* (script, red underline) · red phone box CONTACT : **9480061108** (tap to call). Below: a box *Book The 8th Note for your Bhakthi event* + Enquire on WhatsApp, then the Tapasya Bhakthi event card. Removed: the old red question line, the "Ronak Patiyat — devotional singer…" line, the 4 event boxes and the old quote line. Fonts Anton + Great Vibes added to the Google Fonts link.

---

## 11. Handy facts

- The site is one file (`index.html`) + assets.
- Browsers mute auto-playing video; sound needs a click.
- GitHub is case-sensitive and keeps whatever extension you upload — verify names and folders.
- After any upload, hard-refresh. Link previews (WhatsApp etc.) are cached — new `og-image.jpg` can take a while to show.
- The intro source video has a small sparkle watermark in the bottom-right corner (from the tool that made it).

## 12. Contexts — what is in each (song numbers)

32 contexts (Navkar + C1–C32, C19 unused) + Stuti + Anchoring, in panel order: All songs · ॐ Stuti · Navkar · 🎤 Anchoring · C1 … C32 (Aarti last). Ronak = his own list, in his order. *suggested* = Claude suggestion, to review. ⏳ = placeholder, lyrics to come. 🖼 = Ronak's lyrics image. Songs in Ronak's General Bhakthi list also show under every context **except**: Navkar, Chetya Vandan Stavan, Diksha, Grah Pravesh, Prachin Stavan, Rishto ki Dor, Sahebji, Tapasya Bhakthi, Aarti.

**Navkar** (Claude suggestion, pinned right after Stuti, no General Bhakthi) — _no songs yet_ · *suggested:* #1

**C1 · General Bhakthi** (Ronak) — #6 Bhakti ki hai raat x Nemji shamaliya · #14 Uncha ambar thi · #92 Tara sharane aavyo chhu 🖼 · #4 Akhiyan harkhan lagi x Giriraj na Aadinath x Mara ghat ma birajta · #39 Hai yeh pawan bhoomi · #5 Jeni kiki kali chhe · #18 Rushabhji bolave chhe · #54 Aaj anand ang ang jagyo · #19 Musafari 🖼 · #10 Keva pyara lage mara dada · #180 O guru sa thaaro chelo banu main ⏳ · #99 Tu mane Bhagwan ek vardan aapi de 🖼 · #93 Rome rome hu · #96 Chintamani mari chinta chur (Aani mann shuddh aastha) · #36 Shu karu dada · *suggested:* #1, #7, #12, #24, #32, #34, #40, #41, #43, #46, #49, #53, #55, #56, #57, #58, #59, #61, #72, #76, #79, #84, #87, #88, #89, #90, #94, #156

**C2 · Slow Mashup** (Claude suggestion) — _no songs yet_ · *suggested:* #7, #8, #165, #166, #85, #3, #4, #6, #9, #53

**C3 · Adinath Bhagwan** (Ronak) — #10 Keva pyara lage mara dada · #18 Rushabhji bolave chhe · #5 Jeni kiki kali chhe · #11 Vhala Aadinath · #20 Siddhachal darbar jhajharman lage chhe · #23 Shetrunji nadi ne ghat re · #13 Siddhachal giri namo namah · #26 Siddhachal na vasi · #29 Dada Aadeshwarji · #37 Rushabhji nand dayal re, mohe lagi lagan · #42 Aangan utsav bani aavo Vrushabhji · #65 Albelo Aadeshwar · #69 Dhulewa nagri mein Kesariya viraje · #39 Hai yeh pawan bhoomi · #99 Tu mane Bhagwan ek vardan aapi de 🖼 · #36 Shu karu dada · #35 Tara mast gulabi gaal 🖼 · #143 Aavjo man mandiriye (Sundar aa dehrama) · #145 Mitha Aadinath (Mithi Paldi gam) · #117 Parmatma bani jashe maro aatma · #140 Giriraj na Aadinath · #94 Taro ne maro 🖼 · #47 Kesar tilak lagavo · #22 Hu baal tamaro chhu · #54 Aaj anand ang ang jagyo · #93 Rome rome hu · *suggested:* #4, #8, #9, #38, #71, #85, #120, #151

**C4 · Neminath Bhagwan** (Ronak) — #62 Nemras · #121 Nemji shamaliya (Girnare shobhe dekho) · #16 Shyamla Neminath · #167 Keva pyara lage mara Neminath dada ⏳ · #63 Jay jay garvo Girnar · #10 Keva pyara lage mara dada · *suggested:* #6, #8, #17, #25, #35, #39, #129, #148, #150

**C5 · Fast Dance Number** (Ronak) — #62 Nemras · #63 Jay jay garvo Girnar · #54 Aaj anand ang ang jagyo · #64 Naam hai tera taran hara · #66 Aao dada padharo dada · #65 Albelo Aadeshwar · *suggested:* #50, #51, #69, #74, #75, #76, #84

**C6 · Bhaav Bhakthi** (Ronak) — #132 Samu juo ne · #9 Hu chhu tamaro x Shetrunji nadi ne ghat re 🖼 · #152 Keva shobhe mara jinraya · #143 Aavjo man mandiriye (Sundar aa dehrama) · #178 Mere saheb ne mujhko bohot kuch diya ⏳ · #19 Musafari 🖼 · #10 Keva pyara lage mara dada · #99 Tu mane Bhagwan ek vardan aapi de 🖼 · #93 Rome rome hu · #36 Shu karu dada · _never #6 Bhakti ki hai raat x Nemji shamaliya_

**C7 · Tapasya Bhakthi** (Ronak, no General Bhakthi) — #171 Khamma ghani khamma ghani ⏳ · #172 Tame utsav aaj mandavo ⏳ · #173 Kar ke tapasya tab ko tapasya ⏳ · #174 Tyaag samarpan aur saiyamta ⏳ · #175 Tapasya karta karta ho ⏳ · #82 Jay jay kar tapasvi no · #83 Ga raha sara sansar, tapasvi amar rahe · #54 Aaj anand ang ang jagyo · #180 O guru sa thaaro chelo banu main ⏳ · #99 Tu mane Bhagwan ek vardan aapi de 🖼 · #96 Chintamani mari chinta chur (Aani mann shuddh aastha)

**C8 · Gujarati Songs** (Ronak) — #93 Rome rome hu · #36 Shu karu dada · #117 Parmatma bani jashe maro aatma · #31 Ant chhe anant nahi (Sarva swikar ni sanyam yatra) · #19 Musafari 🖼 · #99 Tu mane Bhagwan ek vardan aapi de 🖼 · #10 Keva pyara lage mara dada · #5 Jeni kiki kali chhe

**C9 · Marvadi Songs** (Ronak) — #69 Dhulewa nagri mein Kesariya viraje · #67 Ek baar mukhdo batao · #68 Jino jino ude re gulaal · #74 Range rame ya range · #75 Mara dada na darbare dhol · #180 O guru sa thaaro chelo banu main ⏳

**C10 · All Pooja** (Ronak) — #21 Sona rupana kalashe · #182 Merushi karnav ⏳ · #180 O guru sa thaaro chelo banu main ⏳ · #99 Tu mane Bhagwan ek vardan aapi de 🖼 · *suggested:* #47

**C11 · Chetya Vandan Stavan** (Ronak, no General Bhakthi) — #120 Uncha uncha Shatrunjay na shikharo sohay · #26 Siddhachal na vasi · #29 Dada Aadeshwarji · #102 Aankhdi mari prabhu harkhay chhe · #179 Rishab jinand ⏳ · #48 Hu prabhu maro tune · #96 Chintamani mari chinta chur (Aani mann shuddh aastha)

**C12 · Classical Songs** (Ronak) — #42 Aangan utsav bani aavo Vrushabhji · #19 Musafari 🖼 · #44 Taro mahima aparampar

**C13 · Diksha** (Ronak, no General Bhakthi) — #130 Virtidhar no vesh · #176 Vairagi ne vandan ⏳ · #52 Rajpath par janara · #177 Jhume re jhume ⏳ · #162 Mare to levani levani chhe diksha · #31 Ant chhe anant nahi (Sarva swikar ni sanyam yatra) · #19 Musafari 🖼 · *suggested:* #17, #119, #122, #123, #128, #134, #135, #136

**C14 · Girnar** (Claude suggestion) — #6 Bhakti ki hai raat x Nemji shamaliya · #8 Fast mashup (Om Shri Neminath…) · #16 Shyamla Neminath · #17 Rajul ne Nem mali jaashe · #25 Namami Nemi · #35 Tara mast gulabi gaal 🖼 · #39 Hai yeh pawan bhoomi · #62 Nemras · #63 Jay jay garvo Girnar · #121 Nemji shamaliya (Girnare shobhe dekho) · #129 Rome rome Girnar · #148 Girnare Shri prabhu Nem chhe · #150 Man mohi lidhu Girnare · #99 Tu mane Bhagwan ek vardan aapi de 🖼 · #93 Rome rome hu · #10 Keva pyara lage mara dada · #36 Shu karu dada

**C15 · Grah Pravesh** (Ronak, no General Bhakthi) — #15 Meri jhopdi ke bhaag · #66 Aao dada padharo dada · #54 Aaj anand ang ang jagyo · #10 Keva pyara lage mara dada · #180 O guru sa thaaro chelo banu main ⏳ · #99 Tu mane Bhagwan ek vardan aapi de 🖼 · #96 Chintamani mari chinta chur (Aani mann shuddh aastha) · *suggested:* #58, #109

**C16 · Mahaveer Swamy Bhagwan** (Ronak) — #3 He Trishla na jaya x Aani shuddh mann aastha · #168 Veer mere patha ⏳ · #169 Vadhavo Veer Jinvar ne ⏳ · #81 Tu Veer se dil ko laga le · #170 Helo maro sambhalo ⏳ · #54 Aaj anand ang ang jagyo · #99 Tu mane Bhagwan ek vardan aapi de 🖼 · *suggested:* #4, #8, #28, #80, #107, #108, #124

**C17 · Nakoda Bherav** (Ronak) — #188 Zamane mein kab kahan ⏳ · #189 Mara Nakoda ra nath ⏳ · #70 Maro bhedo laga dijo paar · #180 O guru sa thaaro chelo banu main ⏳ · #99 Tu mane Bhagwan ek vardan aapi de 🖼

**C18 · Palitana** (Ronak) — #120 Uncha uncha Shatrunjay na shikharo sohay · #91 Chalo ji chalo · #18 Rushabhji bolave chhe · #5 Jeni kiki kali chhe · #9 Hu chhu tamaro x Shetrunji nadi ne ghat re 🖼 · #13 Siddhachal giri namo namah · #20 Siddhachal darbar jhajharman lage chhe · #23 Shetrunji nadi ne ghat re · #26 Siddhachal na vasi · #42 Aangan utsav bani aavo Vrushabhji · #65 Albelo Aadeshwar · #10 Keva pyara lage mara dada · #99 Tu mane Bhagwan ek vardan aapi de 🖼 · #93 Rome rome hu · #36 Shu karu dada · *suggested:* #4, #8, #71, #85, #140, #151

**C20 · Parshwanath Bhagwan** (Ronak) — #30 Shankheshwar ka nath hai · #149 Keva pyara lage mara Parshwanath dada · #96 Chintamani mari chinta chur (Aani mann shuddh aastha) · #4 Akhiyan harkhan lagi x Giriraj na Aadinath x Mara ghat ma birajta · #47 Kesar tilak lagavo · #188 Zamane mein kab kahan ⏳ · #180 O guru sa thaaro chelo banu main ⏳ · #99 Tu mane Bhagwan ek vardan aapi de 🖼 · #93 Rome rome hu · #10 Keva pyara lage mara dada · #36 Shu karu dada · *suggested:* #2, #3, #27, #60, #97, #101, #114, #125, #147, #154, #157

**C21 · Prachin Stavan** (Ronak, no General Bhakthi) — #54 Aaj anand ang ang jagyo · #99 Tu mane Bhagwan ek vardan aapi de 🖼 · #93 Rome rome hu · #36 Shu karu dada · #5 Jeni kiki kali chhe · *suggested:* #26, #27, #96, #97, #98

**C22 · Pratishta / Dhwaja** (Ronak) — #47 Kesar tilak lagavo · #33 Ude re dhwaja (Dada na derasar par) · #15 Meri jhopdi ke bhaag · #78 Lehra do · #54 Aaj anand ang ang jagyo · *suggested:* #45, #46, #117

**C23 · Rajendra Suriji** (Ronak) — #138 Mere dono haathon mein (aisi lakeer hai) · #6 Bhakti ki hai raat x Nemji shamaliya · #92 Tara sharane aavyo chhu 🖼 · #95 Duniya se main haara · #24 O Palanhare · #86 Mere sir par rakho dada · #39 Hai yeh pawan bhoomi · #180 O guru sa thaaro chelo banu main ⏳ · #54 Aaj anand ang ang jagyo

**C24 · Rishto ki Dor** (Ronak, no General Bhakthi) — #183 Tu kitni achhi hai ⏳ · #184 Yeh dosti hum nahi todenge ⏳ · #185 Ek dusre se karte hai pyaar hum ⏳ · #186 Chanda ne poocha taaron se ⏳ · #187 Phoolon ka taaron ka ⏳

**C25 · Sahebji** (Ronak, no General Bhakthi) — #178 Mere saheb ne mujhko bohot kuch diya ⏳ · #9 Hu chhu tamaro x Shetrunji nadi ne ghat re 🖼 · #77 Aagman taro aagman · #22 Hu baal tamaro chhu · #180 O guru sa thaaro chelo banu main ⏳ · #19 Musafari 🖼 · #99 Tu mane Bhagwan ek vardan aapi de 🖼 · #93 Rome rome hu · #36 Shu karu dada

**C26 · Sangh** (Claude suggestion) — _no songs yet_

**C27 · Sankeshwar** (Claude suggestion) — #2 Shankheshwara tu saharo · #3 He Trishla na jaya x Aani shuddh mann aastha · #30 Shankheshwar ka nath hai · #96 Chintamani mari chinta chur (Aani mann shuddh aastha) · #97 Parshwajinanda Vamaji ke nanda · #101 Aankh mari ughade tya Shankheshwar dekhu · #125 Mari aankhoma Shankheshwar aavjo re · #154 He Shankheshwar swami · #99 Tu mane Bhagwan ek vardan aapi de 🖼 · #93 Rome rome hu · #10 Keva pyara lage mara dada · #36 Shu karu dada

**C28 · Shanti Suriji** (Ronak) — #190 Aangi (Shanti Suriji) ⏳ · #191 Phool (Shanti Suriji) ⏳ · #180 O guru sa thaaro chelo banu main ⏳

**C29 · Shantinath Bhagwan** (Ronak) — #181 Keva pyara lage mara Shantinath dada ⏳ · #98 Maro mujro lyo ne raj (Shantinath) · #180 O guru sa thaaro chelo banu main ⏳ · #99 Tu mane Bhagwan ek vardan aapi de 🖼 · #93 Rome rome hu · #10 Keva pyara lage mara dada · #36 Shu karu dada

**C30 · Utsah Songs** (Ronak) — #42 Aangan utsav bani aavo Vrushabhji · #68 Jino jino ude re gulaal · #73 Dhol baje dhol baje · #54 Aaj anand ang ang jagyo · *suggested:* #8, #15, #50, #51, #62, #63, #64, #65, #66, #67, #69, #70, #71, #72, #74, #75, #76, #77, #78, #85, #104, #108, #163

**C31 · Simandhar Swamy Bhagwan** (Ronak) — #195 Suno Chandaji Simandhar parmatam pase ⏳ · #99 Tu mane Bhagwan ek vardan aapi de 🖼 · #93 Rome rome hu · #36 Shu karu dada

**C32 · Aarti** (Ronak, pinned last, no General Bhakthi) — #192 Jay Jay Aarti (Aadi Jinanda) · #193 Mangal Divo (Divo re divo) · #194 Gurudev Aarti ⏳

## 13. All songs — serial number, name, contexts

195 songs. * after a context = suggestion only.

| No. | Song | Typed lyrics / image | Contexts |
|---|---|---|---|
| 1 | नवकार — Nirvikar Navkar |  | Navkar*, C1 General Bhakthi* |
| 2 | शंखेश्वरा तू सहारो — Shankheshwara tu saharo |  | C20 Parshwanath Bhagwan*, C27 Sankeshwar |
| 3 | हे त्रिशला ना जाया × आणि शुद्ध मन आस्था — He Trishla na jaya x Aani shuddh mann aastha |  | C2 Slow Mashup*, C16 Mahaveer Swamy Bhagwan, C20 Parshwanath Bhagwan*, C27 Sankeshwar |
| 4 | अखियाँ हरखण लागी × गिरिराज ना आदिनाथ × मारा घट मां बिराजता — Akhiyan harkhan lagi x Giriraj na Aadinath x Mara ghat ma birajta |  | C1 General Bhakthi, C2 Slow Mashup*, C3 Adinath Bhagwan*, C16 Mahaveer Swamy Bhagwan*, C18 Palitana*, C20 Parshwanath Bhagwan |
| 5 | जेनी कीकी काळी छे — Jeni kiki kali chhe |  | C1 General Bhakthi, C3 Adinath Bhagwan, C8 Gujarati Songs, C18 Palitana, C21 Prachin Stavan |
| 6 | भक्ति की है रात × नेमजी शामलीया — Bhakti ki hai raat x Nemji shamaliya |  | C1 General Bhakthi, C2 Slow Mashup*, C4 Neminath Bhagwan*, C14 Girnar, C23 Rajendra Suriji |
| 7 | मैशअप (सुंदर आ देहरामां…) — Mashup (Sundar aa dehrama…) |  | C1 General Bhakthi*, C2 Slow Mashup* |
| 8 | फास्ट मैशअप (ॐ श्री नेमीनाथ…) — Fast mashup (Om Shri Neminath…) |  | C2 Slow Mashup*, C3 Adinath Bhagwan*, C4 Neminath Bhagwan*, C14 Girnar, C16 Mahaveer Swamy Bhagwan*, C18 Palitana*, C30 Utsah Songs* |
| 9 | हूं छु तमारो × शेत्रुंजी नदीने घाट रे — Hu chhu tamaro x Shetrunji nadi ne ghat re | image | C2 Slow Mashup*, C3 Adinath Bhagwan*, C6 Bhaav Bhakthi, C18 Palitana, C25 Sahebji |
| 10 | केवा प्यारा लागे — Keva pyara lage mara dada |  | C1 General Bhakthi, C3 Adinath Bhagwan, C4 Neminath Bhagwan, C6 Bhaav Bhakthi, C8 Gujarati Songs, C14 Girnar, C15 Grah Pravesh, C18 Palitana, C20 Parshwanath Bhagwan, C27 Sankeshwar, C29 Shantinath Bhagwan |
| 11 | व्हाला आदिनाथ — Vhala Aadinath |  | C3 Adinath Bhagwan |
| 12 | श्वास छे तूं मारो — Shwas chhe tu maro |  | C1 General Bhakthi* |
| 13 | सिद्धाचल गिरी नमो नमः — Siddhachal giri namo namah |  | C3 Adinath Bhagwan, C18 Palitana |
| 14 | ऊंचा अंबर थी — Uncha ambar thi |  | C1 General Bhakthi |
| 15 | मेरी झोपडी के भाग — Meri jhopdi ke bhaag |  | C15 Grah Pravesh, C22 Pratishta / Dhwaja, C30 Utsah Songs* |
| 16 | श्यामला नेमिनाथ — Shyamla Neminath |  | C4 Neminath Bhagwan, C14 Girnar |
| 17 | राजुल ने नेम मळी जाशे — Rajul ne Nem mali jaashe |  | C4 Neminath Bhagwan*, C13 Diksha*, C14 Girnar |
| 18 | ऋषभजी बोलावे छे — Rushabhji bolave chhe |  | C1 General Bhakthi, C3 Adinath Bhagwan, C18 Palitana |
| 19 | मुसाफ़री — Musafari | image | C1 General Bhakthi, C6 Bhaav Bhakthi, C8 Gujarati Songs, C12 Classical Songs, C13 Diksha, C25 Sahebji |
| 20 | सिद्धाचल दरबार — Siddhachal darbar jhajharman lage chhe |  | C3 Adinath Bhagwan, C18 Palitana |
| 21 | सोना रूपाना कलशे — Sona rupana kalashe |  | C10 All Pooja |
| 22 | हुं बाळ तमारो छु — Hu baal tamaro chhu |  | C3 Adinath Bhagwan, C25 Sahebji |
| 23 | शेत्रुंजी नदीने घाट रे — Shetrunji nadi ne ghat re |  | C3 Adinath Bhagwan, C18 Palitana |
| 24 | ओ पालनहारे — O Palanhare |  | C1 General Bhakthi*, C23 Rajendra Suriji |
| 25 | नमामि नेमि — Namami Nemi |  | C4 Neminath Bhagwan*, C14 Girnar |
| 26 | सिद्धाचल ना वासी — Siddhachal na vasi |  | C3 Adinath Bhagwan, C11 Chetya Vandan Stavan, C18 Palitana, C21 Prachin Stavan* |
| 27 | अखियाँ हरखण लागी (मूल स्तवन) — Akhiyan harkhan lagi (original stavan) | text | C20 Parshwanath Bhagwan*, C21 Prachin Stavan* |
| 28 | त्रिशला नन्दनम, प्रभु परमेश्वरम — Trishla nandanam prabhu parmeshwaram |  | C16 Mahaveer Swamy Bhagwan* |
| 29 | दादा आदेश्वरजी — Dada Aadeshwarji |  | C3 Adinath Bhagwan, C11 Chetya Vandan Stavan |
| 30 | शंखेश्वर का नाथ है — Shankheshwar ka nath hai |  | C20 Parshwanath Bhagwan, C27 Sankeshwar |
| 31 | अंत छे अनंत नही — Ant chhe anant nahi (Sarva swikar ni sanyam yatra) |  | C8 Gujarati Songs, C13 Diksha |
| 32 | लगनी लागी छे — Lagni lagi chhe |  | C1 General Bhakthi* |
| 33 | उड़े रे ध्वजा — Ude re dhwaja (Dada na derasar par) |  | C22 Pratishta / Dhwaja |
| 34 | तु खुब मने गमे छे, मारा व्हाला प्रभु — Tu khub mane game chhe | image | C1 General Bhakthi* |
| 35 | तारा मस्त गुलाबी गाल — Tara mast gulabi gaal | image | C3 Adinath Bhagwan, C4 Neminath Bhagwan*, C14 Girnar |
| 36 | शूं करू दादा — Shu karu dada |  | C1 General Bhakthi, C3 Adinath Bhagwan, C6 Bhaav Bhakthi, C8 Gujarati Songs, C14 Girnar, C18 Palitana, C20 Parshwanath Bhagwan, C21 Prachin Stavan, C25 Sahebji, C27 Sankeshwar, C29 Shantinath Bhagwan, C31 Simandhar Swamy Bhagwan |
| 37 | ऋषभजी नंद दयाल रे, मोहे लागी लगन — Rushabhji nand dayal re, mohe lagi lagan |  | C3 Adinath Bhagwan |
| 38 | आदि स्पर्श आया — Adi sparsh aaya |  | C3 Adinath Bhagwan* |
| 39 | है ये पावन भूमि — Hai yeh pawan bhoomi |  | C1 General Bhakthi, C3 Adinath Bhagwan, C4 Neminath Bhagwan*, C14 Girnar, C23 Rajendra Suriji |
| 40 | मेरा एक साथी है — Mera ek saathi hai |  | C1 General Bhakthi* |
| 41 | जब कोई नहीं आता मेरे दादा — Jab koi nahi aata mere dada |  | C1 General Bhakthi* |
| 42 | आंगण उत्सव बनी आवो वृषभजी — Aangan utsav bani aavo Vrushabhji |  | C3 Adinath Bhagwan, C12 Classical Songs, C18 Palitana, C30 Utsah Songs |
| 43 | आ मारा महाराजजी — Aa mara Maharajji | image | C1 General Bhakthi* |
| 44 | तारो महिमा अपरंपार — Taro mahima aparampar |  | C12 Classical Songs |
| 45 | थनगनता जनजनना हैये (अंजननी वेळा) — Thanganta janjanna haiye (Anjan ni vela) |  | C22 Pratishta / Dhwaja* |
| 46 | रंग जामशे रे भक्ति रंग जामशे — Rang jamshe re bhakti rang jamshe |  | C1 General Bhakthi*, C22 Pratishta / Dhwaja* |
| 47 | केसर तिलक लगावो — Kesar tilak lagavo |  | C3 Adinath Bhagwan, C10 All Pooja*, C20 Parshwanath Bhagwan, C22 Pratishta / Dhwaja |
| 48 | हुं प्रभु मारो तुं — Hu prabhu maro tune |  | C11 Chetya Vandan Stavan |
| 49 | तेरे दरवाजे पर — Tere darwaze par |  | C1 General Bhakthi* |
| 50 | पंखिडा ओ पंखिडा — Pankhida o pankhida |  | C5 Fast Dance Number*, C30 Utsah Songs* |
| 51 | टीलडी रे मारा प्रभुजीने — Tiladi re mara prabhuji ne |  | C5 Fast Dance Number*, C30 Utsah Songs* |
| 52 | राजपथ पर जनारा — Rajpath par janara |  | C13 Diksha |
| 53 | ये तूने क्या किया × दीवाना तेरा आया — Ye tune kya kiya × Deewana tera aaya |  | C1 General Bhakthi*, C2 Slow Mashup* |
| 54 | आज आनंद अंग अंग जाग्यो — Aaj anand ang ang jagyo |  | C1 General Bhakthi, C3 Adinath Bhagwan, C5 Fast Dance Number, C7 Tapasya Bhakthi, C15 Grah Pravesh, C16 Mahaveer Swamy Bhagwan, C21 Prachin Stavan, C22 Pratishta / Dhwaja, C23 Rajendra Suriji, C30 Utsah Songs |
| 55 | तने रात दिवस हुं याद करुं — Tane raat divas hu yaad karu |  | C1 General Bhakthi* |
| 56 | तूने मुझे बुलाया — Tune mujhe bulaya |  | C1 General Bhakthi* |
| 57 | दादा जिनको याद करे वो — Dada jinko yaad kare wo |  | C1 General Bhakthi* |
| 58 | सजा दो घर को गुलशन सा — Sajado ghar lo gulshan sa |  | C1 General Bhakthi*, C15 Grah Pravesh* |
| 59 | दूर दूरथी — Dur dur thi |  | C1 General Bhakthi* |
| 60 | मेरे मन में पारसनाथ — Mere mann mein Parasnath |  | C20 Parshwanath Bhagwan* |
| 61 | ढूंढते रहते हैं आजकल — Dhoondhte rehte hain aajkal |  | C1 General Bhakthi* |
| 62 | नेमरस — Nemras |  | C4 Neminath Bhagwan, C5 Fast Dance Number, C14 Girnar, C30 Utsah Songs* |
| 63 | जय जय गरवो गिरनार — Jay jay garvo Girnar |  | C4 Neminath Bhagwan, C5 Fast Dance Number, C14 Girnar, C30 Utsah Songs* |
| 64 | नाम है तेरा तारणहारा — Naam hai tera taran hara |  | C5 Fast Dance Number, C30 Utsah Songs* |
| 65 | अलबेलो आदेश्वर — Albelo Aadeshwar |  | C3 Adinath Bhagwan, C5 Fast Dance Number, C18 Palitana, C30 Utsah Songs* |
| 66 | आओ दादा पधारो दादा — Aao dada padharo dada |  | C5 Fast Dance Number, C15 Grah Pravesh, C30 Utsah Songs* |
| 67 | एक बार मुखडो बताओ — Ek baar mukhdo batao |  | C9 Marvadi Songs, C30 Utsah Songs* |
| 68 | जीणो जीणो उडे रे गुलाल — Jino jino ude re gulaal |  | C9 Marvadi Songs, C30 Utsah Songs |
| 69 | धुलेवा नगरी में केसरिया विराजे — Dhulewa nagri mein Kesariya viraje |  | C3 Adinath Bhagwan, C5 Fast Dance Number*, C9 Marvadi Songs, C30 Utsah Songs* |
| 70 | म्हारो भेरू लगा दीजो पार — Maro bhedo laga dijo paar |  | C17 Nakoda Bherav, C30 Utsah Songs* |
| 71 | हे शत्रुंजय कुंडना — He Shatrunjay kundana |  | C3 Adinath Bhagwan*, C18 Palitana*, C30 Utsah Songs* |
| 72 | प्रभुजी तारा देशमां रेलगाडी आवी — Prabhuji tara desh ma rail gaadi aayi |  | C1 General Bhakthi*, C30 Utsah Songs* |
| 73 | ढोल बाजे ढोल बाजे — Dhol baje dhol baje |  | C30 Utsah Songs |
| 74 | रंगे रमे आ रंगे — Range rame ya range |  | C5 Fast Dance Number*, C9 Marvadi Songs, C30 Utsah Songs* |
| 75 | मारा दादाना दरबारे ढोल — Mara dada na darbare dhol |  | C5 Fast Dance Number*, C9 Marvadi Songs, C30 Utsah Songs* |
| 76 | सनेडो सनेडो लाल लाल — Sanedo sanedo laal laal |  | C1 General Bhakthi*, C5 Fast Dance Number*, C30 Utsah Songs* |
| 77 | आगमन तारुं आगमन — Aagman taro aagman |  | C25 Sahebji, C30 Utsah Songs* |
| 78 | लहरा दो — Lehra do |  | C22 Pratishta / Dhwaja, C30 Utsah Songs* |
| 79 | लेता म्हारा प्रभुजी रो नाम — Leta mara prabhuji ro naam |  | C1 General Bhakthi* |
| 80 | प्रभु वीर जनम्या आज — Prabhu Veer janmiya aaj |  | C16 Mahaveer Swamy Bhagwan* |
| 81 | तू वीर से दिल को लगा ले — Tu Veer se dil ko laga le |  | C16 Mahaveer Swamy Bhagwan |
| 82 | जय जयकार तपस्वीनो — Jay jay kar tapasvi no |  | C7 Tapasya Bhakthi |
| 83 | गा रहा सारा संसार, तपस्वी अमर रहे — Ga raha sara sansar, tapasvi amar rahe |  | C7 Tapasya Bhakthi |
| 84 | ढोल दी रा — Dhol di ra |  | C1 General Bhakthi*, C5 Fast Dance Number* |
| 85 | आदिनाथ मेडली — Adinath medley |  | C2 Slow Mashup*, C3 Adinath Bhagwan*, C18 Palitana*, C30 Utsah Songs* |
| 86 | मेरे सिर पर रखो दादा — Mere sir par rakho dada |  | C23 Rajendra Suriji |
| 87 | दिल में नाम तेरा है — Dil mein naam tera hai |  | C1 General Bhakthi* |
| 88 | दीन दुःखियानो — Din dukhiya na |  | C1 General Bhakthi* |
| 89 | जब जब दिल ये उदास होता है — Jab jab dil ye udaas hota hai |  | C1 General Bhakthi* |
| 90 | काजल टीको लगवाले — Kajal tiko lagwale |  | C1 General Bhakthi* |
| 91 | चालो जी चालो — Chalo ji chalo |  | C18 Palitana |
| 92 | तारा शरणे आव्यो छुं — Tara sharane aavyo chhu | image | C1 General Bhakthi, C23 Rajendra Suriji |
| 93 | रोमे रोमे हुं तारो — Rome rome hu |  | C1 General Bhakthi, C3 Adinath Bhagwan, C6 Bhaav Bhakthi, C8 Gujarati Songs, C14 Girnar, C18 Palitana, C20 Parshwanath Bhagwan, C21 Prachin Stavan, C25 Sahebji, C27 Sankeshwar, C29 Shantinath Bhagwan, C31 Simandhar Swamy Bhagwan |
| 94 | तारो ने मारो संबंध न्यारो — Taro ne maro | image | C1 General Bhakthi*, C3 Adinath Bhagwan |
| 95 | दुनिया से मैं हारा — Duniya se main haara |  | C23 Rajendra Suriji |
| 96 | चिंतामणि मारी चिंता चूर — Chintamani mari chinta chur (Aani mann shuddh aastha) | text | C1 General Bhakthi, C7 Tapasya Bhakthi, C11 Chetya Vandan Stavan, C15 Grah Pravesh, C20 Parshwanath Bhagwan, C21 Prachin Stavan*, C27 Sankeshwar |
| 97 | पार्श्वजिणंदा वामाजी के नंदा — Parshwajinanda Vamaji ke nanda | text | C20 Parshwanath Bhagwan*, C21 Prachin Stavan*, C27 Sankeshwar |
| 98 | मारो मुजरो ल्योने राज, साहिब शांति सलूणा — Maro mujro lyo ne raj (Shantinath) | text | C21 Prachin Stavan*, C29 Shantinath Bhagwan |
| 99 | तूं मने भगवान — Tu mane Bhagwan ek vardan aapi de | image | C1 General Bhakthi, C3 Adinath Bhagwan, C6 Bhaav Bhakthi, C7 Tapasya Bhakthi, C8 Gujarati Songs, C10 All Pooja, C14 Girnar, C15 Grah Pravesh, C16 Mahaveer Swamy Bhagwan, C17 Nakoda Bherav, C18 Palitana, C20 Parshwanath Bhagwan, C21 Prachin Stavan, C25 Sahebji, C27 Sankeshwar, C29 Shantinath Bhagwan, C31 Simandhar Swamy Bhagwan |
| 100 | अरहम अरहम — Arham arham (ajab dhun) |  |  |
| 101 | आंख मारी उघडे त्यां शंखेश्वर देखुं — Aankh mari ughade tya Shankheshwar dekhu |  | C20 Parshwanath Bhagwan*, C27 Sankeshwar |
| 102 | आंखडी मारी प्रभु हरखाय छे — Aankhdi mari prabhu harkhay chhe |  | C11 Chetya Vandan Stavan |
| 103 | आज देव देवीओ रंगे रमे — Aaj dev devio range rame |  |  |
| 104 | आज वगडावो वगडावो — Aaj vagdavo vagdavo |  | C30 Utsah Songs* |
| 105 | इतनी शक्ति हमें देना दाता — Itni shakti hamein dena data |  |  |
| 106 | ओ मारा रूपाळा भगवान — O mara rupala Bhagwan |  |  |
| 107 | केसरियो रंग जिनशासननो आपजो — Kesariyo rang Jinshasan no aapjo |  | C16 Mahaveer Swamy Bhagwan* |
| 108 | गाजे रे गाजे — Gaaje re gaaje (Veer nu shasan) |  | C16 Mahaveer Swamy Bhagwan*, C30 Utsah Songs* |
| 109 | चोख पुरावो — Chokh purao (aaj mere prabhu ghar aavenge) |  | C15 Grah Pravesh* |
| 110 | जिनवर तारुं शासन — Jinvar taru shasan |  |  |
| 111 | झगमगता तारलानुं — Jhagmagta tarla nu derasar |  |  |
| 112 | तन, मन, धन प्रभु ना चरणोमां — Tan man dhan prabhu na charanoma |  |  |
| 113 | तमे मन मूकीने वरस्या — Tame man mukine varasya |  |  |
| 114 | तारी गमती वातो — Tari gamti vato (He Jiravala) |  | C20 Parshwanath Bhagwan* |
| 115 | तारुं धार्युं बधुं थाय छे — Taru dharyu badhu thay chhe |  |  |
| 116 | तारे द्वारे आवीने कोई — Tare dware aavine koi |  |  |
| 117 | परमात्मा बनी जाशे मारो आत्मा — Parmatma bani jashe maro aatma |  | C3 Adinath Bhagwan, C8 Gujarati Songs, C22 Pratishta / Dhwaja* |
| 118 | दोष थी हैयो भर्यो छुं — Dosh thi haiyo bharyo chhu |  |  |
| 119 | धन्य धन्य बनावीश जन्म माहरो — Dhanya dhanya banavish janam maharo |  | C13 Diksha* |
| 120 | ऊंचा ऊंचा शत्रुंजयनां शिखरो सोहाय — Uncha uncha Shatrunjay na shikharo sohay |  | C3 Adinath Bhagwan*, C11 Chetya Vandan Stavan, C18 Palitana |
| 121 | नेमजी शामलीया — Nemji shamaliya (Girnare shobhe dekho) |  | C4 Neminath Bhagwan, C14 Girnar |
| 122 | प्रभु आवशे ने लई जाशे — Prabhu aavshe ne lai jashe |  | C13 Diksha* |
| 123 | प्रभुजी मांगुं तारी पास — Prabhuji mangu tari paas |  | C13 Diksha* |
| 124 | महावीर सा मुझको बन जाना है — Mahaveer sa mujhko ban jana hai |  | C16 Mahaveer Swamy Bhagwan* |
| 125 | मारी आंखोमां शंखेश्वर आवजो रे — Mari aankhoma Shankheshwar aavjo re |  | C20 Parshwanath Bhagwan*, C27 Sankeshwar |
| 126 | कभी प्यासे को पानी पिलाया नहीं — Kabhi pyase ko pani pilaya nahin |  |  |
| 127 | मुक्ति मळे के ना मळे — Mukti male ke na male |  |  |
| 128 | मुनि क्यारे बनीए — Muni kyare baniye |  | C13 Diksha* |
| 129 | रोमे रोमे गिरनार — Rome rome Girnar |  | C4 Neminath Bhagwan*, C14 Girnar |
| 130 | विरतिधरनो वेष — Virtidhar no vesh |  | C13 Diksha |
| 131 | समताथी दर्द सहुं — Samta thi dard sahu |  |  |
| 132 | सामुं जुओ ने — Samu juo ne |  | C6 Bhaav Bhakthi |
| 133 | हे प्रभु हे प्रभु — He prabhu he prabhu |  |  |
| 134 | विरति राग — Virti raag (Rushabh no marag, Nem no marag) |  | C13 Diksha* |
| 135 | गूंजे संयम नो जयकारा — Gunje sanyam no jaykara |  | C13 Diksha* |
| 136 | परम हर्ष पामुं वैराग्य — Param harsh pamu vairagya |  | C13 Diksha* |
| 137 | गुलाबी आंगी तारी — Gulabi aangi tari |  |  |
| 138 | मेरे दोनों हाथों में — Mere dono haathon mein (aisi lakeer hai) |  | C23 Rajendra Suriji |
| 139 | ओ प्यारा नाथ जी — O pyara nath ji |  |  |
| 140 | गिरिराज ना आदिनाथ — Giriraj na Aadinath |  | C3 Adinath Bhagwan, C18 Palitana* |
| 141 | हृदय मंदिरना मारा देव — Hriday mandir na mara dev |  |  |
| 142 | जब खिडकी खोलुं तो — Jab khidki kholu to |  |  |
| 143 | आवजो मन मंदिरिये — Aavjo man mandiriye (Sundar aa dehrama) |  | C3 Adinath Bhagwan, C6 Bhaav Bhakthi |
| 144 | तूने खूब दिया सब भगतों को — Tune khoob diya sab bhagton ko |  |  |
| 145 | मीठां आदिनाथ — Mitha Aadinath (Mithi Paldi gam) |  | C3 Adinath Bhagwan |
| 146 | तमे सुखदाता छो — Tame sukhdata chho |  |  |
| 147 | पार्श्व मीठा छे — Parshwa mitha chhe |  | C20 Parshwanath Bhagwan* |
| 148 | गिरनारे श्री प्रभु नेम छे — Girnare Shri prabhu Nem chhe |  | C4 Neminath Bhagwan*, C14 Girnar |
| 149 | केवा प्यारा लागे मारा पार्श्वनाथ दादा — Keva pyara lage mara Parshwanath dada |  | C20 Parshwanath Bhagwan |
| 150 | मन मोही लीधुं गिरनारे — Man mohi lidhu Girnare |  | C4 Neminath Bhagwan*, C14 Girnar |
| 151 | सिद्धाचलना शिखरोने वंदन — Siddhachal na shikharo ne vandan |  | C3 Adinath Bhagwan*, C18 Palitana* |
| 152 | केवा शोभे मारा जिनराया — Keva shobhe mara jinraya |  | C6 Bhaav Bhakthi |
| 153 | दर्शन देजो नाथ — Darshan dejo nath |  |  |
| 154 | हे शंखेश्वर स्वामी — He Shankheshwar swami |  | C20 Parshwanath Bhagwan*, C27 Sankeshwar |
| 155 | ऐ आत्मोद्धारे चाली गया — Ae aatmoddhare chali gaya |  |  |
| 156 | तारा देरेथी बोलावजो — Tara derethi bolavjo |  | C1 General Bhakthi* |
| 157 | रोम रोम में समाया पारसनाथ — Rom rom mein samaya Parasnath |  | C20 Parshwanath Bhagwan* |
| 158 | तुं एक ज छे मारो सथवारो — Tu ek ja chhe maro sathvaro |  |  |
| 159 | उंगली पकड मेरी — Ungli pakad meri |  |  |
| 160 | आव्या श्री जिनराज — Aavya Shri Jinraj |  |  |
| 161 | दुनिया से सहारा क्या लेना — Duniya se sahara kya lena |  |  |
| 162 | मारे तो लेवानी लेवानी छे दीक्षा — Mare to levani levani chhe diksha |  | C13 Diksha |
| 163 | बधाई — Badhai |  | C30 Utsah Songs* |
| 164 | रजा आपोने हवे दादा — Raja aapo ne have dada |  |  |
| 165 | मैशअप २ (हुं बाळ तमारो छुं…) — Mashup 2 — Hu baal tamaro chhu… |  | C2 Slow Mashup* |
| 166 | कुलपाक संग लगी प्रीतलडी (Mashup) — Kulpak sang lagi pritaldi (Kulpakji mashup) |  | C2 Slow Mashup* |
| 167 | केवा प्यारा लागे मारा नेमिनाथ दादा — Keva pyara lage mara Neminath dada | ⏳ | C4 Neminath Bhagwan |
| 168 | वीर मेरे पथ — Veer mere patha | ⏳ | C16 Mahaveer Swamy Bhagwan |
| 169 | वधावो वीर जिनवरने — Vadhavo Veer Jinvar ne | ⏳ | C16 Mahaveer Swamy Bhagwan |
| 170 | हेलो मारो सांभळो — Helo maro sambhalo | ⏳ | C16 Mahaveer Swamy Bhagwan |
| 171 | खम्मा घणी खम्मा घणी — Khamma ghani khamma ghani | ⏳ | C7 Tapasya Bhakthi |
| 172 | तमे उत्सव आज मनावो — Tame utsav aaj mandavo | ⏳ | C7 Tapasya Bhakthi |
| 173 | करके तपस्या तप को तपाया — Kar ke tapasya tab ko tapasya | ⏳ | C7 Tapasya Bhakthi |
| 174 | त्याग समर्पण और संयमता — Tyaag samarpan aur saiyamta | ⏳ | C7 Tapasya Bhakthi |
| 175 | तपस्या करता करता हो — Tapasya karta karta ho | ⏳ | C7 Tapasya Bhakthi |
| 176 | वैरागीने वंदन — Vairagi ne vandan | ⏳ | C13 Diksha |
| 177 | झूमे रे झूमे — Jhume re jhume | ⏳ | C13 Diksha |
| 178 | मेरे साहेब ने मुझको बहुत कुछ दिया — Mere saheb ne mujhko bohot kuch diya | ⏳ | C6 Bhaav Bhakthi, C25 Sahebji |
| 179 | ऋषभ जिणंद — Rishab jinand | ⏳ | C11 Chetya Vandan Stavan |
| 180 | ओ गुरु सा थारो चेलो बनुं मैं — O guru sa thaaro chelo banu main | ⏳ | C1 General Bhakthi, C7 Tapasya Bhakthi, C9 Marvadi Songs, C10 All Pooja, C15 Grah Pravesh, C17 Nakoda Bherav, C20 Parshwanath Bhagwan, C23 Rajendra Suriji, C25 Sahebji, C28 Shanti Suriji, C29 Shantinath Bhagwan |
| 181 | केवा प्यारा लागे मारा शांतिनाथ दादा — Keva pyara lage mara Shantinath dada | ⏳ | C29 Shantinath Bhagwan |
| 182 | मेरुशिखर न्हवरावे — Merushi karnav | ⏳ | C10 All Pooja |
| 183 | तू कितनी अच्छी है — Tu kitni achhi hai | ⏳ | C24 Rishto ki Dor |
| 184 | ये दोस्ती हम नहीं तोड़ेंगे — Yeh dosti hum nahi todenge | ⏳ | C24 Rishto ki Dor |
| 185 | एक दूसरे से करते हैं प्यार हम — Ek dusre se karte hai pyaar hum | ⏳ | C24 Rishto ki Dor |
| 186 | चंदा ने पूछा तारों से — Chanda ne poocha taaron se | ⏳ | C24 Rishto ki Dor |
| 187 | फूलों का तारों का — Phoolon ka taaron ka | ⏳ | C24 Rishto ki Dor |
| 188 | ज़माने में कब कहां — Zamane mein kab kahan | ⏳ | C17 Nakoda Bherav, C20 Parshwanath Bhagwan |
| 189 | म्हारा नाकोडा रा नाथ — Mara Nakoda ra nath | ⏳ | C17 Nakoda Bherav |
| 190 | आंगी (शांति सूरीजी) — Aangi (Shanti Suriji) | ⏳ | C28 Shanti Suriji |
| 191 | फूल (शांति सूरीजी) — Phool (Shanti Suriji) | ⏳ | C28 Shanti Suriji |
| 192 | जय जय आरती — Jay Jay Aarti (Aadi Jinanda) | text | C32 Aarti |
| 193 | मंगल दीवो — Mangal Divo (Divo re divo) | text | C32 Aarti |
| 194 | गुरुदेव आरती — Gurudev Aarti | ⏳ | C32 Aarti |
| 195 | सुणो चंदाजी सीमंधर परमातम पासे — Suno Chandaji Simandhar parmatam pase | ⏳ | C31 Simandhar Swamy Bhagwan |
