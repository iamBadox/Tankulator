# Changelog

All notable changes to Tankulator will be documented here.

---

## [1.3.0] – 2026-03-27

### Changed
- Input fields now accept Swedish number format — use commas as decimal separator (e.g. 10,50 instead of 10.50)
- Both comma and dot accepted so it works regardless of keyboard

---

## [1.2.0] – 2026-03-27

### Added
- Info icon (ℹ) next to "Trip breakdown" — hover to see a full explanation of how each value is calculated
- Tooltip explains the fuel, wear & tear, and total formulas
- Wear & tear rate attributed to Transportstyrelsen with a link

---

## [1.1.0] – 2026-03-27

### Added
- Wear & tear automatically calculated at the Swedish tax authority rate (1.85 kr/km)
- Rate displayed inline in the breakdown so users know where the number comes from
- Total cost now includes both fuel cost and wear & tear

---

## [1.0.0] – 2026-03-27

### Added
- Initial release
- Input: distance (km), fuel consumption (L/mil), fuel price (kr/L)
- Breakdown: mils driven, litres consumed, fuel price
- Total trip cost in kr
- Numbers formatted Swedish-style (e.g. 1 234,56 kr)
- Press Enter or click Calculate to run
- Dark-themed, single HTML file — no install required
