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



# 🎨 General Design System – Flight Booking Website

## 🧱 Overview
A unified visual language for all pages, ensuring **consistency, clarity, and responsiveness**.  
The design aims to evoke **trust, simplicity, and a modern travel experience**.

---

## 🎨 Color Palette

| Purpose | Variable | Color | Usage |
|----------|-----------|-------|--------|
| **Background** | `--bg` | `#F7FAFC` | Light neutral background for clarity. |
| **Surface (cards, navbar)** | `--surface` | `#FFFFFF` | White background for elevated elements. |
| **Primary (Brand)** | `--primary` | `#0A66C2` | Main airline blue tone for links and buttons. |
| **Primary Hover** | `--primary-600` | `#0959A9` | Darker shade for hover interactions. |
| **Accent (CTA / Highlights)** | `--accent` | `#FFB100` | Used for “Book Now” buttons or promotions. |
| **Accent Hover** | `--accent-600` | `#E6A100` | Slightly darker accent hover color. |
| **Text (Main)** | `--text` | `#0F172A` | Strong, readable text color. |
| **Text (Muted)** | `--text-muted` | `#475569` | For secondary information and placeholders. |
| **Borders / Lines** | `--line` | `#E2E8F0` | Light dividers between sections. |
| **Success / Error** | `--success` / `--danger` | `#16A34A` / `#DC2626` | For form feedback messages. |

---

## ✍️ Typography

| Type | Font Size | Weight | Notes |
|------|------------|---------|-------|
| **h1** | 40px (mobile: 32px) | 700 | Main page titles |
| **h2** | 28px (mobile: 24px) | 700 | Section titles |
| **h3** | 22px | 600 | Subtitles |
| **Paragraph (p)** | 16px | 400 | Main text |
| **Small / Note** | 14px | 400 | Secondary info, hints |

- **Font Family:** `"Heebo", "Rubik", Arial, "Segoe UI", sans-serif`
- **Line height:** `1.6`
- **Base font size:** `16px`

---

## 📏 Spacing & Sizing
- **Spacing scale (px):** 4, 8, 12, 16, 24, 32, 48, 64  
- **Button/Input height:** 44–48px  
- **Card padding:** 16–24px  
- **Icon size:** 20–24px  
- **Border radius:** 12px (rounded corners)  
- **Container max width:** `1200px`

---

## 📱 Breakpoints (Responsive Design)
| Device | Width |
|---------|--------|
| **Mobile** | ≤480px |
| **Tablet** | 481–768px |
| **Laptop** | 769–1024px |
| **Desktop** | ≥1280px |

---

## 🧩 UI Components

### 🧭 Navbar
- Sticky top bar with white background and subtle shadow.  
- Height: 64–72px.  
- Logo on the right (RTL) or left (LTR), and CTA button on the opposite side.  

### 💳 Cards
- Background: white (`--surface`)  
- Rounded corners (`12px`)  
- Drop shadow for elevation (`var(--shadow-1)`)  
- Internal padding: `16–24px`  
- Contains: image (16:9 ratio), title, short description, and “Book Now” button.

### 🧾 Forms
- Input height: `48px`, border: `1px solid var(--line)`  
- Focus state: border-color `--primary`, light blue focus ring.  
- Error messages: red text (`--danger`), small font.  
- Submit button: primary or accent color.

### 💰 Tables
- Clean table with subtle borders (`--line`)  
- Header row (`<thead>`) has gray background `#F1F5F9`  
- Right-aligned numeric values for RTL text.  

### 🔘 Buttons
| Type | Background | Text | Border | Use |
|------|-------------|------|--------|-----|
| **Primary** | `--primary` | White | None | Main actions |
| **Accent** | `--accent` | Dark text | None | CTA / promotions |
| **Secondary** | `--surface` | `--text` | `--line` | Neutral actions |

- Hover: darker shade  
- Active: light translateY(1px) effect  
- Border radius: 12px

---

## 🌈 Accessibility
- **Contrast ratio:** minimum 4.5:1 for body text.  
- **Alt text:** required for all images.  
- **Keyboard focus:** clear visible outline.  
- **Responsive typography:** scales at 480px and 1024px.  

---

## 🧱 Example CSS Variables (Base Styles)

```css
:root {
  --bg: #F7FAFC;
  --surface: #FFFFFF;
  --text: #0F172A;
  --text-muted: #475569;
  --line: #E2E8F0;
  --primary: #0A66C2;
  --primary-600: #0959A9;
  --accent: #FFB100;
  --accent-600: #E6A100;
  --success: #16A34A;
  --danger: #DC2626;
  --font-family: "Heebo", "Rubik", Arial, "Segoe UI", sans-serif;
  --radius: 12px;
  --container: 1200px;
  --shadow-1: 0 2px 10px rgba(15, 23, 42, 0.06);
  --shadow-2: 0 10px 30px rgba(15, 23, 42, 0.12);
}
```

---

## ✈️ Summary
This shared design system provides:
- **Consistent colors and spacing** across all pages.  
- **Readable, modern typography** optimized for Hebrew and English.  
- **Accessible and responsive** layouts that adapt to any device.  
- **Reusable components** (navbar, cards, forms, tables, buttons) that keep the site cohesive.

---

✅ **Goal:** Both partners use this same design base so that each page feels unified and professional.





## 🌈 Optional Enhancements
- Tiny JS: hamburger menu, image carousel.
- `thank-you.html` after form submissions.
- Basic SEO tags (`title`, `meta description`).

We don't use localestorage on this part
We will make like it work, but it s not

## 🧑‍💻 Authors
**Partner A:** Guedalia
**Partner B:** Nerya 
