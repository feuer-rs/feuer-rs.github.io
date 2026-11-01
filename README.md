# Feuer website

Published at https://feuer-rs.github.io/ using GitHub Pages.

The Docusaurus source is maintained in
[PSeitz/feuer/website](https://github.com/PSeitz/feuer/tree/main/website).
This repository contains the publishing workflow.

## Publish

Open [Actions → Deploy website](https://github.com/feuer-rs/feuer-rs.github.io/actions/workflows/deploy.yml)
and choose **Run workflow**. The workflow builds the current `main` branch of
`PSeitz/feuer` and deploys it using this repository's built-in `GITHUB_TOKEN`.
No deploy key or personal access token is required.

Pushing to this repository also triggers publishing. Pushing to `PSeitz/feuer`
does not trigger publishing automatically.
