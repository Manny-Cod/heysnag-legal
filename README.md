# heysnag-legal

Public web home for Snag's legal docs. Auto-deployed to `https://heysnag.app/` via GitHub Pages.

| URL | Source file |
|---|---|
| `https://heysnag.app/` | `index.md` |
| `https://heysnag.app/privacy/` | `privacy/index.md` |
| `https://heysnag.app/terms/` | `terms/index.md` |

## Source of truth

The canonical Privacy Policy and Terms of Service live in the private app repo at `snag-review/legal-web/{privacy,terms}.md`. The files in this repo are **derivatives** — every update flows from canonical → here AND → `app/src/screens/{Privacy,Terms}Screen.tsx` as one atomic commit per the drift-discipline rule.

Do not edit the markdown in this repo directly. Update the canonical source first, copy here second, push as part of the same PR cycle.
