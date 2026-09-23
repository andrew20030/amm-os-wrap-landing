# Abernathy AI Marketing and Media · Operating System (wrap landing)

Self-contained static landing that **wraps** the live Grok Dual Ops app and **embeds** the interactive Ops Desk so the OS is usable inside one page.

## What this is

- Brand: Abernathy AI Marketing and Media Operating System (navy `#0b1f3a` / gold `#c9a227`)
- SPA-style tabs: Overview · Ops Desk · Grok App · Getting Started · Lead Source
- Ops Desk inlined from the overnight pack (Jobs 8-slot, Workflow 01–06, Launch gated on `localStorage amm-gmail-connected`, LIVE Talk to Grokbot)
- Grok Dual Ops iframe: `https://wolf-brush-fjord-xenon.grok.me` (plus “Open in new tab”)
- Pipeline data inlined — works on `file://` and single-file host with no relative fetches
- Checkout is a **disabled stub labeled NOT LIVE** — no charges
- `$497 OS` copy is marketing only; purchase path: separate / not live on this deploy

## Publish SEPARATELY — never overwrite the marketing site

**Do NOT** deploy this folder to `https://abernathy-marketing-media.vercel.app` or any existing Vercel project that serves that URL.

- The sales / marketing page at `abernathy-marketing-media.vercel.app` must stay unchanged.
- This wrap landing is a **brand-new, separate deploy** (new project / new URL).
- After publish, replace `PLACEHOLDER_URL` in `DESKTOP-SHORTCUT.url` with the new URL.

## Deep links

- `?workspace=amm-os` — soft workspace flag on the page
- `#overview` · `#ops` · `#grok` · `#started` · `#leads` — open the matching tab on load

## Live URL

See repo homepage / GitHub Pages once enabled, or jsDelivr: `https://cdn.jsdelivr.net/gh/andrew20030/amm-os-wrap-landing@main/index.html`
