# PlaceTrack — Placement Management Portal

A UI/UX design case study and interactive prototype built to demonstrate end-to-end product design skills — from identifying usability problems to delivering a high-fidelity, interactive solution.

🔗 **[Live Demo](https://adhithyababu.github.io/placement-portal-ux)**

---

## The Problem

My original placement portal had several usability issues common in early-stage product design:

| Issue | Impact |
|---|---|
| Login form had no branding or app context | Users had no sense of what product they were signing into |
| Stat cards used light fills on a dark background | Clashed visually, broke the dark theme's consistency |
| Sidebar had no active state or icons | No visual feedback on where the user currently was |
| Dashboard lower half was completely empty | Wasted screen real estate, no useful information |
| All text had the same visual weight | No hierarchy — nothing guided the user's eye |

---

## The Solution

A redesigned, fully interactive prototype applying human-centered design principles:

### Login screen
- Split-panel layout: left side establishes brand identity and trust (product name, tagline, social proof stats); right side is focused on the login form
- Role toggle (Student / Admin) for dual-user architecture
- Clear field labels, focus states, and a contextual CTA button

### Dashboard
- KPI cards with dark-tinted fills consistent with the overall theme
- Color-coded icons that encode meaning (blue = volume, amber = urgency, green = success)
- Activity feed replacing empty whitespace with time-stamped, contextual updates
- Sticky topbar with search and notifications

### Applications view
- Filter chips for multi-attribute segmentation (All / Applied / Interview / Offer / Not selected)
- Color-coded company logos and status badges for quick scanning
- Clean data table with hover states

### Profile view
- Structured layout with skill pills, progress bars, and application analytics
- Clear information hierarchy using label → value patterns

---

## Design Decisions

**Why dark theme?** Enterprise and placement tools are used for extended sessions. Dark themes reduce eye strain and feel premium in a B2B context.

**Why split-panel login?** The left panel removes cognitive uncertainty — the user instantly knows what PlaceTrack is and why they should trust it. This is a standard pattern in B2B SaaS (Notion, Linear, Vercel).

**Why color-coded status badges?** In a list of 12+ applications, a user needs to triage at a glance. Color + label (not color alone) ensures accessibility.

**Why progress bars on the profile?** Placement portals benefit from gamification cues — showing 85% profile completion motivates users to complete their data, which improves admin-side analytics.

---

## Tools & Skills Demonstrated

- **Figma** — wireframing, component design, interaction flows (design process)
- **HTML / CSS / JavaScript** — high-fidelity interactive prototype
- **Design thinking** — problem identification → user flow → solution → iteration
- **Human-centered design** — accessibility, visual hierarchy, usability principles
- **B2B UI patterns** — data tables, filter systems, dashboard KPIs, sidebar navigation

---

## Screens

| Screen | Description |
|---|---|
| Login | Branded split-panel with role toggle |
| Dashboard | KPI cards + activity feed |
| Applications | Filterable data table with status tracking |
| Profile | User details + skill tags + progress analytics |

---

## How to Run Locally

```bash
# Just open the file — no build step needed
open index.html
```

Or deploy to GitHub Pages:
1. Fork / clone this repo
2. Go to Settings → Pages
3. Set source to `main` branch → `/ (root)`
4. Your live URL: `https://YOUR-USERNAME.github.io/placement-portal-ux`

---

## About

Designed and built by **Adhithya Babu** — Full Stack Developer & aspiring UI/UX Designer.

- 📧 adhithyababu003@gmail.com
- 💼 [linkedin.com/in/adhithyababuu](https://linkedin.com/in/adhithyababuu)
- 🗂 Part of my UI/UX design portfolio

---

> *This project is a UI/UX case study prototype. Data shown is for demonstration purposes only.*
