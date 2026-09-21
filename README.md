# Good Ppl — public website

Static developer, game, support and privacy pages for Good Ppl.

- Website: <https://goodpplgames.github.io/>
- Erase Garden: <https://goodpplgames.github.io/erase-garden/>
- Privacy policy: <https://goodpplgames.github.io/erase-garden/privacy/>
- Support: <mailto:goodpplsupport.scone011@8shield.net>

## Publishing

GitHub Pages publishes the root of the `main` branch. The `.nojekyll` file
disables Jekyll processing. There is no build step, JavaScript, analytics,
cookie storage, form, remote font or external asset dependency.
Keep **Enforce HTTPS** enabled in Settings → Pages.

The website uses GitHub Pages hosting. The Erase Garden privacy policy
describes the game, not the hosting provider's separate processing.

Publish using an installation token for the organization-owned **Good Ppl Pages**
GitHub App, restricted to this repository. Both Git author and committer must be
`good-ppl-pages[bot] <331293865+good-ppl-pages[bot]@users.noreply.github.com>`.
Do not push with a personal account or add personal co-author/sign-off trailers.
Keep all credentials outside this repository and revoke short-lived tokens after use.

## Adding a game

1. Add `<game-slug>/index.html` and `<game-slug>/privacy/index.html`.
2. Reuse `/assets/style.css` and ordinary links to `/` and the game page.
3. Add the game link to the homepage. Preserve existing game and privacy URLs.
4. Review factual text, contact details, mobile layout and every link before
   committing. After pushing, check the Pages deployment and anonymous HTTPS URLs.

Publish only reviewed website materials. Do not add game source code, Android
builds, credentials, private notes, internal reports or unreviewed asset folders.

## Content

The public pages are in English. The policy is dated September 21, 2026
and describes Erase Garden 0.11.2, including parent-only external links.
No store release, age rating or new device/child test result is claimed.

## GitHub documentation

- [Creating a Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)
- [Publishing from a branch](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
- [Enforcing HTTPS](https://docs.github.com/en/pages/getting-started-with-github-pages/securing-your-github-pages-site-with-https)
