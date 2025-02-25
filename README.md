# hugo-kicking-the-tires
This repository uses GitHub Actions to automatically build and deploy a Hugo static website to GitHub Pages whenever changes are pushed to the main branch.
Workflow Overview
The workflow performs the following operations:

Checks out the repository code, including any submodules
Sets up Hugo in the GitHub Actions environment
Builds the static site with Hugo
Deploys the built site to GitHub Pages on the gh-pages branch
