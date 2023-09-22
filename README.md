# [clayell.is](https://clayell.is)

## Development

Run `jekyll serve` from the root directory then visit `localhost:4000` (or whatever port `serve` binds to) to view changes.
After changes have been made, commit and push to deploy. In the Gemfile there are two mutually exclusive dependencies. One is `jekyll` and the other is `github-pages`.
When developing locally, use `jekyll`. But before pushing, make sure `github-pages` is used.