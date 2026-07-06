# SA Global Group — Institutional Staging Environment

A minimalist, high-end corporate institutional mockup built as a single-page, infinite-scroll static website. This project serves as a fully secured, liability-free staging preview designed with strict technical and structural guardrails.

## 🛠 Tech Stack & Architecture

*   **Frontend Base:** Vanilla HTML5 / JavaScript (Single-file deployment via `index.html`)
*   **Styling Engine:** Tailwind CSS via CDN (Strict Light Theme configuration)
*   **Typography:** Playfair Display (Headings) & Inter (Body) via Google Fonts
*   **Hosting Platform:** Vercel (Static edge distribution)
*   **Infrastructure Insights:** Integrated Vercel Web Analytics (`/_vercel/insights/script.js`)

## 🔒 Defensive Guardrails & Security Injections

This staging codebase implements a "glass house" architecture designed to protect intellectual property and establish explicit conceptual boundaries:

1.  **Invisible DOM Watermark:** A self-executing script generates an immutable, repeating fragment (`CONCEPTUAL MOCKUP - NO LEGAL ENTITY`) directly behind the visual layout layer. It is hidden from standard rendering but permanently woven into the DOM tree to invalidate unapproved scraping.
2.  **DevTools Sentry:** High-visibility console warnings flag the property as a non-functional UI demo upon inspection.
3.  **Link Insulation & Interstitials:** Active click-intercept event listeners catch external social routings, enforcing explicit user confirmation prompts before breaking the staging perimeter.
4.  **Asynchronous Report Interceptor:** Core CTA endpoints link to standard `#` hooks paired with explicit prompt alerts, mitigating the risk of distributing unapproved third-party financial or corporate prospectuses.

## 📁 Repository Structure

```text
├── assets/
│   ├── logo-2-615928933...jpg          # Primary corporate branding asset
│   ├── 649086863_1222...jpg            # Parallax-fixed hero background
│   ├── 469813150_1359...jpg            # Portfolio image asset 1
│   └── texas-480926220...jpg            # Portfolio image asset 2
└── index.html                           # Unified 875-line deployment artifact
