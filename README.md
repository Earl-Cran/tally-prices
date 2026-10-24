# Tally's UK price list

The UK subscription prices the [Tally](https://github.com/Earl-Cran) iPhone app uses for its plan buttons, service matching and price-rise watch.

- `CHECKED` is the day a person last checked the prices.
- A plan's `p` is the provider's own UK price; `ap`, when present, is the UK App Store's price for the same plan (only where it differs). Tally uses it to point out subscriptions that cost less outside the App Store.
- Plans can also say what they include, for Tally's "Your plans": `inc` (2–5 short lines), `t` (a stable plan key, shared by a plan's monthly and yearly entries), `tn` (its short name), `for` (who it's limited to, such as "Students"), `addon` (an add-on, not a plan) and `people` (how many it covers). A service with `separate` has plans that are separate products, not steps up. All are optional, and older copies of the app ignore them.
- Changes come as pull requests, each listing every price changed and its source.
- Every change must move `CHECKED` forward to the day it was checked. Phones only take a list newer than the one they have, so a second fix on the same day wouldn't reach them.
- The app downloads this file about once a week, checks it, and ignores it if anything looks wrong.

Nothing personal is in this repository.
