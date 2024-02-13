# Deploy release action

Forked/adapted from: [rossjwr/pr-preview-action](https://github.com/rossjrw/pr-preview-action)

[GitHub Action](https://github.com/features/actions) that deploys releases
to [GitHub Pages](https://pages.github.com/). Works on any
repository with a GitHub Pages site.

Features:

- Creates and deploys releases to your GitHub Pages site
- Leaves a comment on the release pull request with a link to the deployment
- Updates the deployment and the comment whenever new commits are pushed to
  the pull request
- Retains the deployed release when the pull
  request is closed

Main URL will still post to:
`https://[owner].github.io/[repo]`

Release URLs look like this:
`https://[owner].github.io/[repo]/release/[release-dir]/`

This branch URL:
https://andermi.github.io/github-pages-deploy-release-action/release/v1.0.1/