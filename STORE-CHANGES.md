# IconFloat store: trust redesign

All edits were made to an unpublished copy of the live theme, **IconFloat Trust Redesign**
(`gid://shopify/OnlineStoreTheme/187858518068`). The live theme ("Copy of Copy of MistTrack") was not touched.

Preview: https://shopmisttrack.com/products/misttrack-dancer-mist-diffuser?preview_theme_id=187858518068

## Branding
- Header logo is now the IconFloat wordmark with the fedora as the "O", cut from the profile picture
  (`assets/iconfloat-wordmark-hat.png`, uploaded to Files as `iconfloat-wordmark-hat.png`).
- Heading font changed from Playfair Display (serif) to Montserrat SemiBold, closer to the wordmark.
- Savings badge and bundle tags changed from red to brand purple (`#6D28D9`).

## Trust fixes
- Judge.me review widget on the dancer page was set to **sample data** (example reviews shown as if real). Hidden until real reviews exist.
- Fake "Cart reserved for 5:00" countdown in the cart drawer turned off.
- Placeholder text removed: cart drawer icons said "Heading / Heading / Heading"; footer newsletter said
  "A short sentence encouraging customers to subscribe…".
- Footer now shows policy links. Right-click blocking turned off.
- Trust row under Add to cart now states real policy facts: secure checkout, free 30-day returns, ships in 1 business day.
- Header ticker "WELCOME!" replaced with "FREE 30-DAY RETURNS · SHIPS IN 1 BUSINESS DAY".
- New FAQs on the dancer page: shipping, returns, damaged items, who IconFloat is (with contact email).
- Leftover steam-train content removed from the dancer page template (it was disabled but could be re-enabled by mistake).
- Disabled "50% OFF LAUNCH SALE" announcement reworded so it can't go live with a false claim.

Every claim above matches the store's published shipping and refund policies.

# AfroDry store: Black Friday countdown (24 Nov 2026)

Theme: **AfroDry** (live, `gid://shopify/OnlineStoreTheme/187851309108`). Saved, waiting to be published.

- The Black Friday bar above the header now shows an "EARLY BLACK FRIDAY SALE" headline, a live
  hours / mins / secs countdown, and a gold "Shop now" button.
- The countdown runs to **one fixed end time for every visitor**: 25 Nov 2026, 7:30pm UK time
  (`2026-11-25T19:30:00Z`). Reloading does not reset it. When it reaches zero the bar disappears.
- 26 Nov: sale extended. New end time is 27 Nov 2026, 8:35am UK time (`2026-11-27T08:35:00Z`).
- The end time is a theme setting: Customize → Theme settings → Black Friday → "Black Friday sale ends at".
- No % discount is advertised in the bar. "Limited time only" was dropped from the UK message
  because the timer now shows the real deadline.
- A countdown that restarts for each visitor was deliberately not built: it is a fake deadline,
  which UK consumer law (DMCC Act 2024) prohibits.
- 27 Nov: bar redesigned as a slim, minimal near-black strip (gold timer digits, thin kente line).
  Final extension, labelled "Black Friday · Extended · Final day", ending 27 Nov 2026, 11:59pm UK
  time (`2026-11-27T23:59:00Z`). This is the last deadline: no further extensions.
- 27 Nov (evening): merchant chose a Black Friday Weekend sale for the US audience. "Final day"
  wording removed; bar now reads "Black Friday Weekend · Ends Sunday midnight ET" (end text shown
  on desktop only). Countdown ends Mon 30 Nov 2026, 00:00 US Eastern (`2026-11-30T05:00:00Z`).
- Countdown shows days/hours/minutes while a day or more remains, then hours/minutes/seconds under 24 hours.
