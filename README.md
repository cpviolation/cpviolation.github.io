# cpviolation.github.io

Personal website of Maurizio Martinelli (LHCb, University of Milano-Bicocca),
published at <https://cpviolation.github.io/>.

Built with [Jekyll](https://jekyllrb.com) and the [Hydejack](https://hydejack.com/) theme,
deployed automatically by GitHub Pages on every push to `master`.

## Structure

| Path | Content |
|------|---------|
| `research/`, `teaching/`, `outreach/` | Main sections (linked from the sidebar menu) |
| `news/_posts/` | News posts, named `YYYY-MM-DD-title.md` |
| `assets/img/blog/<year>/` | Post images (1920w, `@0,5x` and `@0,25x` versions) |
| `_config.yml`, `_data/` | Site settings, author info, social links |

## Running locally

```sh
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000/>.
