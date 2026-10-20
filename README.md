# BakePilot — zero-cost MVP prototype

A mobile-friendly prototype for Kenyan home bakers and small cake businesses.

## Included
- Local browser-based workspace profile (demo sign-in only; not secure authentication)
- Order create/edit/delete, due dates, status, Cash/M-Pesa labels, deposits and automatically calculated balance due
- Dashboard totals, upcoming orders and payment follow-up
- Expense logging
- Ingredient-based recipe costing and saved estimates
- Customer rollup from orders
- Copy/share order summary suitable for WhatsApp
- JSON data export
- Pricing page and demo paywall (no real payment processing)

## Run
Open `index.html` in a modern browser, or host this repository as a static site. No build step or external dependency is required.

## Important limitations
- All records live in the current browser's local storage. No cloud sync, server backup, secure authentication, multi-user separation or recovery.
- The login form is a local prototype gate only. It does not authenticate identities.
- Plan prices and the paywall are demonstrations only. No subscriptions are sold and no payments are processed.
- Financial totals are simple estimates, not accounting or tax advice. Dashboard estimated net uses total order value less recorded expenses and may not equal cash profit.
- Do not enter sensitive or important real customer information until secure storage, authentication and backups are implemented and tested.

## Next steps
1. Test order create/edit/delete and verify balance calculations.
2. Test on phone and desktop; fix defects.
3. Gather feedback from a few bakers before committing to pricing.
4. Only after validation, assess secure accounts/database and a payment provider.
