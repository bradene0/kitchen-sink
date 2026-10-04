# Kitchen Sink

A complete pressure-washing game in a single HTML file.

Two cartoon hands rip the faucet off a kitchen sink, the broken faucet becomes your hose, and you blast the grime off a frying pan, an oven rack, a casserole dish, and finally the sink itself. There is no build step, framework, library, image file, audio file, backend, or installation. Open the HTML file and play.


## Play

[Launch Kitchen Sink](https://bradene0.github.io/kitchen-sink/)

## Features

* Four filthy objects: frying pan, oven rack, casserole dish, and the kitchen sink
* The sink unlocks once the other three are clean
* Three grime layers that behave differently: splatter, grease, and burnt-on crust
* Regions that chime and sparkle when they hit 100%
* A hidden detail under the grime on every object
* A glow on the last few specks so nobody gets stuck hunting
* Per-object timer and saved best times
* Faucet-ripping intro, skippable, shorter after the first visit
* Mouse and touch input
* All sound generated with Web Audio, with a mute button
* Haptic pulses where the browser supports vibration
* Reduced-motion support
* A controls panel listing every control and cheat code
* Five cheat codes: `JETCANNON`, `RAINBOW`, `SLOWMO`, `WIDELOAD`, `SMASHING`
* Persistent progress, best times, and mute setting using local storage, with a fallback when storage is unavailable
* Built-in self-checks for stamping, percent-clean math, grime layers, region completion, cheats, and storage

## Run Locally

You can open `index.html` directly in a browser.

On macOS:

```
open -a Safari index.html
```

If you want to serve it locally instead:

```
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

To run the self-checks, add `?test=1` to the address.



