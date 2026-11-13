# vishalkiran.raichur — portfolio

Live at **https://vishalkiran-raichur.com**

Multi-page portfolio built with [Astro](https://astro.build). Static, no client framework.

## Pages
`/` · `/projects` · `/projects/{orion,pulsegrid,forgedb,job-beast,sla-copilot,luminara,ivk-media}` · `/work` · `/about` · `/resume` · `/contact`

## Run locally
```bash
npm install
npm run dev      # http://localhost:4321
npm run build    # outputs to dist/
```

## Edit
- Shared nav, footer, ⌘K search: `src/layouts/Layout.astro`
- Search entries, email and links: `src/data.js`
- Colors, fonts, base styles: `src/styles/global.css`
- Each page: `src/pages/**.astro`
- Images: `public/img/` · Résumé PDF: `public/Vishalkiran_Raichur_Resume.pdf`

## Deploy (Netlify)
Connect this repo in Netlify; `netlify.toml` sets the build. The contact form uses Netlify Forms.
