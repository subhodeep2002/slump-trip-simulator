# Slump Trip Simulator

Replays real concrete truck trips reading by reading and shows how three slump formulas predict the slump of the concrete during the trip.

**Live site:** https://slumpsim.duckdns.org

## What it does

- Plays back the drum pressure, drum speed, direction, master pressure and dosing of each trip, in time lapse, with speeds from 1x to 600x.
- Runs three slump formulas side by side, each with its own inputs (plant slump, density or grade, drum radius, load volume).
- Shows each formula's live slump and drum pressure on a chart.
- Compares each formula's prediction with the site slump measured with the cone test.

## Trips

68 trips, oldest first, one reading per minute. Truck 1033 unless noted.

- Trips 1 to 20: June and July 2026.
- Trips 21 to 58: August and early September 2026, with the site cone test time.
- Trips 59 to 68: October 2026. Trips 62 and 63 are trucks 1037 and 1038 (24 October). Where the slump sheet has no site test time, the prediction is compared at the first discharge.

## Use

Open `index.html` in a browser, or visit the live site. Pick a trip at the top. The trip plays by itself. Use the speed buttons to fast forward, the slider to jump, space to pause, and the arrow keys to step one reading.
