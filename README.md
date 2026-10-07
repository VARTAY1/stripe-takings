# Stripe Takings — hosted checker

A single static page. It calls the Stripe API **directly from the visitor's
browser**, so the host never sees a key: nothing is stored, server-side or
otherwise. Deploy as a *static site* (not a web service) — there is no backend.

Use restricted keys (`rk_live_…`) with read access to Balance, Charges,
Payouts and Account.
