# Cinematic Portfolio — Maslah Bashir Ibrahim

Personal portfolio of **Maslah Bashir Ibrahim** — AI Engineer, Full-Stack Developer, ML Enthusiast, and Problem Solver.

I build intelligent, scalable, and beautiful web applications. Currently diving deep into the world of AI and Machine Learning.

## About This Project

This is a cinematic, dark-themed portfolio site featuring a full-screen video hero, custom cursor interactions, scroll-driven animations, and a bronze/champagne visual language throughout. It's built as a single-page React application with smooth, motion-first section transitions.

## Tech Stack

- **React 19** + **TypeScript**
- **Vite** — build tooling
- **Tailwind CSS 4** — styling
- **Framer Motion** — animation and gesture interactions
- **Lenis** — smooth scrolling

## Key Features

- Full-screen cinematic hero video with a custom animated cursor
- 3D tilt / spotlight-sweep interactive portrait card
- Scroll-stacking project cards
- Motion-based entrance animations throughout every section
- Fully responsive layout, from mobile to large desktop

## Sections

1. **Hero** — introduction and primary call to action
2. **About** — bio and portrait
3. **Projects** — featured work
4. **Skills** — technical stack overview
5. **Experience** — work and education timeline
6. **Contact** — direct contact links and a message form

## Contact

- **GitHub:** [github.com/metrixit3-cmd](https://github.com/metrixit3-cmd)
- **LinkedIn:** [linkedin.com/in/maslah-bashir-79904042b](https://www.linkedin.com/in/maslah-bashir-79904042b/)
- **Email:** metrixit3@gmail.com
- **WhatsApp:** [wa.me/254787509941](https://wa.me/254787509941)

## Getting Started

```bash
npm install
npm run dev      # start the dev server
npm run build    # production build
npm run lint      # run lint checks
```

### Contact form

The contact form sends through [Formspree](https://formspree.io) (free, no backend needed).

1. Create a free form at formspree.io and copy its ID from the endpoint URL (`https://formspree.io/f/XXXXXXXX`).
2. Copy `.env.example` to `.env.local` and set `VITE_FORMSPREE_ID` to that ID.
3. For the deployed site, set the same `VITE_FORMSPREE_ID` variable in Vercel: Project Settings → Environment Variables.

Without it set, the form shows an error telling visitors to email you directly instead of silently failing.
