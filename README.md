# ChatCut — Wireframe Playground

Low-fi wireframe explorations for ChatCut product surfaces. No build step,
no dependencies — open the HTML directly in a browser.

## Open this

👉 **[`Onboarding Prototype.html`](./Onboarding%20Prototype.html)** — the active exploration.

Download the file (or clone the repo) and double-click to open in Chrome/Safari.

## Start states (dev strip, top-right)

The prototype simulates the full lifecycle via a state toggle at the top:

| State         | Simulates                                                          |
| ------------- | ------------------------------------------------------------------ |
| **auth**      | Full lifecycle. Signup → first-run → returning. **Start here.**    |
| `first-run`   | Brand-new user: empty gallery, full-width solo layout.             |
| `returning`   | Existing user with projects: gallery visible, sidebar + content.   |
| `shared-link` | Anonymous viewer landing on someone else's shared cut. *(see note)*|

> **Note on `shared-link`:** lower priority. It's a surface the AI added
> while sketching — not a current product priority. Keeping it around as a
> directional placeholder for a potential future feature.

## Recommended path

**Start in `auth` mode.** It's the only path that exercises the full arc —
sign in, hit the creator home, pick a scenario or "just talk to me", go
through prompt reveal → running → post (cut ready), see the tabbed right
panel appear when there's real output to show.

The other three states jump you directly into a single slice — useful for
reviewing specific phases in isolation, not for feeling the full flow.
