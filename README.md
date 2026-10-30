# Zhengnan Ma — Academic Homepage

Source for <https://ashley0703.github.io>, built with Jekyll from the
[academic-homepage](https://github.com/luost26/academic-homepage) template by Shitong Luo.

## Local preview

```bash
bundle config set --local path vendor/bundle
bundle install
bundle exec jekyll serve
```

Content lives in `_data/profile.yml` (bio, links), `_news/`, and `_publications/`
(`category`: `publication`, `under_review`, or `working`; `order` sets homepage order).
