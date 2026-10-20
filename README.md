# ELJO #2027 — Link Wedding

A mobile-first, single-couple wedding website starter for Elizabeth & John.

## Current website sections
- Invitation landing page and wedding date
- Love story
- Traditional and church wedding details
- Photo/video gallery placeholders
- RSVP form demonstration
- Monetary gift, gift registry, and blessing placeholders

## Wedding details currently included
- Couple: Elizabeth & John
- Date: Saturday, 2 January 2027
- Wedding Mass: 10:00 AM
- Venue: Holy Family Catholic Church, Karu-Upke, Obudu LGA, Cross River State
- Reception: Karu Town Hall behind Primary Health Center PHC
- Traditional wedding: Combined with the Reception 
- Colours: emerald green, white, champagne gold, and burgundy

## Run locally
Open `index.html` in a modern browser. The RSVP currently demonstrates a confirmation message only. It does not transmit or store guest information.

## Recommended next deployment steps
1. Create a GitHub repository and upload this folder.
2. Deploy as a static site to a host whose terms allow the intended personal use.
3. Add a Supabase project for secure RSVP storage and a private admin view.
4. Connect email notifications only after the database and spam protections are configured.
5. Integrate a payment provider after the couple's recipient account and business/individual verification are complete. Never put secret API keys in browser code.
6. Test the site on mobile, submit test RSVPs, and verify payment webhooks before publishing gift payments.

## Domain ideas (availability not checked)
- `eljo2027.com`

A free host subdomain can be used for the first preview. A custom domain generally requires an annual registration fee.

## Important limitations
- No live RSVP database or email/SMS notifications yet.
- No payment collection, gift registry backend, or payment verification yet.
- Gallery items are placeholders; replace them with photos/videos the couple has permission to publish.
- Confirm the traditional wedding schedule and venue before sharing the final invitation.
