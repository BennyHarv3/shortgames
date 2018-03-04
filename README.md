# One-Shot RPG Games

This is a (growing) list of short tabletop RPG games I'm writing. Consider all
of these games for free use. If you use one, please just attribute this back to
me.

## Adding New Games

Create a Markdown (.md) file in the `_games` directory. Add the
[Jekyll Front Matter](https://jekyllrb.com/docs/frontmatter/) block to the top
of the file and add a `title` field.

## Adding Ideas

If you have an idea, create a Markdown (.md) file in the `ideas` directory. Add
the [Jekyll Front Matter](https://jekyllrb.com/docs/frontmatter/) block to the
top of the file and add a `title` field.

## Building the Site Locally

The website it using [Jekyll](https://jekyllrb.com/) for static site generation
(built-in to GitHub Pages). To run the site locally, do the following:

```bash
bundle update # update the Gemfile.lock file if it hasn't happened recently
bundle exec jekyll serve # build and launch the website on port 4000
```
