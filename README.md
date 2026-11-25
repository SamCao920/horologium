# Horologium

**An editorial atlas and statistical study of daily routines and work habits across history.**

Horologium showcases reconstructed 24-hour schedules, work rituals, portraits, statistical patterns, and data-backed lessons drawn from **250 historical and modern figures**—spanning **Writers**, **Science & Medicine**, **Philosophers**, **Statesmen & Leaders**, and **Arts, Design & Music**.

## What the Data Shows (Time-Anchored Subset, n = 144)

- **The Prose Ceiling:** Time-anchored Writers log significantly fewer daily deep-work hours than Scientists despite nearly identical ~8-hour sleep.
- **The Night-Owl Paradox:** Contrary to 5 AM lore, Night Owls in the time-anchored subset log more daily deep-work hours than Early Birds.
- **Peripatetic Philosophers:** Philosophers average the most daily walking and physical movement of any discipline—nearly double Scientists.

## Features

- **Atlas & Filterable Directory** — Search and filter all 250 profiles by discipline, chronotype (*Early Bird*, *Night Owl*, *Biphasic Sleeper*), daily habits, and **Source Fidelity** (*Time-Anchored* vs. *Biographical Sketch*), or press `/` to jump straight to search.
- **24-Hour Timeline Comparison** — Stack up to three figures side by side along a synchronized 24-hour ruler with a live **NOW** clock indicator, **Shuffle 3** randomizer, and curated comparison trios.
- **Personal Schedule Overlay** — Toggle your own wake, work, and sleep times directly onto the timeline to measure live Deep Work and Sleep overlap against any figure, and export your custom routine as an `.ics` file.
- **Interactive Category Highlighting** — Click any activity swatch in the masthead (*Sleep*, *Deep Work*, *Exercise*, *Leisure*, *Meals*) to isolate that category across the entire archive.
- **Comprehensive Statistics Panel** — 20 live analytical modules with an **Analytical Sample Scope** toggle (*All 250* or *Time-Anchored Only*) covering sleep and deep-work histograms, a 24-hour collective activity curve, Sleep vs. Deep Work correlation (`r`), wake-up and bedtime distributions, deep-work session architecture, wake-to-work lag, Work-to-Sleep ratios, a 24-hour focus & movement density heatmap, habit lift analysis, percentile benchmarks (`P10`–`P90`), discipline & era matrices, and clickable archive extremes.
- **Lessons Panel** — Eight data-backed principles on focus, sleep, movement, chronotypes, rituals, and recovery distilled directly from the dataset, complete with live metrics, actionable rules, and clickable exemplars.
- **Detail Drawer, Portraits & Primary Citations** — Inspect any figure's portrait, hourly breakdown, work-ethic quote, historical context, primary source, and explicit estimation disclosure, with keyboard navigation (`←` / `→`) and URL hash deep-linking.
- **Calendar Export (`.ics`) & Bookmarks** — Generate and download RFC 5545 `.ics` calendar files for Google Calendar or Apple Calendar, and star favorite routines locally in the browser.

## Data Provenance & Methodology

Horologium builds on the foundational archival work of Mason Currey's *Daily Rituals* (2013) and *Daily Rituals: Women at Work* (2019), expanded with primary diaries, *The Paris Review* interviews, and biographies. Primary sources typically record core wake, work, exercise, and sleep anchors; surrounding meal and transition blocks are conservatively estimated to complete each 24-hour bar. Entries labeled **Time-Anchored** cite explicit clock times in their primary sources; **Biographical Sketch** entries reconstruct cadence from narrative descriptions.

## Tech Stack

Built as a single self-contained static site using HTML, Tailwind CSS, Chart.js, and vanilla JavaScript.

## License & Author

Built by [Fangyuan Cao](https://fangyuancao.me) in November 2026. Open source under the MIT License.
