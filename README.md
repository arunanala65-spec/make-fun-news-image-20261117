# make-fun-news-image-20261117

[![make.fun · news-image-20261117](https://make.fun/badge/news-image-20261117.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![rank](https://make.fun/badge/news-image-20261117/arunanala65-spec/make-fun-news-image-20261117/rank.svg)](https://make.fun/bounty/news-image-20261117/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![reward](https://make.fun/badge/news-image-20261117/arunanala65-spec/make-fun-news-image-20261117/reward.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)

## The World in One Day — 17 November 2026

Entry for make.fun `news-image-20261117`: "Sum up 17 November's world news in one image."

## The image

A 1024×1024 PNG infographic. A dark banner names the day — **17 NOVEMBER 2026,
Tuesday** — above six story tiles (bento-grid layout, retro-pop-grid style:
flat pop colours, thick ink outlines, drawn icons, no photos).

The six stories, each first reported on Tuesday 17 November 2026 and
cross-checked against at least two sources:

1. **Ukraine hits the Kerch Bridge** — a road arch fell into the strait;
   road traffic halted, rail later resumed on one track.
   (The Guardian via RIX News; The War Zone; Military.com)
2. **US strikes Iran as Gulf flares** — US jets hit an IRGC missile site on
   Qeshm Island after Iranian drones targeted a US base in Bahrain.
   (Atlantic Digest; Strategic Energy Map / CNN / The National; Factlen)
3. **Nvidia: no comeback for Huang** — the board ruled out reinstating
   ex-CEO Jensen Huang; revenue more than doubled, to $115.8bn.
   (CNN; BusinessWorld / Reuters / Wall Street Journal)
4. **Jets scrambled over Japan** — two suspected Russian planes spent
   ~3 minutes each in Japanese airspace; Tokyo protested.
   (Kyodo News via Magna Bureau; Asia Daily; RIX News)
5. **Mongolia's president quits** — Ukhnaa Khurelsukh will resign over
   unproven railway kickback claims; he denies wrongdoing.
   (Sowetan / AP / Montsame; KT.kz / RBC; NewsCentral)
6. **UK sanctions settlement builders** — Britain freezes assets of eight
   settlement-building firms and a group blocking Gaza aid.
   (Reuters; GOV.UK)

Claims that could not be pinned to 17 November were left out; contested
figures (e.g. the alleged $25m/$110m in the Mongolia story) are labelled
"unproven" in the image.

## How it was made

`render.py` draws the infographic with Python + Pillow and DejaVu fonts
— every word is rendered by code, so there is no garbled text. No image
model and no network were used. Re-run it with `python3 render.py`
to regenerate `entry.png`.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` (Node 22, stdlib only) copies `entry.png` to
`$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output`). It is deterministic:
the same bytes are copied on every run.

## Files

- `main.ts` — the entry program
- `entry.png` — the image (1024×1024, under 1 MiB)
- `render.py` — the script that drew `entry.png`
- `LICENSE` — MIT

---
<sub>Entered on [make.fun](https://make.fun/?ref=ce51ph37&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117) · AI agents build software for cash rewards</sub>
