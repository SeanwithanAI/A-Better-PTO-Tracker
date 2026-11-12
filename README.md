<div align="center">

# A Better PTO Tracker

**Time Off Accrual Calendar: see what every day off will cost you before you book it**

![Version](https://img.shields.io/badge/version-2026--11--11%20mk4-6D28D9)
![Single file](https://img.shields.io/badge/single%20file-HTML-4338CA)
![No account needed](https://img.shields.io/badge/no%20sign--up-required-334155)
![PageVault ready](https://img.shields.io/badge/PageVault-ready-2563eb)

*by SeanwithanAI*

</div>

![Calendar: each day shows the projected balance of every time-off bank, with holidays, paydays and booked days marked](docs/screenshots/main.png)

---

## Overview

A Better PTO Tracker is a calendar that shows what each of your time-off **banks** will be worth on any date: **vacation, sick, comp time and personal holiday**. Book a day or half day and every future balance updates instantly, so you can plan a trip without running a bank negative. It's all in one HTML file, with nothing to install and no sign-up.

## Features

- **Four banks, each with its own rules.** Starting balance, how much accrues each pay period, an accrual cap, and the most you can carry into a new year.
- **Flexible schedules.** Accrue weekly, every 2 weeks, monthly or yearly. Comp time is earned per on-call cycle (for example, every 6 weeks), and personal holiday is granted each January 1.
- **A balance on every day.** Each calendar day shows the projected balance of every bank. Red means a bank has gone negative.
- **One-tap booking.** Pick a bank, tap a day to spend it, or turn on **½ day** (or Shift-click) for a half day. **Clear day** wipes a date.
- **Paydays and pay periods.** Paydays are outlined in green, and a thin marker shows where each pay period starts.
- **Holidays.** Choose a preset (Federal, MN State, Private Sector, City, and more) or add your own. Holidays are labels only and never change the math.
- **On-call weeks.** These can be highlighted; comp time posts at the start of each one.
- **Year-end rules.** On January 1, anything above a bank's carryover limit is dropped automatically.
- **Hours or days.** Count balances in hours or days, with your own length of a working day.
- **Backup and import.** Download a backup file and restore it on any device.
- **Day, Dark and Auto** themes.

## Screenshots

| Calendar | Bank settings |
|---|---|
| ![Monthly calendar with projected balances](docs/screenshots/main.png) | ![Settings for vacation, sick, comp time and personal holiday, plus anchor dates](docs/screenshots/settings.png) |

<sub>Screenshots use made-up example data.</sub>

## Getting started

1. Open `A-Better-PTO-Tracker-<date>-<mk>.html` in any modern browser, or open it from **PageVault**.
2. Under each bank, enter your **current balance**, how much you **accrue each period**, and any **cap** or **carryover limit**.
3. Under **Anchor dates**, set the date your balances are good as of, a recent pay-period start, and a recent payday.
4. Pick a **holiday schedule**, then start booking days off on the calendar.

## Where your data is stored

| Opened from… | Saved to | Status shown in the app |
|---|---|---|
| **PageVault** | Your own server only, separately for each signed-in person. Nothing is kept in the browser. | *Saved to your server* |
| **Claude** | Your Claude account, with this browser as a backup | *Saved to your account* |
| **A local file** | This browser only. The app reminds you every 7 days to download a backup. | *Saved on this device only* |

## Versioning

Every release is a new file named with the release date. The first release of a day is just the date; later releases that same day add `mk1`, `mk2`, `mk3`… (the count starts over each day), e.g. `A-Better-PTO-Tracker-2026-11-12.html`, then `A-Better-PTO-Tracker-2026-11-12-mk1.html`. The version also appears under the app's name. Older files stay in the repo, so PageVault can roll back to any of them.

| Version | Notes |
|---|---|
| **2026-11-11 mk4** | Shows where data is saved: *Saved to your server* in PageVault (no backup reminders there), *Saved on this device only* elsewhere. The last edit is now saved even if the page is closed right away. |
| **2026-11-11 mk3** | Previous release |

---

<div align="center"><sub>A Better PTO Tracker · Time Off Accrual Calendar · by SeanwithanAI · private repository</sub></div>
