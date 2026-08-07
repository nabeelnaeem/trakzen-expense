# Trakzen static pages

Two one-screen static pages for my own Trakzen workspace. Both contain **no
credentials and no data** — each is a single file that calls a private API and
gets nothing back without a token. This repository is public only because
GitHub Pages requires it; the application itself is private.

## Quick add expense

Logs an expense from a phone. The access token is typed in once on the device
and kept in `localStorage` (optionally encrypted under a PIN).

<https://nabeelnaeem.github.io/trakzen-expense/>

## Client portal

Shows a client the hours logged for them, a whole month at a time, and lets
them send a note back. The token travels in the link, and resolves server-side
to exactly one client: there is no parameter through which it could return
anyone else's hours, an invoice, or anything else in the workspace. Rotating
the link in the app revokes it.

<https://nabeelnaeem.github.io/trakzen-expense/client/?t=TOKEN>
