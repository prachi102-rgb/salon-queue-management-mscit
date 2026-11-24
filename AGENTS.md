# AGENTS.md — Salon Queue Management

Mobile-first salon queue application. Customers join and track their turn; reception and barbers manage the queue; a TV screen shows who is next.

## Read first
- docs/01-brief.md — features and boundaries
- docs/02-screens.md — screen layout and behaviour
- docs/03-flows-rules.md — flows, queue rules and test checklist

## Stack
React + Vite + CSS. Run with `npm install` then `npm run dev`. Build with `npm run build`.

## Working rules
- Work on one screen or feature per task.
- Theme: charcoal (#1F2937) + gold (#D4A017), rounded cards.
- Keep queue rules consistent across screens.
- Do not add features from the Don't build list.
- Test mobile layouts and list changed files after each task.
