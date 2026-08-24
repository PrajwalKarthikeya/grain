# grain — a minimal rice timer

Cups in, countdown out. A tiny, dark-mode-first web app that estimates your rice cook time and counts down every second until it's ready.

## Features

- Rice and water cup inputs with live water-ratio feedback
- Estimated total time plus a wall-clock "ready by" time
- Animated countdown ring with cooking phases (heating → absorbing → resting)
- Pressure-release steam blast when the rice is done
- Dark / light theme with system detection, preference persisted
- Zero dependencies, single HTML file, works offline

## How the timer works

| Phase     | Duration                  |
| --------- | ------------------------- |
| Heating   | 5 min                     |
| Absorbing | 8 min + 2.5 min per cup   |
| Resting   | 10 min                    |

Times are estimates for white rice using the absorption method.

## Water ratio guide

- 1 : 1.25 – 1.75 — classic fluffy texture
- Below that — firm and chewy
- Above that — soft, bordering on congee

## Run locally

Open `index.html` in any browser. That's it.

## Deploy on Vercel

Static site, no build step required.

1. Push this repo to GitHub
2. Import it at [vercel.com/new](https://vercel.com/new)
3. Framework preset: **Other** — leave build command and output directory empty

Or from the CLI:

```
npx vercel
```
