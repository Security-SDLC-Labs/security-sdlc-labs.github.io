# security-sdlc-labs.github.io

Source for <https://security-sdlc-labs.org>, the Security SDLC Labs
organization site.

Hand-written HTML and CSS. No build step, no dependencies, no external requests
(system font stack rather than a font CDN, so visitors are not exposed to a third
party).

This repository holds **only** the organization site. Per-tool documentation is
published from each tool's own repository, so a tool can be transferred to
another maintainer or adopting organization without untangling its docs from
here.

## Editing

Edit `index.html` and push to `main`. GitHub Pages redeploys automatically.

`CNAME` pins the custom domain; do not remove it.
