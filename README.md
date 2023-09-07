# My personal site on GitHub Pages

- https://fmsaraujo.dev
- https://fmsaraujo.github.io

## Update the 'github-pages' gem

Main article: https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll

1. Navigate to the `docs` folder.
1. Open the Gemfile that Jekyll created.
1. Locate line `gem "github-pages", "~> 228", group: :jekyll_plugins`.
1. Replace `228` with the latest supported version of the `github-pages` gem.
You can find this version here: "[Dependency versions](https://pages.github.com/versions/)".
1. From the command line, run `bundle install`.

## Testing locally

```sh
cd docs
bundle install
bundle exec jekyll serve
```
