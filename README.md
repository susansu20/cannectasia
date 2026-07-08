# CANnect Asia — Website Prototype

Design + copy prototype for the CANnect Asia website redesign (Hub Solutions Digital, HS/Q/2026-0382).

## What this is
- Single self-contained `index.html` — all 9 pages via hash routing (`#/who-we-are`, `#/enter-asia`, etc.)
- Brand fonts: Arial Bold headings, Montserrat sub/body (Google Fonts)
- Embedded assets: white logo (base64), dotted Asia market maps (inline SVG), animated hero map
- Per-page SEO titles/descriptions + JSON-LD schema; full SEO map in the HTML comment at the top of the file

## Preview locally
Open `index.html` in any browser, or:
```
npx serve .
```

## GitHub Pages
Settings → Pages → Deploy from branch → `main` / root. The site will be live at
`https://susansu20.github.io/CANNECTASIA/`

## Before production (WordPress build)
- Replace placeholder team portraits and illustrative case-study metrics with confirmed client assets/figures
- Connect diagnostic form + footer newsletter to Scoreapp / CRM / email platform
- Replace Unsplash imagery with licensed/brand photography
