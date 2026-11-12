# AAPL Options Expiration Tracker

> Weekly tracking repository for Apple (AAPL) options expiration numbers, sourced from live Yahoo Finance data.

## Company Snapshot (Apple Inc. — AAPL)

| Field | Value |
|---|---|
| **Last street address** | One Apple Park Way, MS 927-4GC |
| **City** | Cupertino (CA 95014, United States) |
| **Sector** | Technology |
| **Industry** | Consumer Electronics |
| **Current share price** | $355.63 (USB, NasdaqGS) |
| **Market cap** | ~$5.17T |
| **52-week range** | $243.42 – $355.90 |
| **Analyst consensus** | Buy (mean 2.2, 40 analysts) |

## Expiration Map (available options expirations for AAPL)

2026-11-13, 2026-11-16, 2026-11-18, 2026-11-20, 2026-11-27, 2026-12-04, 2026-12-11, 2026-12-18, 2026-12-24, 2027-01-15, 2027-02-19, 2027-03-19, 2027-04-16, 2027-06-17, 2027-09-17, 2027-12-17, 2028-01-21, 2028-03-17, 2028-06-16, 2028-12-15, 2029-01-19

**Three soonest upcoming expirations tracked this week:** 2026-11-13, 2026-11-16, 2026-11-18.

## Per-Expiration Chain Stats

**Share price used for ATM calculation: $355.63**

| Expiration | ATM Strike | Highest-OI Call Strike (OI) | Highest-OI Put Strike (OI) |
|---|---|---|---|
| 2026-11-13 | $355 | $360 (16,819) | $360 (6,822) |
| 2026-11-16 | $355 | $355 (5,737) | $350 (359) |
| 2026-11-18 | $355 | $362.50 (7,037) | $350 (145) |

### Expiry 2026-11-13 (Friday)
- **ATM strike: $355** — closest strike to $355.63 (deviation 0.63)
- **Top call OI: $360** — AAPL261113C00360000, OI = 16,819
- **Top put OI: $360** — AAPL261113P00360000, OI = 6,822
- Notable call OI: $365 (11,856), $355 (11,813), $340 (6,356)
- Notable put OI: $340 (9,560), $330 (10,223), $350 (3,240)

### Expiry 2026-11-16 (Monday)
- **ATM strike: $355** — closest strike to $355.63 (deviation 0.63)
- **Top call OI: $355** — AAPL261116C00355000, OI = 5,737
- **Top put OI: $350** — AAPL261116P00350000, OI = 359
- Notable call OI: $350 (559), $360 (801)
- Notable put OI: $330 (1,537), $340 (1,175)

### Expiry 2026-11-18 (Wednesday)
- **ATM strike: $355** — closest strike to $355.63 (deviation 0.63)
- **Top call OI: $362.50** — AAPL261118C00362500, OI = 7,037
- **Top put OI: $350** — AAPL261118P00350000, OI = 145
- Notable call OI: $357.50 (5,043), $352.50 (2,176)
- Notable put OI: $355 (20), $360 (31)

## Tracking Issues

| Issue | Expiration | Title |
|---|---|---|
| #1 | 2026-11-13 | Expiry 2026-11-13 |
| #2 | 2026-11-16 | Expiry 2026-11-16 |
| #3 | 2026-11-18 | Expiry 2026-11-18 |

## Data Source & Methodology

- **Source:** Yahoo Finance (live data via MCP server) — company profile (`get_stock_info`), option expiration dates (`get_option_expiration_dates`), and full call/put option chains (`get_option_chain`) for each expiration.
- **ATM strike definition:** strike closest to the current share price of $355.63.
- **Top OI definition:** highest `openInterest` value on the respective side (calls or puts) of the chain for that expiration.
- All figures reported exactly as returned by the source; where values look unusual (e.g., very low put OI on 2026-11-18), they are reported as-is rather than smoothed.

## Repository

- **Repository URL:** https://github.com/mcpmark-eval-liuhezi/aapl-expiration-tracker-16
- **Default branch:** `main`
- **Tracking issues:** #1 (2026-11-13), #2 (2026-11-16), #3 (2026-11-18)
- **Pull request:** `add-expirations-markdown` → `main` (inos with EXPIRATION-map.md)
