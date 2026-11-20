# Mahbubul Alam | Developer & Geospatial Researcher Portfolio

A modern, responsive, single-page portfolio for **Mahbubul Alam**, a full-stack developer (TypeScript, React, Next.js, Node.js) and geospatial researcher working on remote sensing, LiDAR and urban climate.

**Live site:** https://delightful-gingersnap-cd02bd.netlify.app/
**GitHub:** https://github.com/Mahbubenvit
**LinkedIn:** https://www.linkedin.com/in/mahbubul-alam-7022b5a9

---

## Features

- **Responsive navbar** with active-section highlighting and a mobile menu
- **Hero section** with designation (typing animation), profile photo, animated particle background and a **View / Download Resume** button
- **Social links** to GitHub and LinkedIn
- **About me**: programming journey, background and interests
- **Global footprint**: study and research across Bangladesh, Germany, Poland, Spain, Austria and Italy
- **Skills**: categorised, graphical skill cards with animated progress rings and a moving tech-stack marquee
- **Education** and **Experience** timelines
- **Research projects** (9 projects): GIS, remote sensing, LiDAR, solar and site-suitability analysis, each with a detail page (stack, description, challenges, future plans, image gallery)
- **Publications & conferences**: peer-reviewed journal article and conference papers (MDPI ECRS-6, AGIT 2026, IEEE GRSS SYP 2026) with links, posters and certificates
- **Awards, scholarships & certificates**: Deutschlandstipendium, DAAD, Erasmus+, UNU-FLORES, UFZ, SAP, Esri; filterable, with a full-size view of each document
- **Web development projects**: live apps with screenshots, live links and GitHub (client) repos
- **Contact**: email, phone and WhatsApp, with contact details stored encoded in the page to reduce spam scraping
- **Footer** with quick links and social icons
- Scroll progress bar, reveal-on-scroll animations, image lightbox and back-to-top button
- Respects `prefers-reduced-motion`

## Tech stack

| Area | Used |
|---|---|
| Markup & style | HTML5, CSS3 (custom properties, Grid, Flexbox, keyframe animations) |
| Interactivity | Vanilla JavaScript (hash routing, IntersectionObserver, Canvas) |
| Fonts | Manrope, Work Sans (Google Fonts) |
| Hosting | Vercel / Netlify (static, no build step) |

## Project structure

```
updateportfolio/
├── index.html                  # Entire site: HTML, CSS and JS
├── hero.jpg                    # Profile photo
├── Mahbubul_Alam_Resume.pdf    # Resume (view / download)
├── shots/                      # Web project screenshots
├── gis/                        # Research maps and figures
├── conf/                       # Conference photos, poster, certificates
├── awards/                     # Scholarships and certificates
└── README.md
```

## Run locally

No installation needed.

```bash
git clone https://github.com/Mahbubenvit/updateportfolio.git
cd updateportfolio
# open index.html in a browser, or serve it:
npx serve .
```

## Deploy

**Vercel:** Add New → Project → import `updateportfolio` → Framework: *Other*, no build command → Deploy.
**Netlify:** Add new site → Import from GitHub → `updateportfolio` → leave the build command empty, publish directory `/` → Deploy.

Every push to `main` redeploys the site automatically.

## Contact
**Mahbubul Alam**, Dresden, Germany
https://delightful-gingersnap-cd02bd.netlify.app/#home

---

© 2026 Mahbubul Alam. All rights reserved.
