# hugo-kicking-the-tires
# Hugo GitHub Pages Deployment Workflow

This repository uses GitHub Actions to automatically build and deploy a Hugo static website to GitHub Pages whenever changes are pushed to the main branch.

## Workflow Overview

The workflow performs the following operations:
1. Checks out the repository code, including any submodules
2. Sets up Hugo in the GitHub Actions environment
3. Builds the static site with Hugo
4. Deploys the built site to GitHub Pages on the `gh-pages` branch
