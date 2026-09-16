# Allan Munyira — Personal Portfolio

Static, responsive personal portfolio for **Allan Munyira**, built from his resume. Dark professional cybersecurity aesthetic with a warm charcoal + amber palette (intentionally distinct from [muncyber.com](https://muncyber.com) cyan/navy branding).

## Contents

```
allan-portfolio/
├── index.html
├── README.md
├── SYNC-TO-DOWNLOADS.json
├── assets/
│   └── Allan-Munyira-Resume.docx
├── css/
│   └── styles.css
└── js/
    └── main.js
```

## Sections

- **Hero** — name, summary, CTAs (email, LinkedIn, resume download)
- **About** — professional summary from the resume
- **Skills** — cybersecurity, programming, tools
- **Projects** — AI SOC Analyst Assistant & Mun Cyber Eye (marked under development)
- **Experience** — Mun Cyber Technologies, Yeshiva SOC trainee, Makerere MIIC, Ison BPO
- **Education** — M.S. Cybersecurity (Yeshiva), B.S. Software Engineering (Makerere)
- **Contact** — mailto form + direct links

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
npx --yes serve .
# or: python3 -m http.server 8080
```

## Accessibility & design

- Semantic HTML5 landmarks and headings
- Skip link, focus-visible styles, `aria-expanded` mobile nav
- Mobile-first layout with sticky header
- `prefers-reduced-motion` respected
- Resume downloadable from `assets/Allan-Munyira-Resume.docx`

## Credentials policy

All content is taken from the resume extract. Projects are labeled **under development**. No invented certifications or tools.

## Zip package

Parent folder zip: `/workspace/Allan-Munyira-Portfolio.zip`
