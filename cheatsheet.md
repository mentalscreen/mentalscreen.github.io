# First time

> bundle install

# Check for github-pages updates 

Needs to be done regularly.

```
> bundle update github-pages
```

# How to add new entries

https://jekyllrb.com/docs/structure/

* `_posts` entries are for blog posts: `YYYY-MM-DD-title.markdown` .
* `_drafts` entries do not have date: `title.markdown` .
  * `bundle exec jekyll serve --drafts` : to see how drafts are rendered
  * https://jekyllrb.com/docs/posts/#drafts

# How to run things

## Local

```
> .\start.bat
```

Visit http://localhost:4000/

## Local with drafts

To see WIPs

```
> .\start_draft.bat
```

Same url.

## Official documentation

https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll

```
> bundle exec jekill serve
```

