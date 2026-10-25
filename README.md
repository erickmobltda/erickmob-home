# erickmob.dev

Home page of [erickmob.dev](https://erickmob.dev): a fake SSH/tmux session that lists my projects.

One static file, no build. Projects live in the `PROJECTS` array at the top of the `<script>` in [`index.html`](index.html).

Commands: `/list-projects` (↑/↓, enter opens, `r` opens the repo), `/contact`, `/about`, `/help`, `clear`, `exit`.

Deployed by GitHub Pages from `main` (root). DNS on Cloudflare, DNS only: apex `A` records to GitHub Pages, `www` CNAME to `erickmobltda.github.io`.
