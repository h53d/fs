# ForgeShape App Store policy support

Host this folder as the public Support URL and Privacy Policy URL for App Store Connect.

| File | App Store Connect field |
|---|---|
| `support.html` | Support URL |
| `policy.html` | Privacy Policy URL |
| `index.html` | site root, so a trimmed URL and the structured-data `WebSite` entity resolve |

Published at `https://h53d.github.io/fs/` from the `main` branch of `h53d/fs`.

**GitHub Pages must be enabled for that repository.** Committing and pushing is not
enough: until Pages is turned on, every URL above returns 404, including the two
URLs already submitted in App Store Connect for all four locales.

These pages are **English only, by decision** — not an oversight and not a pending
translation task. The App Store listing is localized in en-US, de-DE, zh-Hans, and
zh-Hant, and all four locales point at these same English URLs.

Pages follow the STEP Reviewer policy-support layout and describe the current
ForgeShape runtime: on-device print checking, dual-lane repair, format conversion,
and optional Reverse to CAD. They do not claim slicer, CNC, cloud AI, accounts, or
in-app purchases.

`.nojekyll` disables GitHub Pages' Jekyll pass. Without it, Pages renders `README.md`
as the site index and can shadow `index.html`; this is a plain static site, so the
build step only adds surprises.

App Store listing: `https://apps.apple.com/us/app/id6801400880` (Apple ID 6801400880).
That link 404s until the app is released; the App Store badges on these pages point
at it.
