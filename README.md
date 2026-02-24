# ClearCareer v2 (2024)

> The 2024 redesign of the ClearCareer website -- a job search coaching and accountability community that helps professionals land better roles with higher salaries.

![Status](https://img.shields.io/badge/status-active-brightgreen)
![Astro](https://img.shields.io/badge/Astro-BC52EE?logo=astro&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white)

## Overview

ClearCareer v2 is the primary marketing website for the ClearCareer job search community, built with Astro 4.8 and deployed on Vercel. It showcases the community's value proposition -- weekly group coaching, AI-powered job search tools, templates and scripts, and peer accountability -- with extensive social proof from alumni who have landed roles with $5K-$30K salary increases. The site includes a full MDX blog with categories, tags, and RSS feed, plus SEO optimization with Open Graph tags and sitemap generation.

## Features

- **Hero Section** -- "Stop Wasting Time, Start Getting Results" with community join CTA and testimonial image
- **Stats Bar** -- Key metrics: $10K avg salary gain, $30K top salary gain, 100+ alumni
- **Success Story Testimonials** -- Multiple sections featuring named alumni with salary outcomes (e.g., "3 Job Offers + a $10K Raise", "From 200+ Applications to a Job in 3 Weeks", "Landed Associate Director + $25K")
- **Weekly Group Coaching Section** -- Describes live coaching calls with clarity, roadblock removal, and strategy sharing
- **AI Prompts, Tools & Templates** -- 9 featured tools including: Quantify Your Achievements, Instantly Research Salaries, Discover Industry Events, Improve Your Networking, Email Templates, Target Better Companies, Level-Up Interview Prep, Optimize Your LinkedIn, Counter Objections
- **Templates, Scripts & Resources** -- 500+ hours of custom AI prompts, resume optimization tools, email templates
- **Community Support & Accountability** -- Win sharing, feedback, goal setting, weekly priorities
- **4-Step Success Path** -- Clarify Your Career Path, Target the Right Companies, Master Your Outreach, Land The Job
- **Why Choose ClearCareer** -- Feel Valued and Confident, Gain Motivation and Clarity, Make Networking Feel Natural, Develop Your Personal Brand
- **Coach Bio** -- Detailed "Meet Your Coach" section about Izzy, including media features (CBC, Notable Life) and workshop experience (UofT, TMU, Humber College, United Nations Association)
- **Pricing** -- Monthly membership ($49/mo) and Lifetime membership ($249 one-time) with Circle community platform
- **FAQ Section** -- Covers results expectations, program length, weekly calls, community platform, cancellation policy
- **MDX Blog** -- Full blog engine with categories, tags, related posts, and RSS feed
- **SEO Optimization** -- Open Graph tags, sitemap generation, Google Analytics support, Google Site Verification

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Framework | Astro 4.8 |
| Language | TypeScript |
| Styling | Tailwind CSS (with dark mode) |
| Content | MDX blog posts |
| SEO | Sitemap, RSS, Open Graph |
| Deployment | Vercel |

## Getting Started

### Prerequisites
- Node.js 18+
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/izzydoesizzy/clearcareerv2-2024.git
   cd clearcareerv2-2024
   ```
2. **Install dependencies**
   ```bash
   npm install
   ```
3. **Start the development server**
   ```bash
   npm run dev
   ```

### Available Scripts

| Command | Description |
|---------|-------------|
| `npm install` | Install dependencies |
| `npm run dev` | Start local dev server |
| `npm run build` | Build production site to `./dist/` |
| `npm run preview` | Preview production build locally |
| `npm run format` | Format code with Prettier |
| `npm run lint:eslint` | Run ESLint |

## Project Structure

```
src/
├── assets/
│   ├── images/            # Testimonial photos, coach photos, community screenshots
│   └── styles/
│       └── tailwind.css
├── components/
│   ├── widgets/
│   │   ├── Hero.astro
│   │   ├── Hero2.astro
│   │   ├── Features.astro
│   │   ├── Features2.astro
│   │   ├── Steps.astro
│   │   ├── Content.astro
│   │   ├── Testimonials.astro
│   │   ├── Pricing.astro
│   │   ├── FAQs.astro
│   │   ├── Stats.astro
│   │   ├── CallToAction.astro
│   │   └── About.astro
│   ├── blog/              # Blog list, post, and category components
│   ├── common/            # Shared components
│   └── ui/                # Base UI primitives
├── content/
│   ├── post/              # MDX blog posts
│   └── config.ts          # Content collection config
├── layouts/
│   ├── Layout.astro
│   ├── PageLayout.astro
│   └── MarkdownLayout.astro
├── pages/
│   ├── index.astro        # Main landing page
│   └── [...blog]/         # Dynamic blog routes (posts, categories, tags)
├── utils/
├── config.yaml            # Site config (name, SEO, blog settings, analytics)
└── navigation.js          # Navigation menu config
```

## Configuration

Edit `src/config.yaml` to customize:
- Site name, URL, and SEO metadata
- Blog settings (posts per page, permalinks, categories, tags)
- Google Analytics ID
- Theme (system / light / dark)

## Deployment

- **Vercel** (recommended): Connect repo and auto-deploy
- **Netlify**: Connect repo and auto-deploy
- **Manual**: `npm run build` then serve the `dist/` directory

## Tags

`landing-page` `template` `blog` `job-search-community`

## Created

May 2024

## Status

Functional -- full marketing site with blog, testimonials, pricing, and community signup links.

## Author

**Izzy Piyale-Sheard** -- [@izzydoesizzy](https://github.com/izzydoesizzy)
