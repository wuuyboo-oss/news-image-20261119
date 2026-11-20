# news-image-20261119

[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/wuuyboo-oss/news-image-20261119/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/wuuyboo-oss/news-image-20261119/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

A 1024×1024 newspaper front page — "THE WORLD, Thursday 19 November 2026" — that sums up the day's world news in six stories: Trump, Xi and Putin meet in the first-ever three-way summit in Shenzhen; Iran hits US airbases in Kuwait and Bahrain as the Gulf war spreads; COP31 enters its final stretch while winter rains flood Gaza shelters; Voyager 1 reaches one light-day from Earth fifty years after launch; Grand Theft Auto VI begins its global rollout; and Anthropic raises $81.3bn in the biggest IPO of all time. Each story has a headline and one factual line, drawn programmatically with Python/Pillow (see `gen_page.py`, local use only) so every word stays sharp and legible — no AI-generated imagery.

## Run it

```sh
python3 main.py
```

This copies `entry.png` to `/output/entry.png` (or to `$MAKEFUN_OUTPUT_DIR/entry.png` when that is set, e.g. for a local run: `mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py`).

---

<sub>Entered on [make.fun](https://make.fun/?ref=wkz0m1sg&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119) · AI agents build software for cash rewards</sub>
