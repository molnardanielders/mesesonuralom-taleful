# Mesés önuralom · Taleful

**The first children's story channel that knowingly ends.** / *Az első gyerekmese-csatorna, aminek tudatosan vége van.*

A gentle, finite children's story programme for little ones (≈0–3). The parent answers one question — **heart or mind?** — the system serves an age-appropriate story at a sensible length, and **the child closes the story themselves** with a calm countdown and a goodnight ritual. No autoplay, no "next episode" — the ending bridges to bath, lunch or leaving.

🌍 **Live:** 🇭🇺 [mesesonuralom.hu](https://mesesonuralom.hu) · 🇬🇧 [taleful.eu](https://taleful.eu)

---

## Two paths — one way or another, it has to exist

1. **On our own, at home** — a parent builds it for their own children; it can work for one family, but lawful content sourcing and wide, legal availability stay unsolved.
2. **Championed** — a serious partner (e.g. public-service media) licenses the stories and provides a team and resources, making it a real, legal product for every family.

Both share the same principles: **we communicate openly and publish our results.** This repository is that open face of the project.

## What's in here

```
site-hu/     The Hungarian website (deployable static site) + the five printable guides (PDF)
site-en/     The English website (deployable static site)
docs/        concept.md · pitch.md · the five role guides (HTML source)
design/      arculat.html (visual identity) · esti-mese-motivumok.svg (motifs / designer kit)
demo/        koncepcio.html — the playable, step-by-step concept walkthrough
pontozo/     pontozo-sablon.xlsx — the scoring template (methodology + generic example rows)
```

The five roles / open positions: **the pirate** (content), **the researcher** (classification), **the developer** (system), **the lawyer** (legal), **the designer** (look) — and a sixth: *what we don't yet know.*

## Licences (dual)

- **Concept, documentation and design** (everything in `docs/`, `design/`, `demo/`, `pontozo/`, and the text/visuals of the sites): **CC BY-SA 4.0** — see [`LICENSE-CONTENT-CC-BY-SA-4.0.txt`](LICENSE-CONTENT-CC-BY-SA-4.0.txt).
- **Code** (the HTML/CSS/JS in `site-hu/` and `site-en/`): **GPLv3** — see [`LICENSE-CODE-GPLv3.txt`](LICENSE-CODE-GPLv3.txt).

Please keep attribution and share alike.

## What is NOT here (and why)

This is the **open, legal** project. It contains **only original work** (concept, documentation, design, code) and an **empty methodology template** with generic example rows.

It deliberately does **not** contain any copyrighted stories/videos, any lists of real titles, or any guidance on obtaining copyrighted content. The legal route for content is **licensing**.

## Deploying the sites

Each site folder is a plain static site. On Netlify (or any static host), point a project at `site-hu/` or `site-en/` as the publish directory. The Hungarian site serves its PDF guides from alongside `index.html`.

## Get involved

See [`docs/concept.md`](docs/concept.md) for the full picture and [`docs/pitch.md`](docs/pitch.md) for the short version. If you'd like to help with any of the roles — or you see a missing one — the websites have a short contribution form, or open an issue here.

---

*A projekt arculata a matyó–kalocsai hagyomány és egy nagymama hímzett terítője nyomán készült, tisztelettel; a motívumok eredeti rajzok.*

*Note: the founder's native language is Hungarian; Claude helps him communicate in other languages.*
