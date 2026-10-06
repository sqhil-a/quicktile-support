# QuickTile support

Setup, troubleshooting, and privacy links for the QuickTile iPhone app and Mac companion.

- Repository: https://github.com/sqhil-a/quicktile-support
- Pages root: https://sqhil-a.github.io/quicktile-support/
- Official support page: https://sqhil-a.github.io/quicktile-support/support.html
- Contact: sahilambegaonkar@gmail.com

This is a static documentation site, not the QuickTile app source repository.
It uses system fonts, local original vector assets, and no tracking or scripts.

## Publish when ready

These files are exported locally; no publication is implied.
Choose **Settings → Pages → Build and deployment → Source: GitHub Actions**.
The included workflow can deploy after a push to `main` or a manual run on `main`.
It uploads only public HTML, CSS/SVG assets, `.nojekyll`, `robots.txt`, and the sitemap.
README, workflow files, build metadata, and the export manifest are excluded.

The authored templates and exporter live in the QuickTile workspace under
`website/` and `Scripts/`. Re-export from there after changes. The exporter refuses
to overwrite files changed here; reconcile edits in the source workspace first.

Workflow reference: https://docs.github.com/en/pages/getting-started-with-github-pages/using-custom-workflows-with-github-pages
