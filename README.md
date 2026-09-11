# NACUAA DC Website

The official website for the **North America Colleges and Universities Alumni Alliance, Washington DC Chapter** (北美高校联盟华盛顿DC分会).

- 🌐 **Live Website**: [https://dc.nacuaa.ai](https://dc.nacuaa.ai)
- 👤 **President**: 刘斌 (Bin Liu), `bin@nacuaa.ai`

## Tech Stack
* **Framework**: Astro (v5)
* **Styling**: Tailwind CSS (v4)
* **Internationalization**: Custom lightweight i18n routing (`zh-CN`, `en`, `zh-TW`)
* **Deployment**: Cloudflare Pages (`nacuaadc.pages.dev`)

## Features
* 🌐 **Full i18n Support**: Supports Simplified Chinese (`zh-CN`, default), English (`en`), and Traditional Chinese (`zh-TW`).
* 🎨 **Theme & Design**: Responsive layout with dark-mode navy & slate palettes and custom typography.
* 👥 **Leadership Roster**: Highlights chapter leadership (President 刘斌 Bin Liu).
* 📝 **Official Activity Release of Liability Agreement (Waiver)**: Bilingual waiver terms, electronic touch handwriting signature pad, auto-generated PDF receipts via `pdf-lib`, and optional Cloudflare Workers/R2 archiving backend (`/waiver/`, `/waiver/admin/`).
* 🏆 **9 Specialized Alumni Clubs**: Dedicated directory and club pages for Guandan, Hike, Pickleball, Golf, Tennis, Music, Garden, AI, and AI Creative Media.

## Local Development
Install dependencies:
```bash
npm install
```

Start dev server:
```bash
npm run dev
```

Build production static bundle:
```bash
npm run build
```

## Cloudflare Pages Deployment
Deployed via Cloudflare Pages:
* **Project**: `nacuaadc`
* **Custom Domain**: `dc.nacuaa.ai`
* **Build Command**: `npm run build`
* **Output Directory**: `dist`

