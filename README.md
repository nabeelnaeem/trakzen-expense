# Quick add expense

A one-screen phone page for logging an expense to my own Trakzen workspace.

It is a single static file. It contains **no credentials and no data** — the
access token is typed in once on the device and kept in `localStorage`, and
every request goes to a private API that rejects anything without that token.
This repository is public only because GitHub Pages requires it; the
application itself is private.

Served at <https://nabeelnaeem.github.io/trakzen-expense/>.
