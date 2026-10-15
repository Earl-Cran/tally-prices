# Tally's UK price list

The UK subscription prices the [Tally](https://github.com/Earl-Cran) iPhone app uses for its plan buttons, service matching and price-rise watch.

- `CHECKED` is the day a person last checked the prices.
- A plan's `p` is the provider's own UK price; `ap`, when present, is the UK App Store's price for the same plan (only where it differs). Tally uses it to point out subscriptions that cost less outside the App Store.
- Changes come as pull requests, each listing every price changed and its source.
- Every change must move `CHECKED` forward to the day it was checked. Phones only take a list newer than the one they have, so a second fix on the same day wouldn't reach them.
- The app downloads this file about once a week, checks it, and ignores it if anything looks wrong.

Nothing personal is in this repository.
