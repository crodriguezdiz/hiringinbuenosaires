# Hiring in Buenos Aires — One-Pager

A self-contained HTML page covering everything a hiring manager or recruiter needs to know about sourcing technical talent in Buenos Aires, Argentina.

---

## What's inside

| Section | Description |
|---|---|
| **Main hubs** | Interactive tab view of Buenos Aires, Córdoba and Mendoza with metrics and a side-by-side comparison |
| **Talent availability** | Role mix chart showing relative volume of Frontend, Backend and Data Engineering profiles |
| **Universities** | Overview of Argentina's higher education system and top technical institutions |
| **Compensation** | Employment model, contractor structures, talent insights and macroeconomic context |
| **Hiring strategies** | Market context and actionable strategies to attract and retain senior tech talent |
| **Cultural context** | Communication style, work priorities and collaboration norms for Argentine teams |

---

## How to use

The entire page lives in a single file: **`argentina-onepager.html`**

**View locally**
Just open the file in any browser — no server or installation needed.

**Share with your team**
The easiest way to publish it so others can see the live page (not the raw HTML):

1. Go to **[netlify.com/drop](https://netlify.com/drop)**
2. Drag and drop `argentina-onepager.html` onto the page
3. Rename the file to `index.html` before dropping if you want a cleaner URL
4. Netlify gives you a public link instantly — share it via Slack or email

Alternatively, deploy via **GitHub Pages**:
1. Create a new repository on github.com
2. Upload the file renamed as `index.html`
3. Go to Settings → Pages → select branch `main`
4. Your page will be live at `yourusername.github.io/repo-name`

---

## Editing the content

All content and styles are in the single HTML file. The key areas to update:

- **Section content** — find the `<section id="...">` block for the section you want to edit
- **Hub data** — inside `<section id="main-hubs">`, each hub has its own `<div class="hub-panel">` block
- **Footer contacts** — at the bottom of the file, find the `<div class="contacts">` block and add or edit `.contact-btn` entries
- **Colors** — all colors are CSS variables defined in `:root` at the top of the `<style>` block

---

## Team contacts

Reach out in Slack if you have questions about the content:

- **Kabi Gishuru** — Director, Talent Acquisition
- **Caro Diz Rodriguez** — Lead Tech Recruiter
- **Aman Sheena** — Senior Manager, Talent
- **Malena Pham** — Recruiting Coordinator
