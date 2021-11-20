generate a slideshow with [reveal-ck](https://github.com/jedcn/reveal-ck) (using reveal.js)


# Setup

install:

```bash
gem install reveal-ck
```

config:

```yaml
# config.yml
theme: night
transition: fade
title: testing reveal-ck
author: sohooo
```


# Usage

create `slides.md`, then:

```bash
# generates slides/
reveal-ck generate

# live hosting
reveal-ck serve
```
