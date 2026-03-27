# Changelog

All notable changes to Tankulator will be documented here.

---

## [3.1.0] – 2026-03-27

### Changed
- Result now shows two totals:
  - **Cost excl. wear & tear** — fuel/energy cost only
  - **Total cost (incl. wear & tear)** — the full amount, highlighted in orange
- Works across all modes (⛽ fuel, ⚡ electric) and both languages (🇸🇪 🇬🇧)

---

## [3.0.0] – 2026-03-27

### Added
- ⚡ Electric car mode — toggle between ⛽ Fuel and ⚡ Electric using the pill button top left
- EV mode uses kWh/mil for consumption and kr/kWh for electricity price
- EV result row shows "Energy used (kWh)" instead of "Fuel consumed (L)"
- EV tooltip explains the calculation in both Swedish and English
- Swedish EV tooltip notes that wear & tear applies to electric cars too
- App icon in the title updates to match the selected mode

### Changed
- Mode toggle and language flags now sit in the same top bar

---

## [2.0.0] – 2026-03-27

### Added
- 🇸🇪 / 🇬🇧 flag switcher in the top right corner — click to toggle language
- Full Swedish translation across all labels, hints, buttons, error messages, and results
- Full English translation as an alternative
- Swedish tooltip: explains calculations in Swedish, references Transportstyrelsen & Skatteverket
- English tooltip: references the Swedish Transport Agency (Transportstyrelsen) in English
- Results re-render automatically when switching language
- App boots in Swedish by default

### Changed
- Output numbers now formatted per locale (Swedish: commas, English: dots)

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
