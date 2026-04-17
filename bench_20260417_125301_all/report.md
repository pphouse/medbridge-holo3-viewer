# Holo3 Benchmark Report — 20260417_125301_all

- Patient: 00000001
- Screens: 6
- Time: 2026-04-17T12:53:01.372798 → 2026-04-17T13:05:07.075569

## Summary

| Metric | Value |
|---|---|
| Grounding hit rate | **0.844** (27/32) |
| Mean pixel distance | **149.1 px** |
| OCR mean recall | **0.667** |

## Per-screen

### login

- Grounding: 2/2

![login](annotated/login.png)

### patient_list

- Grounding: 6/6

![patient_list](annotated/patient_list.png)

### karte

- Grounding: 5/6

![karte](annotated/karte.png)

### labs

- Grounding: 5/6
- OCR[lab_results]: 6/6 (recall 1.00)

![labs](annotated/labs.png)

### meds

- Grounding: 5/6
- OCR[medications]: 1/1 (recall 1.00)

![meds](annotated/meds.png)

### diagnoses

- Grounding: 4/6
- OCR[diagnoses]: 0/2 (recall 0.00)

![diagnoses](annotated/diagnoses.png)
