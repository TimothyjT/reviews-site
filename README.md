# reviews-site

Review Autopilot product site — https://reviews.northbeambuilds.com

Static GitHub Pages site in the Northbeam Builds product-site pattern (same
chrome/assets as faqagent-site). Copy sources: the review-recovery deploy
kit's LISTING-COPY-SECTION.md and ONE-PAGER.md, under the claim fences in
REA-PROCUREMENT-005 and REA-PROCUREMENT-007 (human-run, owner-approved —
never described as automated sending; no Podium price figures; no merged
competitor claims; no invented clients/results/testimonials).

Stripe quick-buy link (created 2026-10-14, live account TubbsterBot):
`https://buy.stripe.com/dRm7sL5oM3hqbsCfrMgYU05`
(plink_1UQW9QDuI42vTlvNKtcnxnUv — product "Review Autopilot"
prod_VROxPzZSqBL7XP; prices: $149 one-time "Setup audit (one-time)"
price_1UQW9IDuI42vTlvNu4q6S5lB + $29/mo recurring "Monthly service
(per location)" price_1UQW9KDuI42vTlvNpczyiCCt; $178 due today, verified
by re-reading the link's line items in Stripe. Post-payment redirect goes
to this site's /contact/ page — the stand-in intake surface until a
dedicated Review Autopilot intake page exists.)

Swap-in record (2026-10-14): every buy CTA (index ×3, pricing, faq,
contact, sample) now points at the Stripe link with the label
"Get Review Autopilot — $149 setup + $29/mo", replacing the company
contact-path fallback; llms.txt carries the "Buy online (Stripe
checkout)" line. The free-sample path still runs by email
(northbeambuilds@gmail.com) and is unchanged.
