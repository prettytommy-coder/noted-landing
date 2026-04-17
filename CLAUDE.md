# NOTED Landing

Static one-page landing for NOTED — beauty recommendation platform.

## Stack
- Pure HTML + CSS + vanilla JS (no frameworks, no build tools)
- Deployed on Vercel (auto-deploy from `master` branch)
- Live: https://noted-landing-iota.vercel.app

## Structure
- `index.html` — single page: preloader, hero + phone mockup, marquee, features, blogger form, footer
- `style.css` — all styles, dark palette (#110D13), Unbounded/Nunito/JetBrains Mono fonts
- `assets/og-image.svg` — Open Graph preview
- `vercel.json` — security headers

## Design
- Dark beauty palette: --bg:#110D13, --card:#1E1822, --accent:#FF4F8B
- Lusion.co-inspired animations: giant counter preloader (curtain slide-up), clip-mask text reveals, custom cursor (dot + lagging ring), magnetic buttons, 3D tilt cards, parallax, marquee ticker
- Realistic iPhone mockup (Dynamic Island, status bar, side buttons, glass glare)
- Animated canvas background (floating gradient orbs)
- All animations respect `prefers-reduced-motion`

## Related project
Main app: `C:/Users/Tatiana/Downloads/noted-project` (Next.js 14 + Supabase + Telegram Mini App)
- Repo: github.com/prettytommy-coder/noted-project, branch `master`
- Deployed: https://noted-project-eta.vercel.app

## Rules
- No external JS libraries — vanilla only
- Branch is `master`, not `main`
- Don't touch files outside explicit scope
- Don't add unsolicited refactoring or comments
