# IQOS Scope

A single-page **WebHID** dashboard that reads live data from an **IQOS ILUMA i ONE** over USB — right in the browser.

**Live:** https://iqos-scope.vercel.app

## What it shows
- Identity: model code, serial number, firmware
- Live sensors: battery %, voltage, element temperature, error state, stick-inserted state
- Lifetime counters: sticks smoked, total puffs, usage time
- Settings: brightness, vibration, FlexPuff, FlexBattery, autostart, pause
- Spend estimate (set your pack price) + averages (puffs per stick, last-stick duration, cost per puff)

## Requirements
- **Chrome or Edge** on desktop (Safari/Firefox have no WebHID)
- The IQOS connected via USB cable to the same computer

## Privacy
Everything runs client-side via WebHID. No data ever leaves your machine — the page only talks to the device on your cable.

## Notes
- Tested only on **IQOS ILUMA i ONE**. Other models may not expose every field.
- Not affiliated with Philip Morris International / IQOS. For personal use.
