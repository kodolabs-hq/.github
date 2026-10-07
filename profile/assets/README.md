# Brand assets

`kodo-labs.png` is the supplied Kodo Labs organization logo, preserved without
modification. It appears in the organization profile and its repository preview.

The `*-social.png` files are wide GitHub repository preview cards. They combine
the existing logos with accurate project descriptions. The editable layout is
[`docs/social-preview-cards.html`](../../docs/social-preview-cards.html).
Serve the repository locally, open that page with `?card=org`, `?card=cli`, or
`?card=web`, and capture its 1280 by 640 CSS-pixel card to regenerate the exports.

The `bonjou-*` files are product logo exports copied from
`kodolabs-hq/bonjou-web/public/brand/`.
The canonical geometry is `bonjou-web/src/share/brandMark.json`; run
`npm run generate:brand` there before updating these copies.

Use `bonjou-avatar.png` for Bonjou product artwork. Its padding keeps the mark
clear in square and circular crops. Use `bonjou-mark.svg` on transparent
backgrounds in product documentation.
