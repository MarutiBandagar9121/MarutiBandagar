# Maruti Portfolio (React)

Personal portfolio site for **Maruti Bandagar**, a full-stack developer — built with React, TypeScript, and Tailwind CSS.

> **Status: retired.** This was my portfolio site, previously deployed to GitHub Pages. It's no longer hosted — I've since moved to a new portfolio. This repo is kept around as a reference / for its code.

## Tech Stack

| Layer | Tool |
|---|---|
| Framework | React 19 + TypeScript 5.4 |
| Build | Vite 5 |
| Styling | Tailwind CSS 3 |
| Routing | React Router DOM 6 |
| Animation | Framer Motion 11 |
| Icons | @remixicon/react |
| Deployment | gh-pages → GitHub Pages |

## Features

- **Home** — Hero, About, Skills, Work Experience, Projects, and Contact sections composed on a single page
- **Project Details** — dedicated route per project with tech stack, highlights, and links to source
- **Resume downloads** — PDF resume served as a static asset
- Scroll-triggered animations throughout via Framer Motion
- Fully responsive, dark-themed UI

## Project Structure

```
src/
├── components/       # Navbar, Hero, About, Skills, WorkExperience, Projects, Contact
├── pages/            # Home.tsx (section composition), ProjectDetails.tsx
├── data/             # projectsData.ts (all project content)
├── App.tsx           # Router setup
└── index.css         # Tailwind base imports

public/
├── images/           # Profile photo, project screenshots, contact illustration
└── svg/              # SVG assets

resumes/              # Resume PDFs (served as static assets)
```

## Getting Started

```bash
npm install
npm run dev       # start the Vite dev server
```

Other scripts:

```bash
npm run build     # type-check + build to dist/
npm run preview   # preview the production build locally
npm run deploy    # build + publish to GitHub Pages (gh-pages)
```

> Note: `npm run deploy` and the `homepage` field in [package.json](package.json) still point at the old GitHub Pages URL from when this site was live. They're left as-is for historical accuracy rather than actively used.

## Author

**Maruti Bandagar**
[GitHub @MarutiBandagar9121](https://github.com/MarutiBandagar9121)
