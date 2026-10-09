# Growth Audit — Suno (volume 2)

**Live:** https://plykhvar-glitch.github.io/suno-flow-rebuild-v2/

Suno's onboarding (sign-up, birthday, name) stays exactly as it ships. Every change starts at the
paywall: personalised with the name the onboarding collects, and — for Apple Ads installs — with
the search that brought the person in. The prototype has two paths, **Organic** and **Apple Ads**,
switchable above the phone. The prototype starts at the paywall: the onboarding screens before it are unchanged, so they are not rebuilt.

| # | Idea | Screen | Potential outcome |
| :-- | :-- | :-- | :-- |
| 01 | Give the back arrow a second chance: a month of Pro, next to what Free leaves out | Offer on close | ARPU +10–15% |
| 02 | Match the paywall to the Apple Ads search (music maker, SoundCloud, ai cover, lyrics) | Paywall · Apple Ads | CR +15–20% |
| 03 | Greet them by name, with the 4.9 from 368K ratings under it | Paywall | CR +10–15% |
| 04 | Show the real saving on each plan (in euros: Pro 21 €, Premier 121 € a year) | Paywall | ARPU +10–15% |
| 05 | Count Pro in songs, not credits — “up to 500 songs a month” | Paywall, after purchase | CR +3–8% |

**New in Adapty: virtual currency.** The first screen after purchase shows Suno's credits as a
balance, and a top-up sheet sells Suno's own credit packs (500 / 1,000 / 2,000 credits) to
subscribers.

EN / ES / DE, light and dark, a 30-second walkthrough per path, full-screen on a phone
(`?open=proto`, or `?open=asa` for the Apple Ads path).

**Grounding.** Prices, ratings, plan lines and limits come from Suno's in-app paywall (euro
storefront), the US App Store listing and suno.com/pricing. Keyword examples come from public
observation of Suno's Apple Ads, not from their account. Prompts are placeholders.

Impact ranges are Adapty's expected effect from teardowns and A/B tests across subscription apps —
not measured lift for Suno.

## Run locally

```bash
python3 -m http.server 8000
```
