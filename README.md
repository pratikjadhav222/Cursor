# Cursor Landing Page – Recreation

A desktop-first HTML/CSS recreation of the [Cursor](https://cursor.com) developer tool landing page.

## Sections Recreated

1. **Top Navigation Bar** – Logo, nav links, Login + Download CTA, dark background
2. **Hero Section** – Large headline, description, CTA buttons, full code editor mockup with AI panel
3. **Trusted By / Logos** – Row of company names (OpenAI, Stripe, Shopify, Vercel, etc.)
4. **Feature Sections (3 blocks)** – Tab completions, Chat, and Composer — alternating text/visual layout
5. **Feature Cards** – 4-card grid (Cmd+K, Context, Privacy Mode, BYOK)
6. **Testimonials** – 6 quote cards in a 3-column grid with author names and roles
7. **Use Cases** – 3 cards (Startups, Enterprise, Students) with visual headers
8. **Changelog / Updates** – Timeline-style list of 5 recent updates with dates
9. **Team / About** – Two-column: team visual + description + CTA
10. **Final CTA** – Large heading + single Download button
11. **Footer** – 5-column layout (Brand, Product, Resources, Company, Legal)

## Fonts Used

- **Geist** (Google Fonts) — weights 300–900
- Same font family used on the actual Cursor website

## Colors Used

| Token | Value | Usage |
|-------|-------|-------|
| Background | `#0c0c0c` | Page background |
| Surface | `#141414` | Cards, editor |
| Surface 2 | `#1c1c1c` | Topbars, sidebars |
| Border | `#262626` | Dividers |
| Text Primary | `#f5f5f5` | Headings |
| Text Secondary | `#a3a3a3` | Body text |
| Text Muted | `#666` | Labels, dates |
| Accent White | `#ffffff` | CTAs, logo |
| Code Green | `#86efac` | String literals |
| Code Blue | `#60a5fa` | Functions, props |
| Code Purple | `#c084fc` | Keywords |
| Code Yellow | `#fbbf24` | Types |

## Constraints Met

- ✅ HTML and CSS only
- ✅ No JavaScript
- ✅ No TailwindCSS
- ✅ No animations
- ✅ Desktop-only layout (min-width: 1280px)

## How to Run

Open `index.html` directly in any browser. No build step or server needed.

```bash
open index.html
```

## Hosting on GitHub Pages

1. Push to a public repo
2. Go to Settings → Pages → Deploy from main branch
3. Live at `https://username.github.io/repo-name`
