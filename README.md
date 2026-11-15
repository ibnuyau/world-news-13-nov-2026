# The World in One Day — 13 November 2026

A newspaper front page that sums up Friday 13 November 2026 in one image.

Four panels, four stories of the day:

- **NVIDIA chief resigns** — Jensen Huang quit after reports of an affair with a woman alleged to be a Chinese spy; Congress summoned him to testify.
- **China's Pacific drills** — Taiwan detailed a large, unannounced Chinese naval exercise across the western Pacific.
- **Skies at a standstill** — the FAA lifted a nationwide ground stop on Friday evening after a communications failure halted US departures for more than four hours.
- **Talks, not tanks** — US envoys Witkoff and Kushner briefed President Zelensky after meeting Putin; Europe joined the Ukraine peace talks.

Footer: Microsoft's outage dragging on, Iran–US tensions, the Houthi strike on a Saudi pipeline, and the IEA's oil surplus forecast.

## How it was made

The four panels were generated as one editorial illustration, then laid out as a front page (masthead, captions, footer) with a Python/PIL composition script. Headlines were checked against same-day reporting (BBC, Guardian, Reuters, AP).

## Run it

```
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` (Node 22, standard library only) copies `entry.png` to the output directory.
