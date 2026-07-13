# PHP Health Metrics Calculators

A set of standalone procedural-PHP calculators for common body/health metrics, originally built as page modules for [FitPatients.com](https://fitpatients.com).

## Calculators included

| File | Calculates |
|---|---|
| `bmiCalculator.php` | Body Mass Index from height (cm) and weight (kg) |
| `bmrMan.php` / `bmrWoman.php` | Basal Metabolic Rate (gender-specific formula) |
| `ibwCal.php` | Ideal Body Weight |
| `homaIR.php` | HOMA-IR insulin resistance index from fasting glucose + insulin |
| `insDose.php` | Daily bolus/basal insulin dose split for Type 1 diabetics |

Each page follows the same pattern: an HTML form submits via `GET`, the PHP block computes the result, and the result is echoed back on the same page.

## About this repository

These files are extracted directly from a live production site. They demonstrate the calculation logic and form-handling pattern in isolation; the shared layout includes (`header.php`, `footer.php`) and the site's CSS belong to the parent site and are not part of this repo, so the pages won't render standalone without supplying your own layout wrapper.

## Stack

PHP (procedural) · HTML forms

## Author

Ünal Zeray
