# ifs-therapy.com: website of Monika Riese

Plain static site, no build step. Cloudflare Pages publishes the repository root on every push to main (no build command, output directory "/"); security headers live in _headers. Domain ifs-therapy.com is registered at GoDaddy, DNS is managed by Cloudflare. Main address is www.ifs-therapy.com; ifs-therapy.com redirects there. Never touch email records (MX, TXT etc.).
Netlify was used first but its free plan only allows about 20 deploys a month (shared with riese.com); it is no longer used for this site.
Batch changes: commit locally and push once per round of edits.

## Files
- index.html: the whole one-page site in English
- impressum.html, privacy.html: English legal pages
- de/index.html, de/impressum.html, de/datenschutz.html: German versions (informal "du", lowercase); paths use ../
- Every page has an EN · DE switch in the header. Keep both languages in sync: any content change goes into both index.html and de/index.html.
- site.css: all styles
- fonts/: self-hosted Cormorant Garamond and Jost (no Google requests; the privacy page says so)
- img/: images

## Rules
- Design must stay clearly different from riese.com (Jens's site): light, warm, feminine; no dark sections.
- Palette: warm ivory #F8F1E4, sand #F0E5D3, soft rose #F3E3DA, soft mint #DCEBE2, espresso #40332F headings, rosewood #A57E72 italic accents, deep green #2F4A3E buttons (never black), matte gold #B39A62 for lines and labels.
- Positioning: IFS and systemic therapy for individuals and couples (family constellations, IFIO).
- Heilpraktikerin = state-licensed healing practitioner, NOT "für Psychotherapie".
- Homeopathy and Oxytocin Practitioner: mention in About only, never as a service.
- Do not link to Jens's own journeys or retreats. Allowed links: https://riese.com/chalet (group retreats) and https://riese.com/couples-retreat.html (couples retreats with Jens).
- Contact by mailto only: monikariese@hotmail.com. No forms, no cookies, no tracking.
- No cut-out photos of Monika (they looked artificial).

## Open
- Check licences of the stock images (hands, doors, wooden figures, IFS head illustration).
