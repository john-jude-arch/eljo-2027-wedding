# ELJO #2027 — implementation plan

## Stage 1 — Invite website (current)
- Mobile-first one-page invitation
- Brand colours: emerald green, white/ivory, champagne gold, burgundy
- Love story, events, gallery, RSVP, gifts, blessings

## Stage 2 — RSVP backend
- Supabase Postgres table for guest submissions
- Public guests may submit an RSVP, but cannot read guest lists
- Admin dashboard protected by authentication
- Validate and rate-limit submissions; avoid collecting unnecessary personal data
- Optional email notification through a server-side function

## Stage 3 — Gift experience
- Gift registry list with item availability and a couple-approved destination
- Monetary gifts in NGN and international currencies, depending on provider eligibility
- Server-side payment initialization, signed webhook verification, idempotency, and status tracking
- Never store card details or expose secret keys in front-end code

## Stage 4 — Launch
- Confirm traditional wedding date/time/venue
- Replace placeholders with approved photos and video
- Test RSVP flows and accessibility on mobile
- Publish and share the final link

## Initial free-first approach
Use a free Git repository and a static hosting preview for the invitation page. Supabase has a free tier suitable for prototyping, but free projects may pause after inactivity and have usage limits. Hosting-plan terms should be checked before any commercial use. A custom domain is usually not free.
