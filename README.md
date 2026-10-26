# Paywall Audit — Pura Mente

**Live:** https://bterzic123.github.io/pura-mente-paywall-audit/

Prepared for the Pura Mente team by Adapty. Four ranked ideas for the onboarding paywall, each backed by a number from State of Paywalls 2026, a scorecard of the paywall against the report, and a clickable rebuild of the paywall and the close moment in Pura Mente's own design, with a Today / Proposed switch.

## The ideas

| # | Idea | Report anchor (State of Paywalls 2026) | Outcome |
| :-- | :-- | :-- | :-- |
| 1 | Show your 50% offer when someone closes the first paywall | 4.5: only 4% of apps show a paywall after the first is closed; it converts at 0.88× the main one and beats it in 45% of apps | ARPU +10–15% · based on Adapty data |
| 2 | Put monthly next to the annual trial | 5.2: changing the number of plans wins 57% of A/B tests on LTV; 5.3: trial on annual, emphasized | CR +15–30% · observed in winning A/B tests |
| 3 | Put your 4,8 stars and 35,000 people on the paywall | 3.1: 27% of top paywalls show social proof; 5.3: social proof on the paywall | CR +10–30% · observed in winning A/B tests |
| 4 | Use the goal they picked in the headline | 3.5: 2% of top headlines are personalized; 5.3: onboarding personalization | CR +8–17% · observed in winning A/B tests |

## Benchmarks

Health & Fitness, App Store data, Oct 2025–Sep 2026. Much of Pura Mente's revenue comes from Google Play and the report covers the App Store only, so the audit compares the paywall's setup and uses A/B test findings rather than conversion or price benchmarks.

Full report: https://adapty.io/state-of-paywalls/?utm_source=paywall-audit&utm_medium=github-pages&utm_campaign=sop_2026&utm_content=pura-mente

## Grounding

Prices (33,83 €/year with a 7-day trial, 6,63 €/month, 17,99 €/year at 50% OFF), the 4,8 rating from 8,1 thousand ratings (Spanish App Store), “+35,000 personas eligen Pura Mente” and every line of paywall copy come from Pura Mente's own App Store listing and in-app screens. Impact ranges are observed lifts from winning A/B tests in State of Paywalls 2026 and Adapty's own data, not measured results for Pura Mente.

## Run locally

```
python3 -m http.server 8000
```

Then open http://localhost:8000. Add `?open=proto` to land on the prototype.
