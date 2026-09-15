# TEST REPORT — Social services
> Tester: Senior Engg | Segment: Health consultant | Tier-4/5

## Build
- [ ] `npm run build` (pending)

## Static QA (generator asserts)
- Phone: `tel:+919538566665` + WhatsApp | Maps embed (lazy iframe) + JSON-LD LocalBusiness schema + H1 + title<=60
- No lorem ipsum, no invented hours/prices/ratings

## Build result (2026-09-15)
- [x] `npm run build` PASS (vite 5.4.21, 0 warnings)
- dist: index 11.86 kB / CSS 11.45 kB / JS 1.17 kB — under perf budget

## Static QA (2026-09-15, all PASS)
- [x] title<=60, Maps embed iframe, JSON-LD schema, H1, no lorem, phone/WhatsApp rules per CSV

## Verdict: BUILT + STATIC QA PASS → gh-pages branch deploy
