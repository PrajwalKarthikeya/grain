<div align="center">

# grain - a minimal rice timer

**Cups in, countdown out.**

[![Live Site](https://img.shields.io/badge/live-grain--bice.vercel.app-F2B64E?style=for-the-badge&logo=vercel&logoColor=white)](https://grain-bice.vercel.app/)

A tiny, dark-mode-first web app that estimates your rice cook time and counts down every second until it's ready, then blows the steam whistle when it's done.

</div>

## How to use

1. Enter how many cups of **rice** you're cooking
2. Enter how many cups of **water** you're pouring in
3. Hit **Start cooking**: the timer tells you exactly when your rice will be ready

That's it. No accounts, no ads, no cookies.

## What you get

- A live countdown ring with cooking phases: **heating → absorbing → resting**
- A wall-clock **ready by** time so you can plan the rest of your meal
- Instant feedback on your water ratio before you commit
- A pressure-release steam blast when the rice is done
- Dark / light mode that follows your system, switchable anytime

## How the timer works

Times are estimates for white rice using the absorption method:

| Phase     | Duration                |
| --------- | ----------------------- |
| Heating   | 5 min                   |
| Absorbing | 8 min + 2.5 min per cup |
| Resting   | 10 min                  |

## Water ratio guide

| Ratio (rice : water) | Result                    |
| -------------------- | ------------------------- |
| 1 : 1.25 - 1.75      | Classic fluffy texture    |
| Below that           | Firm and chewy            |
| Above that           | Soft, bordering on congee |

`grain` will warn you if your ratio looks off before you start.

## Run locally

No build step, no dependencies: just open `index.html` in any browser.

## Deploy your own

It's a single static file, so hosting it anywhere is trivial. On Vercel: import this repo, pick **Other** as the framework preset, leave everything else empty.

---

Made with too much rice.
