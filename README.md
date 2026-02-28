# Just the Docs Template

Just the Docs template for creating the Documentation site for a GitHub repository. This template repository includes:

- A [Jekyll] site configured with the [Just the Docs] theme, located in the `docs` folder
- A GitHub [Actions workflow] in the `.github/workflows` folder to build and deploy the site to GitHub Pages
- A copy of the [Creative Commons Attribution-ShareAlike 4.0 International License](LICENSE-CC-BY-SA-4.0) in the
  repository root. This license applies to all site documentation content
- A Notice file for third-party attributions in the repository root

## Getting started

To get started with creating a site, simply:

1. Copy the [docs](docs) folder and [.github/workflows/pages.yml](.github/workflows/pages.yml) file into your
   repository.
2. Copy the [LICENSE-CC-BY-SA-4.0](LICENSE-CC-BY-SA-4.0) and [NOTICE](NOTICE) files into your repository root.
3. Go to Settings > Pages > Build and deployment > Source, and select GitHub Actions

After completing the creation of your new site on GitHub, update it as needed:

- `_config.yml` (site title, description, and repository URL)
- `README.md` (information for those who access your site repo on GitHub)
- `NOTICE` (attributions for any third-party content you use in your site)

## Building and previewing your site locally

Assuming [Jekyll] and [Bundler] are installed on your computer:

1. Change your working directory to the root directory of your site.
2. Run `bundle install`.
3. Run `bundle exec jekyll serve` to build your site and preview it at `localhost:4000`.

The built site is stored in the directory `docs/_site`.

## Licensing and Attribution

This repository uses the [Just the Docs] theme for static site generation. A copy of their [MIT License] is included in
the `docs/` folder.

The deployment GitHub Actions workflow is heavily based on GitHub's mixed-party [starter workflows]. A copy of their MIT
License is available in [actions/starter-workflows].

All documentation content within the `docs/` folder is authored by Iván Fernández and licensed under
the [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0) License].

You are generally free to reuse or extend upon the code in this repository as you see fit, provided you comply with the
terms of the respective licenses for the code and documentation.



[Jekyll]: https://jekyllrb.com
[Just the Docs]: https://just-the-docs.github.io/just-the-docs/
[GitHub Pages / Actions workflow]: https://github.blog/changelog/2022-07-27-github-pages-custom-github-actions-workflows-beta/
[Bundler]: https://bundler.io
[MIT License]: https://en.wikipedia.org/wiki/MIT_License
[starter workflows]: https://github.com/actions/starter-workflows/blob/main/pages/jekyll.yml
[actions/starter-workflows]: https://github.com/actions/starter-workflows/blob/main/LICENSE
[Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0) License]: https://creativecommons.org/licenses/by-sa/4.0/
