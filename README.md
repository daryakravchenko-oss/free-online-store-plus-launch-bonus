# Free Online Store + Launch Bonus — Sellvia lead offer

Bank-style lead offer: a **free, ready-made online store** plus a **stepped cash "Launch Bonus"** that grows with the seller's sales over their first 3 months (90 days). Modelled on merchant rewards from banks like Chase / Bank of America.

The bonus is credited **to the seller's Sellvia balance, on top of profit** (the seller keeps 50–70% of every sale). Headline hook: **"Earn up to $1,000."**

## The offer ladder (current — v3)

| Sales in the first 3 months | Bonus |
|---|---|
| $500 – $999 | $50 |
| $1,000 – $2,499 | $100 |
| $2,500 – $4,999 | $250 |
| $5,000 – $9,999 | $500 |
| $10,000+ | $1,000 |

> ⚠️ **Numbers are not final.** They still need to be re-confirmed with the team lead. The original brief was harder ($100k → $1,000 in the first month); this version softened the top tier to $10k, widened the window to 3 months, and added the $500 → $50 entry step to pull leads in.

## The file

- **`index.html`** — self-contained landing page. Open it directly in a browser to view the live page. All CSS/JS is inline; images and fonts load from external URLs (see below).

## Page structure

Promo bar (sticky) → nav → **hero** (offer + ladder card with a round "Up to $1,000 Bonus" sticker) → stats strip → benefit row → **Step 1: free store** → **Step 2: dark bonus-table block** → How it works → What's free → product catalog → Recognition (awards / featured / ratings) → testimonials → FAQ (accordion) → final CTA → closer → fine print → footer.

JS: reveal-on-scroll + FAQ accordion.

## Live assets used

- **Checkout / CTA:** `https://sellvia.com/checkout/?product=custom&type_custom=free_basic_hosting`
- Store designs, awards: `sellvia.com/images-for-landings/free-online-store-plus-instagram-and-tiktok-store/`
- Products, icons, featured logos, ratings, review avatars: `sellvia.com/images-for-landings/premium-business-bundle/`
- Heading font: `DM Serif Text` (Google Fonts); body: system SF Pro stack.

## Compliance guardrails (built in — keep them)

- "up to $1,000", never "you will earn $1,000"
- "this is not a guarantee of income", "results vary"
- top tiers are reached "by only a portion of sellers"
- FAQ "Is the bonus guaranteed income?" → "No…"
- Bonus = balance credit, counted on **net sales** (minus refunds and order fees) — all disclosed in the fine print.

## Open items / to-do

- Re-confirm the ladder numbers with the team lead.
- Decide the fate of the "312 people started today" counter (keep / remove).
- **Port into the live Sellvia stack:** this is still a standalone HTML page, not yet in the Sellvia WordPress theme. Either rebuild against an existing live landing's markup, or hand off to whoever builds Sellvia pages.
