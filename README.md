<div align="center">

# Maslah Bashir Ibrahim

### AI Engineer · Full-Stack Developer · ML Enthusiast

Building intelligent, scalable, and beautiful web applications.

[![Visit Portfolio](https://img.shields.io/badge/Visit%20Portfolio-cinematic--portfolio--lilac.vercel.app-CBB59D?style=for-the-badge&logo=vercel&logoColor=black)](https://cinematic-portfolio-lilac.vercel.app)
[![GitHub](https://img.shields.io/badge/GitHub-metrixit3--cmd-181717?style=for-the-badge&logo=github)](https://github.com/metrixit3-cmd)

[About](#about) · [Features](#highlights) · [Tech Stack](#tech-stack) · [Run Locally](#run-locally) · [Contact](#contact)

</div>

## Portfolio Preview

**[Open the live portfolio →](https://cinematic-portfolio-lilac.vercel.app)**

[![Preview of Maslah Bashir Ibrahim's portfolio](https://image.thum.io/get/width/1200/crop/750/https://cinematic-portfolio-lilac.vercel.app)](https://cinematic-portfolio-lilac.vercel.app)

## About

This repository contains the personal portfolio of **Maslah Bashir Ibrahim**, an AI Engineer and Full-Stack Developer interested in building useful digital products with thoughtful design and technology. The site presents my background, selected projects, skills, experience, and ways to get in touch.

## Highlights

- Cinematic, full-screen hero experience with video and custom cursor interactions
- Interactive portrait card with 3D tilt and spotlight effects
- Scroll-stacked project cards and motion-driven section transitions
- Dedicated About, Projects, Skills, Experience, and Contact sections
- Responsive layout for mobile, tablet, and desktop screens
- Smooth scrolling powered by Lenis
- Contact form integration with Formspree
- Vercel Analytics and Speed Insights

## Tech Stack

| Area | Technologies |
| --- | --- |
| UI | React 19, TypeScript |
| Build tooling | Vite |
| Styling | Tailwind CSS 4 |
| Animation | Framer Motion |
| Scrolling | Lenis |
| Deployment and insights | Vercel, Vercel Analytics, Vercel Speed Insights |
| Quality checks | Oxlint |

## Portfolio Sections

1. **Hero** — introduction and primary call to action
2. **About** — background and portrait
3. **Projects** — selected work
4. **Skills** — technical capabilities
5. **Experience** — experience and education timeline
6. **Contact** — contact links and message form

## Run Locally

### Requirements

- Node.js and npm

### Setup

```bash
git clone https://github.com/metrixit3-cmd/cinematic-portfolio.git
cd cinematic-portfolio
npm install
npm run dev
```

Vite prints the local development URL in the terminal.

### Available scripts

```bash
npm run dev      # start the development server
npm run build    # create a production build
npm run preview  # preview the production build locally
npm run lint     # run Oxlint
```

## Contact Form Configuration

The contact form uses [Formspree](https://formspree.io). To enable submissions:

1. Create a form at Formspree and copy its form ID from the endpoint URL (`https://formspree.io/f/XXXXXXXX`).
2. Copy `.env.example` to `.env.local` and set your ID:

   ```dotenv
   VITE_FORMSPREE_ID=your_form_id
   ```

3. Add `VITE_FORMSPREE_ID` to your Vercel project's environment variables for the deployed site.

Without this value, the form directs visitors to contact me by email.

## Project Structure

```text
.
├── public/
│   ├── videos/          # Hero and other public video assets
│   ├── favicon.svg
│   └── resume.pdf
├── src/
│   ├── assets/          # Images and visual assets
│   ├── components/      # Portfolio sections and UI components
│   ├── App.tsx          # Page composition
│   └── main.tsx         # Application entry point
├── .env.example
├── index.html
└── package.json
```

## Contact

- **Email:** [metrixit3@gmail.com](mailto:metrixit3@gmail.com)
- **GitHub:** [@metrixit3-cmd](https://github.com/metrixit3-cmd)
- **LinkedIn:** [Maslah Bashir Ibrahim](https://www.linkedin.com/in/maslah-bashir-79904042b/)
- **WhatsApp:** [+254 787 509 941](https://wa.me/254787509941)

---

<div align="center">

Made by **Maslah Bashir Ibrahim** · [View the live portfolio](https://cinematic-portfolio-lilac.vercel.app)

</div>
