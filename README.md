# ebrains-cls-interactive.github.io

## CI
- For each push to the repo, a [plan](https://github.com/ebrains-cls-interactive/ebrains-cls-interactive.github.io/actions/workflows/gh-pages.yml) is triggered.
- This will fetch the wizard from its original [repo](https://github.com/antonelepfl/ebrains-wizard) and build it changing the base_url
- The plan will put the built wizard on static/wizard folder and push everything to gh-pages branch from where the full page is served.

### [Ebrains Wizard](https://antonelepfl.github.io/ebrains-wizard/dev)
