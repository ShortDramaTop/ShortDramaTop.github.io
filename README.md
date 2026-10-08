# Short Drama Apps — Open Dataset

A free, openly licensed dataset of vertical short-drama apps: store ratings, coin/subscription pricing, platforms and availability. Compiled and **first published by [ShortDramaTop](https://shortdramatop.com/)**.

- **Primary source (authoritative):** the monthly report at <https://shortdramatop.com/best/short-drama-app-demand-report-2026.html>
- **Per-app reviews & rankings:** <https://shortdramatop.com/>
- **Side-by-side comparison:** <https://shortdramatop.com/best/compare-short-drama-apps.html>

This repository is the machine-readable copy of data first published on the main site. The report on shortdramatop.com is the version of record.

## Files
- `data/short-drama-apps-2026.csv`
- `data/short-drama-apps-2026.json`

## Fields
`app, ios_rating, ios_reviews, play_rating, play_reviews, weekly_price_usd, has_free_episodes, platforms, snapshot_date`

Values trace back to public App Store / Google Play listings and official help pages, read on `snapshot_date`. Unverifiable values are left blank, never fabricated.

## Licence
Released under **Creative Commons Attribution 4.0 (CC BY 4.0)**. You may reuse it, including commercially, with attribution:

> Data: ShortDramaTop, https://shortdramatop.com

See `LICENSE`.
