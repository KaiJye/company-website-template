# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview
Next.js 15 company website with TypeScript and Tailwind CSS v4, using the App Router architecture.

## Key Commands
- **Development**: `npm run dev` - Starts dev server with Turbopack at localhost:3000
- **Build**: `npm run build` - Creates production build
- **Production**: `npm run start` - Starts production server
- **Lint**: `npm run lint` - Runs ESLint with Next.js rules

## Architecture
- **Routing**: Next.js App Router (`/app` directory)
- **Pages**: Home page (`/app/page.tsx`) with hero, about, services, and contact sections
- **Styling**: Tailwind CSS v4 with custom CSS variables for dark/light mode
- **Fonts**: Geist font family from Vercel
- **Metadata**: SEO-optimized with company branding

## File Structure
```
app/
├── page.tsx         # Home page with company sections
├── layout.tsx       # Root layout with metadata
├── globals.css      # Tailwind CSS and global styles
└── favicon.ico      # Site icon

public/              # Static assets (SVGs)
```

## Development Notes
- Uses Next.js 15 with Turbopack for fast dev builds
- Responsive design built with Tailwind CSS
- TypeScript throughout with strict configuration
- Modern ES2017 target with JSX preserve
- ESLint configured for Next.js core web vitals