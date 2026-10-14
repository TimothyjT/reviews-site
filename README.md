# reviews-site

Review Autopilot product site — https://reviews.northbeambuilds.com

Static GitHub Pages site in the Northbeam Builds product-site pattern (same
chrome/assets as faqagent-site). Copy sources: the review-recovery deploy
kit's LISTING-COPY-SECTION.md and ONE-PAGER.md, under the claim fences in
REA-PROCUREMENT-005 and REA-PROCUREMENT-007 (human-run, owner-approved —
never described as automated sending; no Podium price figures; no merged
competitor claims; no invented clients/results/testimonials).

Stripe quick-buy link (audit-only; created 2026-10-14, live account
TubbsterBot):
`https://buy.stripe.com/aFa8wPeZmdW4fISenIgYU06`
(plink_1UQWEBDuI42vTlvNuNDX76hE — product "Review Autopilot"
prod_VROxPzZSqBL7XP; single line item: $149 one-time "Setup audit
(one-time)" price_1UQW9IDuI42vTlvNu4q6S5lB; $149 due today, verified by
re-reading the link's line items in Stripe. Post-payment redirect goes
to this site's /contact/ page — the stand-in intake surface until a
dedicated Review Autopilot intake page exists.)

Reconciliation record (2026-10-14): the kit's canonical offer is
audit-first — the $29/mo loop is an optional follow-on agreed separately
after the audit, never bundled in at checkout (kit LISTING-COPY-SECTION:
"agreed separately, never bundled in silently"; MONITORING-SPEC: "only
under a separate agreement after a $149 audit/setup"). The original
combined link (plink_1UQW9QDuI42vTlvNKtcnxnUv, $149 + $29/mo = $178 due
today) contradicted that offer and was DEACTIVATED in Stripe; the
audit-only link above replaces it. Every buy CTA (index ×3, pricing,
faq, contact, sample) points at the audit-only link with the label
"Get the Review Autopilot audit — $149, one time"; llms.txt carries the
"Buy online (Stripe checkout)" line. The $29/mo recurring price
(price_1UQW9KDuI42vTlvNpczyiCCt) itself was not changed — it is used
only when a buyer separately agrees to the loop after the audit. The
free-sample path still runs by email (northbeambuilds@gmail.com) and is
unchanged.
