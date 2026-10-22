# WINGLY — Bird Lifecycle Intelligence

WINGLY is a bird-exclusive lifecycle management platform inspired by the lifecycle-management approach of ANIVERA. It is a separate product and codebase focused on birds only.

## Current MVP
- Responsive dashboard with bird-care overview
- Bird registry with searchable sample profiles
- Add-bird profile modal (session-only state in this first frontend commit)
- Bird status indicators for healthy, monitoring, and incubating
- Daily care checklist interactions
- Placeholder sections for health, breeding, nutrition, lifecycle, and insights

## Tech stack
- React 19 + TypeScript
- Vite
- Lucide icons
- Responsive custom CSS

## Run locally
```bash
npm install
npm run dev
```

## Build
```bash
npm run build
```

## Deployment
Designed for Vercel static frontend deployment. Framework preset: Vite. Build command: `npm run build`; output directory: `dist`.

## Important MVP note
Bird profiles and care checklist changes are currently held in browser session state; they are not yet persisted to a database. Do not use this prototype as a medical diagnostic tool. Health concerns should be reviewed by an avian veterinarian.

## Product boundary
WINGLY covers birds only. Keep its branding, codebase, configuration, and deployment separate from ANIVERA and HERDON.
