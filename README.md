# TrackRabbit public site

Privacy policy, terms of use and support pages, served by GitHub Pages from an organization repo
named `<org>.github.io` (site at `https://<org>.github.io/`).

Before publishing, replace the placeholders (macOS sed):

```sh
cd site
sed -i '' -e 's/{{PUBLISHER_NAME}}/Jane Doe/g' \
          -e 's/{{PUBLISHER_COUNTRY}}/Germany/g' \
          -e 's/{{CONTACT_EMAIL}}/support@example.com/g' *.html
grep -n '{{' *.html   # should print nothing
```

Then set `SITE` in `apps/mobile/src/lib/links.ts` to the site URL (and `supportEmail`).

Update the "Effective" date on a page whenever its text changes. These texts are a careful draft,
not legal advice; have them reviewed by a lawyer when possible.
