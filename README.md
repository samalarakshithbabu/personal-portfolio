# Personal Portfolio

A modern, responsive portfolio website built with Next.js and Tailwind CSS to showcase projects, skills, and contact information.

---

## Problem Statement

Developers need a professional, deployable portfolio site to present projects and skills to potential employers and collaborators.

## Objectives

- Build a responsive portfolio website
- Showcase projects loaded dynamically from JSON
- Deploy easily to Vercel or GitHub Pages
- Maintain clean, modern design

## Key Features

- **Modern Design** — clean UI with Tailwind CSS
- **Fully Responsive** — mobile, tablet, and desktop layouts
- **Fast Performance** — Next.js static generation
- **Dynamic Project Loading** — projects loaded from `projects.json`
- **Smooth Scrolling Navigation** — section-based navigation
- **Easy Deployment** — Vercel or GitHub Pages

## Technologies Used

| Component | Technology |
|-----------|-----------|
| Framework | Next.js 14 |
| Styling | Tailwind CSS |
| Language | TypeScript |
| Deployment | Vercel / GitHub Pages |

## Project Structure

```
personal-portfolio/
├── components/         # Reusable UI components
├── pages/              # Next.js pages
├── public/             # Static assets
├── styles/             # CSS styles
├── projects.json       # Project data
├── next.config.js      # Next.js configuration
├── tailwind.config.js  # Tailwind configuration
├── tsconfig.json       # TypeScript configuration
└── README.md
```

## Installation and Setup

### Prerequisites
- Node.js 18+
- npm or yarn

### Setup
```bash
npm install
npm run dev
```

Application runs at `http://localhost:3000`.

### Build for Production
```bash
npm run build
npm start
```

## Limitations

- Single-page portfolio (no blog or CMS)
- Projects managed via JSON file (no admin panel)

## Author and Contact Information

**SAMALA RAKSHITH BABU**

- Email: samalarakshithbabu7@gmail.com
- LinkedIn: https://www.linkedin.com/in/samala-rakshith-babu-9374ab281/
- GitHub: https://github.com/samalarakshithbabu

## License

No LICENSE file present in repository.