# ✈️ Flight Booking Website  
### *Full-Stack Web Development – Static Website Project (Units 13–20)*

## 📘 Project Overview
A **static, responsive, and content-rich** website simulating an **international flight booking service**.  
Covers semantic HTML, CSS Grid/Flexbox, forms, tables, media, internal/external links, and full responsiveness.

## 🎯 Objectives
- Build a **multi-page static site** with **HTML5 + CSS3**.  
- Use **semantic HTML**, **Grid**, and **Flexbox**.  
- Include **forms**, **tables**, **media embeds**, and **anchors/links**.  
- Ensure **mobile/tablet/desktop** responsiveness.  
- **Equal remote collaboration** in pairs via GitHub.

## 🧭 Sitemap
| Page | File | Description |
|---|---|---|
| **Home** | `index.html` | Deals banner, flight search form, popular destinations, internal/external links. |
| **Destinations** | `destinations.html` | Grid of regions (Europe/Asia/America), images, short copy, sample “from ₪”. |
| **Flight Details** | `flight.html` | Airline, schedule, **price table** (class/baggage), **booking form**, related flights. |
| **About Us** | `about.html` | Company story, trust & service section, **embedded video/map**. |
| **Contact** | `contact.html` | **Full form** (name/email/phone/subject/message/select/checkbox), **hours table**, map iframe. |
| **FAQ** | `faq.html` | Lists of Q&A on booking, cancellations, insurance, name changes. |
| **Policy** | `policy.html` | Clear policy with internal anchors (pricing/cancellations/changes). |
| **Gallery** | `gallery.html` | Destination photo **Grid** with `figure/figcaption`. |

## 🧩 Tech & Features
- **Semantic HTML5**: `header`, `nav`, `main`, `section`, `article`, `aside`, `footer`.
- **Links**: ≥3 internal + ≥3 external across the site.
- **Media**: `img`, optional `video`/`audio`, required `iframe`/`embed`.
- **Tables & Forms**: pricing/booking/hours.
- **Responsive (Media Queries)**:
  - Mobile ≤480px | Tablet 481–1024px | Desktop ≥1025px.
- **Grid** for catalog/gallery, **Flexbox** for nav/cards/forms.
- **Accessibility**: `alt`, labels, focus, contrast.
- **Light animations**: `transition`, `:hover`, `@keyframes`.

## 🗂️ Folder Structure
```
/project-root
  /assets
    /images
    /media
    /icons
  /css
    base.css
    layout.css
    components.css
    pages.css
  /js
    main.js
  index.html
  destinations.html
  flight.html
  about.html
  contact.html
  faq.html
  policy.html
  gallery.html
```

## 👥 Equal Remote Work (Rotation)
**Shared foundation**
- **Git/GitHub** with branches: `main`, `feature/home`, `feature/destinations`, `feature/flight`, `feature/contact`, `feature/about`, `feature/faq`, `feature/policy`, `feature/gallery`.  
- **PR workflow**: feature branch → PR with screenshots → partner review → merge.  
- **Issues/Milestones**: small tasks per page/section/form/table/media/responsiveness.

**Rotation 1 (~7–8h)**
- **Partner A**: **Home** (Hero + Search + Popular Destinations) + **Gallery**; set up global CSS (`base/layout/components`) and navbar/footer.
- **Partner B**: **Destinations** (Grid + static anchors/filters) + first **Flight Details** page (price table + booking form + related flights).

**Rotation 2 (~7–8h)**
- **Partner A** → **Contact** (full form + hours table + map/video) + **FAQ** (lists + anchors).
- **Partner B** → **About** + **Policy** (rich text, links, embed).
- Each partner adds **media queries** (2–3 sizes) to their pages and does an **accessibility** pass.

## 📅 Timeline by Units (20–24h)
- **Unit 13 (~3h)**: research, wireframes (paper/Figma), sitemap, color/typography decisions, repo & scaffolding.
- **Units 14–18 (~15h)**: build per rotations + interim reviews and merges.
- **Unit 19 (~3h)**: responsive/accessibility checks, link validation, micro-animations, image compression, CSS cleanup.
- **Unit 20 (~3h)**: “Site Map” page for demo, 50/50 presentation split.

## ✅ Page Checklist
- [ ] `h1` + meaningful `h2` sections.
- [ ] Internal + external links.
- [ ] Images with descriptive `alt`.
- [ ] **Grid/Flex** layout.
- [ ] ≥1 breakpoint (preferably 2).
- [ ] Forms: `label`, `required`, submit to `thank-you.html`.
- [ ] Tables: `<caption>`, `<thead>/<th>`; clear structure.

## 🧪 Definition of Done
- [ ] Looks great on mobile/tablet/desktop (no unwanted horizontal scroll).
- [ ] No broken links.
- [ ] Clean separation (HTML/CSS/Media).
- [ ] Basic accessibility (alt/labels/focus/contrast).
- [ ] PR with description & screenshots approved by partner.

## 📋 Starter Task Board
| Task | Primary (Round 1) | Secondary (Rotation) | Status |
|---|---|---|---|
| Repo + structure + base CSS | Both | — | ☐ |
| Home (Hero, Search, Highlights) | A | B (responsive/polish) | ☐ |
| Destinations (Grid + static filters) | B | A | ☐ |
| Flight Details (table + form) | B | A | ☐ |
| Contact (full form + map) | A | B | ☐ |
| FAQ (lists + anchors) | A | B | ☐ |
| About (media/embed) | B | A | ☐ |
| Policy (text + anchors) | B | A | ☐ |
| Gallery (Grid + captions) | A | B | ☐ |
| Responsiveness (all pages) | Both | Both | ☐ |
| Final QA + light animations | Both | — | ☐ |
| “Site Map” demo page | Both | — | ☐ |

## 🌈 Optional Enhancements
- Tiny JS: hamburger menu, image carousel.
- `thank-you.html` after form submissions.
- Basic SEO tags (`title`, `meta description`).

We don't use localestorage on this part
We will make like it work, but it s not

## 🧑‍💻 Authors
**Partner A:** Guedalia
**Partner B:** Nerya 
