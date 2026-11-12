# Contributing to aapl-expiration-tracker

Thanks for helping keep Apple (AAPL) options tracking data current and accurate.

## How to submit changes

1. Create a new branch from `main` (e.g. `add-<topic>`).
2. Make your changes (new file, update to `expirations.md`, or new tracking issues).
3. Open a pull request against `main`.
4. Keep market figures sourced from live data (Yahoo Finance via the desk's MCP tooling). If a number looks odd, report exactly what the source returned rather than silently correcting it.

## Tracking issues

Each upcoming expiration gets its own issue titled `Expiry YYYY-MM-DD`, containing that expiry's ATM strike, highest-open-interest call strike, highest-open-interest put strike, and the share price used.

## Repository

- URL: https://github.com/mcpmark-eval-liuhezi/aapl-expiration-tracker-16
- Default branch: `main`
- Key files: `expirations.md` (company snapshot, expiration map, per-expiration stats), `CONTRIBUTING.md` (this file).
