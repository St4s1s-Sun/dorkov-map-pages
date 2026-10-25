# Dorkov Map

Hosted player preview: https://st4s1s-sun.github.io/dorkov-map-pages/

This repository contains the prebuilt Player delivery selected for publication on 2026-10-25. The dataset is a hypothetical preview, not a claim of completed in-game verification.

GitHub Pages publishes the root of `main`. No application build is required here. The supplied data directory is served as `packs/`, matching the frontend transport URL. The PWA and assets use relative paths for repository hosting.

For frontend updates, replace only frontend files. For data updates, retain older immutable releases and artwork under `packs/`, add the new payloads, and update `packs/current.json` in the same deployment commit. Keep developer datasets, observations, private reports, and personal saves out of this repository.
