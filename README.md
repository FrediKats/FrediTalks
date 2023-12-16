# Fredi Talks

Когда-то тут появится описание.

P.S. Репозиторий сделано из шаблона [@yegor256](https://github.com/yegor256/bloghacks), который `Feel free to clone it and copy`. Спасибо, Егор.

## How to run it locally

```ps1
docker run -it --rm -v "${PWD}:/b" -p 4000:4000 yegor256/blog-image 'cd /b && bundle update && bundle exec jekyll serve --trace --drafts --future --host 0.0.0.0'
```