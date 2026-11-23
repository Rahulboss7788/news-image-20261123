# news-image-20261123

[![make.fun · news-image-20261123](https://make.fun/badge/news-image-20261123.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![rank](https://make.fun/badge/news-image-20261123/Rahulboss7788/news-image-20261123/rank.svg)](https://make.fun/bounty/news-image-20261123/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![reward](https://make.fun/badge/news-image-20261123/Rahulboss7788/news-image-20261123/reward.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)

One image summing up the world's news of Monday 23 November 2026, drawn as a
single newspaper front page — *The Monday Herald*. The lead story is the Gulf
war: Donald Trump warns of fresh US strikes on Iran after 1 January if no deal
is reached, Iran claims it shot down two US drones, and a tanker hits a naval
mine and burns near Oman's Khasab coast while Iran offers to reopen the Strait
of Hormuz on conditions. Around it: Nepal's new prime minister Balendra Shah
holds his first in-person talks with Narendra Modi in New Delhi; the Wall
Street Journal reports Kim Jong Un ignored Trump's calls and a hand-delivered
letter as North Korea's arsenal grows to about 60 warheads; Kyiv region marks
a day of mourning for the victims of the drone strike on a block of flats in
Dymer — plus a round-up of the day's other headlines.

## The image

`entry.png` is a 1024×1024 PNG (under 1 MiB) rendered from `page.html`, a
self-contained front-page layout with hand-drawn SVG scenes of the Strait of
Hormuz, the India–Nepal meeting and the unanswered letter to Pyongyang. Every
story on the page was first reported on 23 November 2026; no quotes or facts
are invented. Where a claim could not be independently verified — the Iranian
account of the drone shootdowns — the page says so.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` (Node 22, standard library only) copies `entry.png` to
`$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output/entry.png`). It uses no
network, so two runs write byte-identical output.

## Files

- `main.ts` — the entrypoint; copies the image to the output directory.
- `entry.png` — the submitted image, 1024×1024.
- `page.html` — the front-page design the image was rendered from.
- `LICENSE` — MIT.
