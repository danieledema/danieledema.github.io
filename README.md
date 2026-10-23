# Daniele De Martini — personal website

This Hugo site contains the personal profile, career-wide publication archive,
selected work and contact details. The [Mobile Robotics Group website](https://ori-mrg.github.io/)
owns current project descriptions, team information, news and application guidance.

## Content ownership

- Edit the biography in `content/myself/_index.md`. It is rendered on the homepage;
  `/myself/` redirects there. Its `headline` and `intro` fields appear above the
  profile shortcuts. The sidebar role and institution are set in `hugo.toml`;
  `params.description` supplies the homepage's search and sharing description.
- Edit the short highlights in `content/selected-work/_index.md`. Link to the main
  project pages rather than copying their content. Publication links resolve from
  the existing archive and a missing reference fails the build.
- Keep individual publication records in `content/publications/`. These have been
  retained. Until a shared catalogue is introduced, link to this archive from MRG
  instead of copying publication records; no automatic synchronisation is configured.
- Keep personal contact details in `content/contacts/_index.md`. Application
  guidance is linked to MRG rather than maintained here.
- Change `params.group_url` in `hugo.toml` to update the shared MRG links. The
  `mrg-link` shortcode supports a relative `path` and link `text`.

The old `/research/` URL redirects to the homepage's research interests section.
`/research/2024_robotcycle/` redirects to the RobotCycle project website.
These are HTML redirects, supported by GitHub Pages, with canonical URLs and
fallback links. The existing publication URLs and downloadable files are retained.

## Preview and build

Use Hugo Extended 0.128.0, matching the GitHub Pages workflow:

```sh
git submodule update --init --recursive
hugo server
hugo --minify
```

Site templates in `layouts/` and styles in `assets/css/custom.css` override the
Poison theme without modifying the submodule.
