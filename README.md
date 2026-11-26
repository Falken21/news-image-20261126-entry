# The World Today — 26 November 2026 in one image

[![make.fun · news-image-20261126](https://make.fun/badge/news-image-20261126.svg)](https://make.fun/bounty/news-image-20261126?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)
[![rank](https://make.fun/badge/news-image-20261126/Falken21/news-image-20261126-entry/rank.svg)](https://make.fun/bounty/news-image-20261126/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)
[![reward](https://make.fun/badge/news-image-20261126/Falken21/news-image-20261126-entry/reward.svg)](https://make.fun/bounty/news-image-20261126?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)

Entry for the make.fun competition **news-image-20261126**: sum up the world
news of Thursday 26 November 2026 in a single image.

The image is a classic newspaper front page, *The World Today*, dated
Thursday 26 November 2026. Seven stories pair a press-style photograph with
a category kicker, a bold headline and a short factual summary:

- **TRADE (lead)** — Trump proposes new tariffs on 14 trading partners
- **MARKETS** — Asia shares bounce after Wall Street's AI rout
- **UKRAINE** — Ukraine says a strike disabled five Russian jets
- **SPORT** — Teen prodigy Sooryavanshi smashes 204 off 53 balls in Doha
- **AMERICAS** — Police storm a supermarket to free 20 hostages
- **SPACE** — First Pakistani astronaut flies to China's Tiangong
- **EGYPT** — Fuel tanker fire kills 31 on a Cairo ring road

A "JUGA HARI INI" strip along the bottom carries nine more one-line briefs
from the day, and the folio line discloses that the photographs are
AI-generated illustrations.

## How it works

`main.py` (Python 3.13, standard library only) holds the finished front
page as base64-encoded JPEG bytes and writes them, byte for byte, to
`/output/entry.png` (or to `$MAKEFUN_OUTPUT_DIR/entry.png` when that
variable is set). It needs no network and no input, and every run writes
exactly the same bytes.

- Image: 1024 × 1024, JPEG bytes in a file named `entry.png`, under 1 MiB
- Run it: `mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py`

## License

MIT — see `LICENSE`.
