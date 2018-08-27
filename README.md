# Samljen

Another simple blog theme for Hexo, inspired by [Choo](https://choo.io/).

## Preview

![Samljen](./Samljen.png)

## Installation

```shell
cd your-blog
git clone https://github.com/chunqiuyiyu/hexo-theme-samljen themes/samljen
```

Modify `_config.yml` in your blog directory and change the value of` theme` to `samljen` (the default is` landscape`).

## Configuration

### RSS

```shell
npm install hexo-generator-feed --save
```

Configure plugin in `_config.yml`.

```yaml
feed:
  type: atom
  path: atom.xml
  limit: 20
  hub:
  content:
  content_limit: 140
  content_limit_delim: ' '
```

### Local Search

```shell
npm install hexo-generator-search --save
```

Configure plugin in `_config.yml`.

```yaml
search:
  path: search.xml
  field: post
  format: html
```

New search page: `hexo new page search`.
```markdown
---
title: Search
type: search
---

```

## Browser support

| IE | Edge | Firefox | Chrome | Safari | iOS Safari |
| -- | ---- | ------- | ------ | ------ | ---------- |
| 11+| 17+  | 61+     | 49+    | 11.1+  | 10.3+      |


## License

[MIT](LICENSE)
