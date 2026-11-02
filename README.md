# Data standards and integrations for Edu AI

The public version of our design for an integration layer between schools and AI tutoring tools.
The site is published at <https://i-dot-ai.github.io/sovereign-edu-data-public/>.

## View the site on your computer

You need [Docker](https://www.docker.com/). From this folder, run:

```sh
docker run --rm -it -p 4000:4000 -v "$PWD":/site -w /site ruby:3.3 \
  bash -c "bundle install && bundle exec jekyll serve --host 0.0.0.0 --baseurl ''"
```

Then open <http://localhost:4000>. The page updates when you save a file.

If you already have Ruby 3, you can run `bundle install` then `bundle exec jekyll serve` instead.
