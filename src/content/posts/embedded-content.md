---
title: 'Embedded Content'
pubDate: '2025-06-06'
---

Use these directives to embed media:

```
::link{url="https://xxxxx.xxx"}

::bilibili{url="https://www.bilibili.com/video/xxxxx"}

::github{repo="username/repo"}
```

```
🟡

When embedded content is still loading,
the table of contents positioning may be inaccurate.
```

## Link Card

::link{url="https://pitchfork.com/reviews/albums/ichiko-aoba-luminescent-creatures/"}

```
🟡

Link Card metadata is fetched automatically during `pnpm dev` and `pnpm build`.
Run `pnpm update-link-metadata --force` to refresh existing entries.

-

To disable Link Card, set `linkCard: false` in `src/config.ts`.
Restart `pnpm dev` for the change to take effect.
```
## BiliBili

::bilibili{url="https://www.bilibili.com/video/BV1Vm421W7pX/?vd_source=c0bc2746a6d2b23de50d26376498b2ff"}

## GitHub

::github{repo="the3ash/astro-chiri"}
