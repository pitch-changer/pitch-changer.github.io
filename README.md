# Pitch Changer
From practice to production, [Pitch Changer](https://pitch-changer.com/) helps musicians transpose, shift pitch, change song key and process audio with power and precision.

This repo contains the Jekyll source for the product website hosted on GitHub Pages: https://pitch-changer.com/.

## Local development
1. Use the Ruby version from [.ruby-version](/Users/navi/projects/extensions/pitch-changer.github.io/.ruby-version).
2. Install gems with `bundle install`.
3. Start the site with `bundle exec jekyll serve`.
4. Open the local URL printed by Jekyll and test both `/` and `/ru/`.

## Localization
- English lives at `/`.
- Russian lives at `/ru/`.
- Locale copy is stored in `_data/locales/`.
- Shared layout and partials render both locales as static HTML for search engines.

## Deployment
- GitHub Pages is deployed through the workflow in [.github/workflows/pages.yml](/Users/navi/projects/extensions/pitch-changer.github.io/.github/workflows/pages.yml).
- The workflow builds the site with Jekyll `4.4.1` on Ruby `4.0.2` and uploads the generated `_site` artifact to Pages.
