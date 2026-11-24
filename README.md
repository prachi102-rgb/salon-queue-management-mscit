# Salon Queue Management System

**Live demo:** Add your deployed Vercel URL here after deployment  
**Hosted on:** Vercel (frontend)

## About
A mobile-first salon queue management system that lets customers join a queue, view their token and estimated wait, and allows receptionists and barbers to manage service flow.

## Features
- Customer queue joining and token generation
- Queue status and estimated wait
- Reception dashboard and walk-in entry
- Barber Start/Done controls
- Waiting-area TV display
- Owner settings for services, barbers and queue
- English/Gujarati toggle

## Run locally
```bash
npm install
npm run dev
```

## Production build
```bash
npm run build
npm run preview
```

## Routes / screens
The app uses in-app navigation for Home, Join Queue, My Status, Reception, Barber View, TV Display and Owner Settings.

## Demo access
This prototype uses local browser storage and has no staff authentication. Use the Reception, Barber View and Owner Settings navigation items to demonstrate staff flows.

## Deployment
Import the GitHub repository into Vercel. Framework preset: Vite. Build command: `npm run build`. Output directory: `dist`.

## Limitations
This classroom prototype stores state in browser localStorage. It is suitable for demonstrating flows in one browser profile. True multi-device synchronization requires a shared backend/database such as Supabase or Firebase.
