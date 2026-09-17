# Zorganizowana Grupa Malarska

Landing page for a painting crew: prices, contact form, phone.

## Setup

```sh
npm install
cp .env.example .env
```

In `.env`, set `PUBLIC_FORMSPREE_ID` to your [Formspree](https://formspree.io) form id.

## Images

Drop files here (same names). SVG placeholders are used until then:

- `public/images/hero.png`
- `public/images/service-malowanie.jpg`
- `public/images/service-szpachlowanie.jpg`
- `public/images/service-gladzi.jpg`

## Commands

| Command | Action |
| --- | --- |
| `npm run dev` | Dev server at `localhost:4321` |
| `npm run build` | Production build to `./dist/` |
| `npm run preview` | Preview the build |
