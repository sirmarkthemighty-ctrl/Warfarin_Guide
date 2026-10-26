# Warfarin Planner

A warfarin dosing tool for the clinic and the ward, by Warodom Phaenthong, M.D. It is one self-contained HTML page
(`warfarin-planner.html`, opened by `index.html`) that runs in the browser, with no installation and no patient data
sent anywhere.

It is a teaching aid for healthcare professionals, not a substitute for clinical judgement.

**Open it:** https://sirmarkthemighty-ctrl.github.io/Warfarin_Guide/

## What it does

**Simple view** (the default) is a pharmacy-counter calculator:

- Enter the total weekly dose; a row of +20% … −20% buttons shows each new weekly dose. An optional INR highlights the
  step from the Thai warfarin nomogram (Thai HA 2010), with hold-dose and vitamin K warnings.
- A Monday–Sunday table in Thai day colours with tablet pictures (1 mg white, 2 mg orange, 3 mg blue, 4 mg yellow,
  5 mg pink), the achievable weekly dose and real % change, the next INR date and the tablets to dispense until then.
- Pick the tablet strengths in stock and allow halves. Swap doses between days, or build the week tablet by tablet by
  dragging from the tablet tray (mouse or touch).
- TTR calculator (Rosendaal) from dated INRs, with ESC 2024 and NICE NG196 prompts.
- Thai / English switch, six sample cases, print and copy.

**Detailed view** covers the full plan: INR-guided dose adjustment, drug-interaction adjustment, when to stop before
procedures, and reversal with vitamin K, FFP and PCC, for OPD and IPD (CHEST 2012/2022, ASH 2018, ACC 2020,
AHA/ASA 2022).

Light and dark themes, collapsible colour-coded blocks, phone layout. Tap the version badge next to the title for the
changelog.

The same planner is also a tab of the [Cardio Care Suite](https://github.com/sirmarkthemighty-ctrl/CARDIO-SUITE).

## Licence

Copyright (c) 2026 Warodom Phaenthong, M.D. Licensed under
[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/): share and adapt for non-commercial use,
with credit, under the same licence. See `LICENSE` and `NOTICE`.
