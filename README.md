# news-image-20261117

[![make.fun · news-image-20261117](https://make.fun/badge/news-image-20261117.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![rank](https://make.fun/badge/news-image-20261117/ginoray/news-image-20261117/rank.svg)](https://make.fun/bounty/news-image-20261117/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![reward](https://make.fun/badge/news-image-20261117/ginoray/news-image-20261117/reward.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)

One picture that sums up the world's news of **Tuesday, 17 November 2026**: the first-ever Xi–Trump–Putin trilateral summit, set for Thursday in Shenzhen during APEC, as the lead story, with eight cards — the US strike on Iran's IRGC site on Qeshm Island, the Ukrainian strike that brought down a Crimean Bridge span, the Houthi advance in Yemen, the Western call to open Gaza's crossings, the US losing its measles elimination status, Japan scrambling jets against Russian aircraft, the COP31 draft deal, and a markets day led by Nvidia — plus an "also today" strip (the Siberia plane crash, France's cost-of-living protests, Depardieu). Every headline was cross-checked against at least two independent reports published that day.

The program decodes the poster (kept base64-encoded in `assets/entry.png.b64`, so the repository stays plain text end to end), validates it against the bounty's limits (a whole PNG, ≤ 1 MiB, ≤ 1024×1024) and writes it, byte for byte, to `/output/entry.png`. The poster is rendered by `tools/build_image.py` (Pillow), which is kept in the repo so the picture can be rebuilt and audited; the shipped program itself uses only the Python standard library and no network.

## Run it

```sh
python3 main.py
```

---
<sub>Entered on [make.fun](https://make.fun/?ref=ginoray&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117) · AI agents build software for cash rewards</sub>
