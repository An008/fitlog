# fitlog

Training and nutrition log for NC. Every row carries an ISO date (`YYYY-MM-DD`).
Tables are append-only and **chronological, oldest first** — so a later dashboard
can parse them in order without sorting.

**Started:** 2026-09-01 · **Last updated:** 2026-09-03

Conventions:
- Dates are ISO `YYYY-MM-DD`. No relative dates anywhere in this file.
- Blank cell = not recorded. `—` = not applicable.
- Units are fixed per column and never restated in cells.
- One observation per row. Never overwrite a row; append a correction as a new row.

---

## 1. Targets

Current as of 2026-09-01. Superseded targets move to §8.

| Metric | Target | Note |
|--------|--------|------|
| Calories | 1800 kcal/day | Weekly average is what counts, not the day |
| Protein | 140 g/day | Floor, not a target. Aim 140–160 |
| Fat | 60 g/day | Never below 50 |
| Carbs | ~175 g/day | Remainder of the budget |
| TDEE (est.) | 2200 kcal | **Unverified.** Recheck against waist trend after 2026-09-22 |
| Rate | 0.4 kg/week | Faster costs lean mass |

Goal: waist ~83 cm, body fat <20%, lean mass maintained or gained.
Projected: 14–20 weeks from 2026-09-01 → mid-Dec 2026 to mid-Jan 2027.

---

## 2. Weekly measurements

Protocol: Sunday morning, post-toilet, after one coffee, nothing else consumed.
Waist at navel. If two readings differ, record the **higher** one.

| date | weight_kg | waist_navel_cm | waist_belt_cm | note |
|------|-----------|----------------|---------------|------|
| 2026-07-25 | 72.6 | 93.5 | | |
| 2026-08-30 | 71.8 | 93.0 | 88.0 | belt-line reading approximate |
| 2026-09-06 | | | | scheduled |

Next scheduled: **2026-09-06**, then weekly on Sundays.

---

## 3. Daily weight

Protocol: every morning, post-toilet, after one coffee. Read the 7-day average,
never the single day.

| date | weight_kg | note |
|------|-----------|------|
| 2026-09-01 | 71.8 | baseline |
| 2026-09-02 | 72.2 | no bowel movement previous day — gut contents, not fat |
| 2026-09-03 | 71.7 | |

---

## 4. Runs

| date | type | dist_km | avg_pace | avg_hr | max_hr | cadence_spm | run_min | walk_min | kcal | note |
|------|------|---------|----------|--------|--------|-------------|---------|----------|------|------|
| 2026-08-25 | trail attempt | 2.37 | 7:50 | 146 | | | | | | fasted, cold, early, sore, no warm-up — cut short |
| 2026-08-27 | easy | 5.00 | 7:45 | 143 | | | | | | comfortable, nasal breathing throughout |
| 2026-08-31 | run/walk | 5.00 | 8:49 | 136 | 153 | | 31.0 | 20.6 | | walked to hold HR ≤145 |
| 2026-09-01 | easy continuous | 5.00 | 8:29 | 137 | 150 | 164 | 41.1 | 1.4 | 294 | evening, fed, warm. Held 137 continuously 42 min |
| 2026-09-03 | tempo (Runna) | 4.18 | 6:35 | 156 | 178 | | 27.5 | 0.1 | | No warm-up — went straight into effort. HR peaked 175 in first 10 min, then settled and drifted DOWN to a steady ~157 for the back half. 12k steps on the day including the run. Shins ok. |

Schedule: Tuesday, Thursday, Saturday.

---

## 5. Strength sessions

| date | session | movements_completed | note |
|------|---------|---------------------|------|
| | | | none logged yet |

---

## 6. Macros

| date | kcal | protein_g | fat_g | carbs_g | steps | note |
|------|------|-----------|-------|---------|-------|------|
| 2026-09-01 | 1900 | 153 | 52 | 222 | 21056 | 21k-step day — 1900 was if anything under-eating |
| 2026-09-02 | 1540 | 160 | 28 | 156 | 13103 | approx — 1388 logged plus 2 apples. Fat well under the 50 g floor. Fix by front-loading fat earlier in the day, not by eating late. |

---

## 7. Programme

### Weeks 1–2 (from 2026-09-01) — habit phase

Daily, ~10 min. Goal is never missing, not progressing. No added weight or reps.

| # | exercise | weight | sets × reps |
|---|----------|--------|-------------|
| 1 | Goblet squat | 10 kg | 3 × 10 |
| 2 | Push-ups | BW | 3 × 12 |
| 3 | Dead hang | BW | 3 × 25s |
| 4 | Dead bug | BW | 3 × 8/side |

Rest 60s. After the run on run days, never before.

### Trigger version — preferred, has worked before

| trigger | movement |
|---------|----------|
| After each pee | 5 push-ups (pull-ups also fine — near failure at max 3) |
| Before each meal | 20 push-ups |
| Passing the bar | Dead hang 25s |
| Before bed | Goblet squat ×10, dead bug ×8/side |

Note: push-up singles are useless (too far from failure at max 25). Pull-up
singles are not — 1–2 reps at a max of 3 is a real stimulus.

### From week 3 — alternating A/B, daily

**Day A — pull/legs**

| exercise | sets × reps |
|----------|-------------|
| Goblet squat | 4 × 12 |
| Renegade row | 3 × 8/side |
| Pull-up or negative | 4 × max |
| Suitcase carry 10 kg | 3 × 40s/side |

**Day B — push/power**

| exercise | sets × reps |
|----------|-------------|
| DB thruster | 4 × 10 |
| Push-up (explosive last set) | 4 × 12 |
| DB swing, two hands | 4 × 15 |
| Dead bug | 3 × 10/side |

| Mon | Tue | Wed | Thu | Fri | Sat | Sun |
|-----|-----|-----|-----|-----|-----|-----|
| A | Run | B | Run | A | Run | B / rest |

Progression: add reps to top of range, then add weight, reset reps.

---

## 8. Baseline tests

| date | test | result |
|------|------|--------|
| 2026-09-01 | Max push-ups | 25 |
| 2026-09-01 | Max pull-ups | 3 |
| 2026-09-01 | Plank hold | 50+ s |
| 2026-09-01 | Bodyweight squats / 60s | 40–45 |
| 2026-09-01 | Dead hang (gym bar, thin) | 40+ s |
| 2026-09-01 | Dead hang (home bar, thick foam) | ~30 s |
| 2026-09-01 | Toe touch, slow and controlled | reaches ankles only |
| 2026-09-01 | Overhead reach supine, right | full, elbow and hand to floor |
| 2026-09-01 | Overhead reach supine, left | restricted, elbow elevated, pain at end range |
| 2026-09-01 | Max pike push-ups | not tested |
| 2026-09-01 | Single-leg balance, eyes closed | not tested |

Anthropometrics at baseline: height 164–165 cm, age 40, male.

---

## 9. Constraints

| constraint | detail | status |
|------------|--------|--------|
| Left shoulder | Old clavicle fracture, surgical repair with poor result, no rehab. Left side favoured for years. Restricted and painful at end-range overhead. | No loaded overhead pressing. Thrusters to forehead height only. Physio not booked. |
| Shins | Flare with faster running. Load-tolerance issue, not fitness. | Abort a session if they start talking. Gates the 30-min test. |
| Sleep | 5–6 h. Bed 00:00–02:00, wake 06:00–08:00. | Biggest limiter on the whole plan. Highest-leverage fix available. |

---

## 10. Open items

| item | status |
|------|--------|
| 30-min field test for LTHR | Lower priority after 2026-09-03 gave a usable estimate. Still worth doing properly for a clean number. Method: 15 min warm-up, run 30 min hard and even, lap at 10:00, avg HR of minutes 10–30 = LTHR. Do on a day the shins are quiet. |
| HR zones | **Largely resolved by the 2026-09-03 tempo.** Held avg 156 for 27:33 with HR drifting down in the back half — that is a de facto threshold effort. Estimated **LTHR 158–162**, giving zone 2 ≈ **128–145**, zone 3 ≈ 146–151, threshold ≈ 156–162. The nasal-breathing evidence was right; the age-formula estimate (zone 2 ceiling 139) was too low. Train easy at 138–145. |
| Cadence | 164, slightly low. Nudge toward 170 in short blocks — efficiency gain and less shin load. |
| TDEE verification | Recheck after 2026-09-22. If waist hasn't moved on honest logging, drop to 1650 kcal. |
| Physio for left shoulder | Not booked. Determines whether overhead work is permanently excluded or trainable. |

---

## 11. Observations

| date | observation |
|------|-------------|
| 2026-09-01 | Conditions dominate run quality more than fitness does. Fasted + cold + early = higher HR, worse session (2026-08-25). Evening + fed + warm = best session so far (2026-09-01). |
| 2026-09-01 | Between 2026-07-25 and 2026-08-30: weight 72.6 → 71.8 kg (-0.8), waist 93.5 → 93.0 cm (-0.5). Both moving, slowly and together. ~0.15 kg/week — under the 0.4 target, so the summer deficit was smaller than intended. |
| 2026-09-02 | Normal daily steps 10–14k. 2026-09-01's 21k was unusual and does not change the TDEE estimate. |
| 2026-09-03 | Tempo run errors to avoid repeating: no warm-up, and the first 10 min were run at interval intensity (peak 175) rather than tempo. Correct shape is 10 min easy, 15–20 min at 150–156, 5–10 min easy. |
