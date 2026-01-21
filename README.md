# My Personal Website

[Live Site](https://www.sterling-miller.tech) • Built with Astro + Tailwind, Deployed using Vercel  
![Astro](https://img.shields.io/badge/astro-red?logo=astro&logoColor=red&labelColor=gray)
![Tailwind CSS](https://img.shields.io/badge/tailwind-blue?logo=tailwind-css&labelColor=gray)
![Vercel](https://vercelbadge.vercel.app/api/sterling-miller/Personal-Website)

A fast, responsive personal portfolio built to showcase my profile, work experience, education, and projects.

Tech stack
- Framework: Astro
- Styling: Tailwind CSS
- Deployment: Vercel
- Formatter: Prettier (with Astro plugin)

## Getting started

Prerequisites
- Node.js v16+ (or your preferred runtime)
- bun (if you prefer) or npm/yarn/pnpm

Install and run
```bash
# clone
git clone https://github.com/Sterling-Miller/personal-website.git
cd personal-website

# using bun
bun install
bun run dev

# or npm
npm install
npm run dev
```

Open http://localhost:4321/ in your browser.

Build and preview
```bash
# build
bun run build   # or npm run build

# preview
bun run preview # or npm run preview
```

Project structure
- src/         — site source (pages, components)
- public/      — static assets (images, favicon)
- astro.config.ts
- package.json

Deployment
- Recommended: Vercel — connect your repo and set the build command (bun run build or npm run build).
- Example: deploy with one-click Vercel button in the repo.

## Template

This project is based on an Astro template provided by Vercel. The template has been customized to include my personal content and design preferences. Deploy your own Astro project using Vercel:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/vercel/examples/tree/main/framework-boilerplates/astro&template=astro)

_Live Example: https://astro-template.vercel.app_
