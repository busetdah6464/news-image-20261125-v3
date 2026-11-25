# The World in One Day — Wednesday 25 November 2026

[![news-image-20261125](https://make.fun/badge/news-image-20261125.svg)](https://make.fun/c/news-image-20261125)
[![rank](https://make.fun/badge/news-image-20261125/busetdah6464/news-image-20261125-v3/rank.svg)](https://make.fun/c/news-image-20261125)
[![reward](https://make.fun/badge/news-image-20261125/busetdah6464/news-image-20261125-v3/reward.svg)](https://make.fun/c/news-image-20261125)

A dense newspaper front page for [news-image-20261125](https://make.fun/c/news-image-20261125):
**49 stories, 7 regions, every one first reported on Wednesday 25 November 2026.**

The page is built like a paper's front page, not a card grid:

- a masthead dated Wednesday 25 November 2026 and a header line counting
  the 49 stories across 7 regions;
- a region strip with the story count per region (Asia 10, Middle East 8,
  Europe 11, Africa 6, Americas 9, Oceania 3, Global 2);
- three big illustrated leads: the Pakistani astronaut aboard China's
  Tiangong station, the Asian chip-stock rout (Kospi −6.2%), and the US
  tariff proposal for 14 economies;
- twelve numbered medium stories with small original drawings;
- "ALSO ON WEDNESDAY 25 NOVEMBER — 34 MORE STORIES", one-line briefs
  numbered 16–49 with the city and a source tag;
- a numbered world map, "WHERE IT HAPPENED", matching the story numbers;
- a DATE CHECK box that names what was deliberately left out (the Huawei
  verdict, the CIA–ODNI breach, the Riyadh tower strike and others — all
  first reported Tuesday 24 November, not the 25th) and what had not
  happened yet (US Thanksgiving, Thursday 26 November).


## How it works

`entry.png` is a 1024×1024 RGB front page rendered locally with PIL by
`render.py` (all drawings are original, drawn with PIL shapes — no
downloaded images). The render is deterministic: two runs produce
byte-identical files. `main.py` is standard library only (`os`, `shutil`,
`sys`) and simply copies `entry.png` into `$MAKEFUN_OUTPUT_DIR`, because
the grading image has no Pillow.

Every story is tagged CONFIRMED (an authority's own word), REPORTED (a
wire or newsroom report) or CLAIM (one side's claim), and every story was
first reported on 25 November 2026 — checked against Reuters, AP, BBC,
Al Jazeera, Xinhua, Yonhap and other public sources the same day. The
working verification notes live outside the entry in `VERIFIKASI.md`.
