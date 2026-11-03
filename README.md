# Content Hive Plugin: 即刻

适用于 Content Hive 的即刻内容解析插件，支持图文、Live Photo 及视频帖子的内容解析。

Plugin for [Content Hive](https://github.com/content-hive/content-hive).

## Layout

```
plugin/              # plugin source, installed as plugins/jike/ by Content Hive
├── manifest.json    # plugin metadata (domain, version, requirements, release_notes)
├── __init__.py
└── ...
contenthive.json     # repository metadata for the Content Hive plugin catalog
```

## Releasing

1. Bump `version` and rewrite `release_notes` in `plugin/manifest.json`.
2. Merge into `main`.
3. Publish a GitHub Release whose tag is `v<version>` (for example `v0.1.1`).
