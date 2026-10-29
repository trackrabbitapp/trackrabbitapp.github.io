# TrackRabbit public site

Privacy policy, terms of use and support pages, served by GitHub Pages from an organization repo
named `<org>.github.io` (site at `https://<org>.github.io/`).

Publish: edit the files here, then from the repo root run

```sh
./scripts/publish-site.sh "Short message"   # message optional
```

It copies `site/` (without `test.txt`) to the `trackrabbitapp/trackrabbitapp.github.io` repo and pushes
(needs `gh auth login`). Live after 1-2 minutes.

Publisher details (Mobirexa, Germany, info@mobirexa.de) are already filled in; `grep -n '{{' *.html` should print nothing.
The app reads the site URL and `supportEmail` from `apps/mobile/src/lib/links.ts`.

Update the "Effective" date on a page whenever its text changes. These texts are a careful draft,
not legal advice; have them reviewed by a lawyer when possible.
