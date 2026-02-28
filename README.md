# just-the-docs-template

This is a template repository that contains:

- A [Jekyll] site using the [Just the Docs] theme for the repository documentation in the \`docs\` folder
- GitHub [Actions workflow] to build and publish the site to GitHub Pages
- MIT License for source code
- Creative Commons License for the site documentation
- Notice file for attributions

To get started with creating a site, simply:

1. click "[use this template]" to create a GitHub repository
2. go to Settings > Pages > Build and deployment > Source, and select GitHub Actions

After completing the creation of your new site on GitHub, update it as needed:

## Replace the content of the template pages

Update the following files to your own content:

- `README.md` (information for those who access your site repo on GitHub)
- `_config.yml` (site title, description, and repository URL)
- `NOTICE` (attributions for any third-party content you use in your site)

## Building and previewing your site locally

Assuming [Jekyll] and [Bundler] are installed on your computer:

1. Change your working directory to the root directory of your site.
2. Run `bundle install`.
3. Run `bundle exec jekyll serve` to build your site and preview it at `localhost:4000`.

The built site is stored in the directory `docs/_site`.

## Customization

You're free to customize sites that you create with this template, however you like!

[Browse our documentation][Just the Docs] to learn more about how to use this theme.


### Copy the template files

1. Create a `.github/workflows` directory at your project root if your repo doesn't already have one. Copy the
   `pages.yml` file into this directory.
2. Create a `docs` directory at your project root and copy all remaining template files into this directory.
3. Copy the `LICENSE` and `NOTICE` files to your project root.


## Licensing and Attribution

This repository is licensed under the [MIT License]. You are generally free to reuse or extend upon this code as you see
fit; just include the original copy of the license (which is preserved when you "make a template"). While it's not
necessary, we'd love to hear from you if you do use this template, and how we can improve it for future use!

The deployment GitHub Actions workflow is heavily based on GitHub's mixed-party [starter workflows]. A copy of their MIT
License is available in [actions/starter-workflows].


[Jekyll]: https://jekyllrb.com
[Just the Docs]: https://just-the-docs.github.io/just-the-docs/
[GitHub Pages]: https://docs.github.com/en/pages
[GitHub Pages / Actions workflow]: https://github.blog/changelog/2022-07-27-github-pages-custom-github-actions-workflows-beta/
[Bundler]: https://bundler.io
[use this template]: https://github.com/just-the-docs/just-the-docs-template/generate
[`jekyll-default-layout`]: https://github.com/benbalter/jekyll-default-layout
[`jekyll-seo-tag`]: https://jekyll.github.io/jekyll-seo-tag
[MIT License]: https://en.wikipedia.org/wiki/MIT_License
[starter workflows]: https://github.com/actions/starter-workflows/blob/main/pages/jekyll.yml
[actions/starter-workflows]: https://github.com/actions/starter-workflows/blob/main/LICENSE
