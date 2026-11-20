# KCG Casino Arena

A first interactive prototype for the KCG Mega Event.

## Open the prototype
After GitHub Pages publishes the new folder, open:

https://kcgofficials.github.io/KCG-Invitation-/casino/

## Included in this prototype
- Admin view: select the performing team and category, open betting, lock betting, declare the result.
- Team Mobile view: select a team and submit one BACK or CHALLENGE choice.
- LED view: jackpot pools, majority result, and team wallets.
- Fixed bet: 1,000 event coins per participating team per category.
- Starting wallet: 15,000 event coins per team.
- Majority: 3 or more of the 5 non-performing teams.
- Payout: winning bettors receive their 1,000-coin stake back plus an equal share of the losing pool.
- Golden Vault: one of Ramp Walk, Tagline, or Act is selected secretly at the start of each performing team's round; after all three categories are complete, winners in that category receive 500 bonus coins each from a separate 2,500-coin reserve.

## Important limitation
This version is a local browser prototype. It uses browser localStorage so the Admin, Team Mobile, and LED views can be tested in the same browser (or same browser profile). It does **not** yet synchronize across separate phones or computers.

## Before the live event
A secure real-time backend still needs to be connected. The production version should use authenticated team accounts, an Admin-only control account, server-side wallet transactions, immutable bet locks, result/payout processing, and real-time updates to all connected screens. Do not use public database write rules for the live event.

The current page is a prototype, not a production-ready event wallet or cross-device system.
